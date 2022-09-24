# Crear proyecto en netbeans


## 1. Crear proyecto maven web aplication

![image](https://user-images.githubusercontent.com/31961588/192114602-91d33377-8e4f-46af-bad3-5f2d83e146a9.png)


## 2. Validar configuración de la propiedades del proyecto

### 2.1

![image](https://user-images.githubusercontent.com/31961588/192114869-9e3692c5-c6a6-48c9-9767-f3dce6a765fb.png)

### 2.3 

![image](https://user-images.githubusercontent.com/31961588/192114916-ca26089c-7d58-4e80-8e3c-1a534511d264.png)

### 2.4

![image](https://user-images.githubusercontent.com/31961588/192114950-12cf828f-05b2-47a7-8ca9-c3435eb05370.png)

# Configurar las dependencias en el poom.xml

![image](https://user-images.githubusercontent.com/31961588/192115134-12863b91-e70c-40dc-a1a7-eb240e4b54e5.png)

A continuación se proporciona el archivo poo.xml que se configuro para el proyecto. 

```Xml
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>

    <groupId>UtsPractica</groupId>
    <artifactId>AppSaldosSab</artifactId>
    <version>1.0</version>
    <packaging>war</packaging>

    <name>AppSaldosSab</name>

    <properties>
        <endorsed.dir>${project.build.directory}/endorsed</endorsed.dir>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    </properties>
    
    <dependencies>
        <dependency>
            <groupId>javax</groupId>
            <artifactId>javaee-web-api</artifactId>
            <version>8.0.1</version>
            <scope>provided</scope>
        </dependency>
        <dependency>
            <groupId>mysql</groupId>
            <artifactId>mysql-connector-java</artifactId>
            <version>8.0.30</version>
        </dependency>

    </dependencies>

    <build>
        <plugins>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-compiler-plugin</artifactId>
                <version>3.1</version>
                <configuration>
                    <source>1.8</source>
                    <target>1.8</target>
                    <compilerArguments>
                        <endorseddirs>${endorsed.dir}</endorseddirs>
                    </compilerArguments>
                </configuration>
            </plugin>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-war-plugin</artifactId>
                <version>2.3</version>
                <configuration>
                    <failOnMissingWebXml>false</failOnMissingWebXml>
                </configuration>
            </plugin>
            
        </plugins>
    </build>

</project>

```

## 4. Clean and Build

### 4.1

![image](https://user-images.githubusercontent.com/31961588/192115267-21b575d3-d159-4173-b3ce-5c7554381954.png)

### 4.2 

![image](https://user-images.githubusercontent.com/31961588/192115303-61f95c87-259e-4b07-9e48-375b850d5215.png)


# Study with Me :)

* [1. Hello Backend!](#1-hello-backend๐)
  * [1.1. ์ ํ๋ ์์ํฌ๋ฅผ ์ฐ๋์?](#11-์-ํ๋ ์์ํฌ๋ฅผ-์ฐ๋์)
  * [1.2. ํ๋ ์์ํฌ๋ ์ด๋ป๊ฒ ๊ตฌ์ฑ๋๋์?](#12-ํ๋ ์์ํฌ๋-์ด๋ป๊ฒ-๊ตฌ์ฑ๋๋์)
    * [1.2.1. ๋์์ธ ํจํด](#121-๋์์ธ-ํจํด)
    * [1.2.2. ๋ผ์ด๋ธ๋ฌ๋ฆฌ](#122-๋ผ์ด๋ธ๋ฌ๋ฆฌ)
  * [1.3. Spring๊ณผ IntelliJ](#13-spring๊ณผ-intellij)
    * [1.3.1. Spring์ ์ฅ์ ](#131-spring์-์ฅ์ )
    * [1.3.2. IntelliJ Idea](#132-intellij-idea)
  * [1.4. Gradle](#14-gradle)
    * [1.4.1. Gradle Build Lifecycle](#141-gradle-build-lifecycle)
    * [1.4.2. Gradle ์ฌ์ฉ๋ฒ](#142-gradle-์ฌ์ฉ๋ฒ)
      * [Plugin](#-plugin)
      * [Repository](#-repository)
      * [Dependency](#-dependency)
      * [Test](#-test)
* [2. Testcode](#2-testcode)
  * [2.1. ํ์คํธ์ฝ๋๋ฅผ ์ ์์ฑํด์ผ ํ๋์?](#21-ํ์คํธ์ฝ๋๋ฅผ-์-์์ฑํด์ผ-ํ๋์)
  * [2.2. Spring boot ํ์คํธ์ฝ๋๋ ์ด๋ป๊ฒ ์์ฑํด์ผ ํ๋์?](#22-spring-boot-ํ์คํธ์ฝ๋๋-์ด๋ป๊ฒ-์์ฑํด์ผ-ํ๋์)
    * [2.2.1. Given-when-then](#221-given-when-then)
    * [2.2.2. Given-when-then ์ฐ์ต](#222-given-when-then-์ฐ์ต)
  * [2.3. Lombok์ผ๋ก ์๋ฐ๋ฅผ ๋ ํธํ๊ฒ ์จ๋ด์๋ค](#23-lombok์ผ๋ก-์๋ฐ๋ฅผ-๋-ํธํ๊ฒ-์จ๋ด์๋ค)
* [3. Java Persistence Api](#3-java-persistence-api)
  * [3.1. JPA๊ฐ ๋ฌด์์ธ๊ฐ์?](#31-jpa๊ฐ-๋ฌด์์ธ๊ฐ์)
  * [3.2. JPA๋ฅผ ์ ์ฉํด๋ด์๋ค](#32-jpa๋ฅผ-์ ์ฉํด๋ด์๋ค)
  * [3.3. ๊ฒ์๊ธ ๋ฑ๋ก API๋ฅผ ๋ง๋ค์ด๋ด์๋ค](#33-๊ฒ์๊ธ-๋ฑ๋ก-api๋ฅผ-๋ง๋ค์ด๋ด์๋ค)
  * [3.4. ํ์คํธ ์ฝ๋๋ก JPA๊ฐ ์ ๋์๊ฐ๋์ง ํ์ธํด๋ณผ๊น์?](#34-ํ์คํธ-์ฝ๋๋ก-jpa๊ฐ-์-๋์๊ฐ๋์ง-ํ์ธํด๋ณผ๊น์)
* [4. Template Engine](#4-template-engine)
  * [4.1. Server Side vs Client Side](#41-server-side-vs-client-side)
    * [4.1.1. Server Side Template Engine](#411-server-side-template-engine)
    * [4.1.2. Client Side Template Engine](#412-client-side-template-engine)
  * [4.2. Mustache](#42-mustache)
  * [4.3. Mustache๋ฅผ ์ฌ์ฉํด๋ด์๋ค](#43-mustache๋ฅผ-์ฌ์ฉํด๋ด์๋ค)
* [5. References](#5-references)

## 1. Hello Backend!๐

### 1.1. ์ ํ๋ ์์ํฌ๋ฅผ ์ฐ๋์?

์ํํธ์จ์ด์  ๊ด์ ์์ **ํ๋ ์์ํฌ**๋ ์ ํ๋ฆฌ์ผ์ด์์ ๋ง๋ค๊ธฐ ์ํ ํฐ ํ๊ณผ๋ ๊ฐ์ต๋๋ค.
์ฑ์ ๊ณจ๊ฒฉ์ ํ๋ ์์ํฌ๋ก๋ถํฐ ๋น๋ ค์ด๋ค๋ฉด ๊ฐ๋ฐ์๋ ๊ตฌํํด์ผ ํ๋ ํต์ฌ ๋ก์ง์๋ง ์ง์คํ  ์ ์์ต๋๋ค.
> ํ๋ ์์ํฌ์ ํจ๊ป๋ผ๋ฉด, ๋ ์คํ ๋์ ์ฐํ์๊ฒ๋ ์ฌ๋ฃ ์๊ธ์ด๋ ๋งค์ฅ ๊ด๋ฆฌ์ ์ ๊ฒฝ์ธ ํ์ ์์ด ์๋ฆฌ๋ง ํ  ์ ์๋ ํ๊ฒฝ์ด ์ฃผ์ด์ง๋๋ค.
>
> ํ๋ ์์ํฌ์ ํจ๊ป๋ผ๋ฉด, ๊ฐ๋ฐ์์๊ฒ๋ XML ์ค์ ๊ณผ WAS ์ค์น ๋ฑ์ ์ ๊ฒฝ์ธ ํ์ ์์ด ๋ก์ง์ ์ง๋ ๊ฒ์๋ง ์ง์คํ  ์ ์๋ ํ๊ฒฝ์ด ์ฃผ์ด์ง๋๋ค.

### 1.2. ํ๋ ์์ํฌ๋ ์ด๋ป๊ฒ ๊ตฌ์ฑ๋๋์?

ํ๋ ์์ํฌ๋ **๋์์ธ ํจํด๊ณผ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ฅผ ๋ชจ์ ํ๋ก๊ทธ๋จ ํํ๋ก ๋ง๋  ๊ฒ**์๋๋ค.
> ํ๋ ์์ํฌ = ๋์์ธํจํด + ๋ผ์ด๋ธ๋ฌ๋ฆฌ

#### 1.2.1. ๋์์ธ ํจํด

**๋์์ธ ํจํด์ ๊ฐ์ฒด ์งํฅ ์ค๊ณ๋ฅผ ์ํ ์ ํํ๋ ์ค๊ณ ๋ฐฉ๋ฒ์๋๋ค.**
๊ฐ์ฒด์งํฅ ์ธ์ด๋ก ๋์ด์ค๋ฉฐ ๊ฐ๋ฐ์๊ฐ ๋ง๋ฅ๋จ๋ฆด ์ ์๋ ๋ฌธ์ ๋ฅผ ํผํ๊ธฐ ์ํด ๋ฌด์์ ๊ฐ์ฒด๋ก ์ ํ ์ง, ๊ฐ์ฒด ๊ฐ ๊ด๊ณ๋ฅผ ์ด๋ป๊ฒ ์ ํ ์ง๊ฐ ์ค์ํด์ก์ต๋๋ค.
๋์์ธ ํจํด์ ์ฝ๋๋ฅผ ์ฒ์ ๋ณด๋ ์ฌ๋๋ ์ค๊ณ์ ๋ชฉ์ , ์ฉ๋, ๊ตฌํ ๋ฐฉ๋ฒ์ ์ฝ๊ฒ ์ดํดํ๊ณ  ๊ฐ๋ฐํ  ์ ์๋๋ก ๋์ต๋๋ค.

#### 1.2.2. ๋ผ์ด๋ธ๋ฌ๋ฆฌ

**๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ ํ๋ก๊ทธ๋จ์ ๊ตฌ์ฑ์์๋ก ๊ณตํต์ผ๋ก ์ฌ์ฉ๋  ์ ์๋ ํน์  ๊ธฐ๋ฅ๋ค์ ๋ชจ๋ํํ ๊ฒ์๋๋ค.**
์ค๋ณต๋ ์ฝ๋๋ฅผ ๋ฐ๋ณตํด์ ์์ฑํ์ง ์๋๋ก ํ๊ธฐ ์ํด ์ฌ์ฌ์ฉํ  ์ ์๋๋ก ๋ง๋ค์ด๋ ์ ์์ต๋๋ค.

### 1.3. Spring๊ณผ IntelliJ

#### 1.3.1. Spring์ ์ฅ์ 

* ๋ณต์กํ์ง ์์ต๋๋ค.
  * ์ ํ๋ฆฌ์ผ์ด์ ๊ธฐ๋ณธ ์ค์ ์ด ๊ฐํธํฉ๋๋ค.
* ํ๋ก์ ํธ ์ ์ฒด ๊ตฌ์กฐ ์ค๊ณ์ ์ ์ฉํฉ๋๋ค.
  * ์คํ๋ง์ ์น, ๋ฐ์ดํฐ๋ฒ ์ด์ค ๋ฑ ์ด๋ ํ ๋ถ์ผ์๋ง ์ง์คํ์ง ์๊ณ  ์ ์ฒด๋ฅผ ์ค๊ณํ๋ ์ฉ๋๋ก ์ฌ์ฉํ  ์ ์์ต๋๋ค.
* ๋ค๋ฅธ ํ๋ ์์ํฌ๋ฅผ ํฌ์ฉํฉ๋๋ค.
  * ๋ค๋ฅธ ํ๋ ์์ํฌ์์ ์์์ ์ถ๊ตฌํ๋ฏ๋ก ์ต์ํ์ ์์ ์ผ๋ก ์ฌ๋ฌ ์ข๋ฅ์ ํ๋ ์์ํฌ๋ฅผ ํผ์ฉํด์ ์ธ ์ ์์ต๋๋ค.
* ๊ฐ๋ฐ ์์ฐ์ฑ์ด ์ข์ต๋๋ค.
  * XML ์ค์ ์ ์ด์ฉํด ์ ์ง๋ณด์๊ฐ ์ฉ์ดํ๊ณ  ์ฌ๋ฌ ํ๋ฌ๊ทธ์ธ์ ์ง์ํด ์๋ก์ด ๊ฐ๋ฐ ๋๊ตฌ์ ๋ํ ๋ณ๋์ ์ ์ ์์ด๋ ๊ฐ๋ฐ์ด ๊ฐ๋ฅํฉ๋๋ค.

๊ทธ ์ค **Spring Boot๋ ์คํ๋ง์ ํ๋ก์ ํธ ์ค ํ๋๋ก, ์ค์ ์ด ์ต์ํ๋์ด ๊ฐ๋จํ ์คํํ  ์ ์๋ค๋ ์ฅ์ ์ด ์์ต๋๋ค.**
๋ฒ์ ๊ด๋ฆฌ๊ฐ ์ฝ๊ณ  JUnit ๋ฑ ํ์คํธ ๊ด๋ จ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ค์ด ํฌํจ๋์ด ์์ด ํ์คํธ ์ผ์ด์ค๋ฅผ ์ฝ๊ฒ ์์ฑํ  ์ ์์ต๋๋ค.
JAR ํ์ผ๋ก ํจํค์งํด์ ์ฌ์ฉํ  ์ ์์ด ๋น ๋ฅด๊ฒ ์ดํ๋ฆฌ์ผ์ด์์ ๊ฐ๋ฐํ๋ ๋ฐ์๋ ํจ๊ณผ์ ์๋๋ค.

~~์ ๊ฐ์ ๋ฐฑ๋ฆฐ์ด๋ ์คํ๋ง๋ถํธ ํ๋ค์ด ์ ์ผ ๋ฎ์์ ์ฌ์ฉํฉ๋๋ค...~~

#### 1.3.2. IntelliJ Idea

IntelliJ๋ ๋ํ์ ์ธ ์๋ฐ ์น ๊ฐ๋ฐ๋๊ตฌ์๋๋ค.

Eclipse vs IntelliJ

* ์ถ์ฒ ๊ธฐ๋ฅ์ด ๊ฐ๋ ฅํฉ๋๋ค.
* ๋ฆฌํฉํ ๋ง๊ณผ ๋๋ฒ๊น ๊ธฐ๋ฅ์ด ๋ค์ํฉ๋๋ค.
* ๊น ์์ ๋๊ฐ ๋์ต๋๋ค.
* ํ์ผ์ ๋น๋กฏํ ์์ ๊ฒ์์ด ๋น ๋ฆ๋๋ค.
* ์๋ฐ์ ์คํ๋ง๋ถํธ ๋ฒ์ ์์ ๋ง์ถ์ด ์๋ฐ์ดํธ๊ฐ ๋น ๋ฆ๋๋ค.
* ๋ํ์์ด์๋ฉด ์ ฏ๋ธ๋ ์ธ ํํ์ด์ง์ ๊ฐ์ํ๊ณ  ์น๋ฉ์ผ ์ธ์ฆ ํ ultimate ๋ฒ์ ์ ๋ฌด๋ฃ๋ก ์ฌ์ฉํ์ค ์ ์์ต๋๋ค.

### 1.4. Gradle

**Gradle์ Groovy ๊ธฐ๋ฐ์ ์คํ์์ค ๋น๋ ๋๊ตฌ์๋๋ค.**
Ant์ ์ ์ฐ์ฑ๊ณผ Maven์ ํธ๋ฆฌ์ฑ์ ์กฐํฉํด XML์ ๋ํ ์ด์๋ Groovy๋ฅผ ์ฌ์ฉํด ํด๊ฒฐํ  ์ ์์ต๋๋ค.
gradle์ Maven์์ ์ข์ข ๋ฐ์ํ๋ ๋ผ์ด๋ธ๋ฌ๋ฆฌ ๋ฒ์  ๋ฌธ์ , ์ถฉ๋ ๋ฌธ์  ๋ฑ์ ํด๊ฒฐํฉ๋๋ค.

#### 1.4.1. Gradle Build Lifecycle

1. Initialization: ๋น๋ ๋์ ํ๋ก์ ํธ ๊ฒฐ์  ํ ๊ฐ Project ๊ฐ์ฒด๋ฅผ ์์ฑํ๊ณ 
setting.gradle ํ์ผ์์ ํ๋ก์ ํธ๋ฅผ ๊ตฌ์ฑ
2. Configuration: ๋น๋ ๋์์ด ๋๋ ๋ชจ๋  ํ๋ก์ ํธ์ ๋น๋ ์คํฌ๋ฆฝํธ๋ฅผ ์คํ
3. Execution: ๊ตฌ์ฑ ๋จ๊ณ์์ ์์ฑ/์ค์ ๋ ํ๋ก์ ํธ์ task ์ค ์คํ ๋์์ ๊ฒฐ์ 

#### 1.4.2. Gradle ์ฌ์ฉ๋ฒ

์ฐ์  build.gradle ํ์ผ์ ๋น๋์ ๋ณด๋ฅผ ์ ์ํฉ๋๋ค.
๊ทธ ๋ค์ ํ๋ก์ ํธ์์ ์ฌ์ฉํ๋ ํ๊ฒฝ์ค์ , ๋น๋๋ฐฉ๋ฒ, ๋ผ์ด๋ธ๋ฌ๋ฆฌ ์ ๋ณด ๋ฑ์ ๊ธฐ์ ํด ๋น๋ ๋ฐ ํ๋ก์ ํธ์ ๊ด๋ฆฌํ๊ฒฝ์ ๊ตฌ์ฑํฉ๋๋ค.

##### Plugin

ํ๋ฌ๊ทธ์ธ์ ์ ์ฉํจ์ผ๋ก์จ ํ๋ก์ ํธ๋ฅผ ํ์ฅํ  ์ ์์ต๋๋ค.
ํ๋ฌ๊ทธ์ธ์ ์ฌ์ฌ์ฉ์ ์ด์งํ๊ณ  ๋ ๋์ ์์ค์ ๋ชจ๋ํ๋ฅผ ํ์ฉํฉ๋๋ค.
๊ธฐ์กด์๋ apply plugin์ ์ฌ์ฉํ์ง๋ง [๊ณต์ ํํ์ด์ง](https://url.kr/1e6ioq)์์๋
Gradle์ด ๋ ์์ ํ๊ฒ ์คํํ  ์ ์๋๋ก plugins๋ฅผ ์ฌ์ฉํ๋ ๊ฒ์ ์งํฅํฉ๋๋ค.

๊ธฐ์กด ๋ฐฉ๋ฒ

```gradle
apply plugin: 'java'
apply plugin: 'eclipse'
apply plugin: 'org.springframework.boot'
apply plugin: 'io.spring.dependency-management'
```

๊ฐ์  ๋ฐฉ๋ฒ

```gradle
plugins {
    id 'java'
    id 'eclipse'
    id 'org.springframework.boot' version '2.1.7.RELEASE'
    id 'io.spring.dependency-management' version '1.0.9.RELEASE'
}
```

##### Repository

![์์กด์ฑ ๊ด๋ฆฌ ๋ชจ์๋](https://docs.gradle.org/current/userguide/img/dependency-management-resolution.png)

**repository๋ ์ํํธ์จ์ด๋ฅผ ๋ฑ๋กํ์ ๊ด๋ฆฌํ๋ ์ฅ์๋ฅผ ๊ฐ๋ฆฌํต๋๋ค.**
๋ก์ปฌ ํ๊ฒฝ์ด๋ ๋คํธ์ํฌ์ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ฅผ ๊ณต๊ฐํ๊ณ  ๊ทธ ์ฃผ์๋ฅผ ์ ์ฅ์๋ก ๋ฑ๋กํ๋ฉด ์ ์ฅ์์ ์๋ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ฅผ gradle์ด ์ทจ๋ํด ์ด์ฉํ  ์ ์์ต๋๋ค.
๋ง์ฝ ์ค์์ ์ฅ์์ ๊ณต๊ฐ๋์ง ์๊ฑฐ๋ ์ฌ๋ด์์๋ง ์ฌ์ฉํ๋ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๊ฐ ์์ ๊ฒฝ์ฐ ๋ก์ปฌ ์ ์ฅ์๋ฅผ ์ด์ฉํ๋ฉด ๋ฉ๋๋ค.
์๋ฅผ ๋ค์ด ์๋๋ mavenCentral()๊ณผ jcenter()๋ฅผ ์ฌ์ฉํด ๋ ์ ์ฅ์๋ฅผ ์ด์ฉํ๋ ์ฝ๋์๋๋ค.

```gradle
repositories {
    mavenCentral()
    jcenter()
}
```

##### Dependency

**dependency๋ ์์กด์ฑ์ ๊ดํ ์ค์ ์ ๊ด๋ฆฌํ๋ ํ๋กํผํฐ์๋๋ค.**
ํ์ํ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ฅผ ๊ธฐ์ ํ๋ฉด ํด๋น ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ฅผ ์ฐธ์กฐํ  ์ ์์ต๋๋ค.
๊ธฐ๋ณธ์ ์ผ๋ก group, name, version ์์ผ๋ก ์์กด์ฑ์ ๊ธฐ์ ํ์ง๋ง group:name:version์ผ๋ก ์ถ์ฝํด ์ธ ์ ์์ต๋๋ค.
๋ง์ฝ ext ๋ธ๋ก์ผ๋ก ๋ฒ์ ์ ์ ์ด๋๋ฉด dependency์ version ์ ๋ณด๋ฅผ ์๋ตํด๋ ์๋์ผ๋ก ์ ์ฉ๋ฉ๋๋ค.

```gradle
dependencies {
    // ๊ธฐ๋ณธํ
    compile group: 'org.hibernate', name: 'hibernate-core', version: '3.6.7.Final'
    // ์ถ์ฝํ
    compile 'org.hibernate:hibernate-core:3.6.7.Final'
}
```

##### Test

gradle์ ํตํด์ ํ์คํธ ๋ํ ๊ฐํธํ๊ฒ ํ  ์ ์์ต๋๋ค.
gradle์ test์์ ํน์  ํ์คํธ๋ง ์งํํ  ์ ์์ต๋๋ค.
์๋๋ jUnit์ ์ฌ์ฉํ๊ธฐ ์ํ ์ฝ๋์๋๋ค.
~~์ ๋ ๊ธ์ฐ๋๊ฒ ์ง์ณ์๊ฐ ์๋๋ผ~~ ํ์คํธ ์ฝ๋์ ๋ํด์๋ ๋ค์ ์ฅ์์ ๋ ๊ณต๋ถํด๋ณด๋ ค ํฉ๋๋ค.

```gradle
test {
    useJUnitPlatform()
}
```

## 2. Testcode

### 2.1. ํ์คํธ์ฝ๋๋ฅผ ์ ์์ฑํด์ผ ํ๋์?

์์ฆ์ ๊ฐ๋ฐ์์ **ํ์คํธ๋ ํ์**์ ์๋๋ค. ์ด๋ฒ์ฃผ์ ์ ๋ Junit4๋ฅผ ์ฌ์ฉํด ํ์คํธํ๋ ๋ฐฉ๋ฒ์ ์ตํ์ต๋๋ค.

* ๋จ์ ํ์คํธ๋ ๊ฐ๋ฐ๋จ๊ณ ์ด๊ธฐ์ ๋ฌธ์ ๋ฅผ ๋ฐ๊ฒฌํ๊ฒ ๋์์ค๋๋ค.
* ๋จ์ ํ์คํธ๋ฅผ ํ๋ฉด ๊ฐ๋ฐ์๊ฐ ๋์ค์ ์ฝ๋๋ฅผ ๋ฆฌํฉํ ๋งํ๊ฑฐ๋ ๋ผ์ด๋ธ๋ฌ๋ฆฌ ์๊ทธ๋ ์ด๋ ๋ฑ์์ ๊ธฐ์กด ๊ธฐ๋ฅ์ด ์ฌ๋ฐ๋ฅด๊ฒ ์๋ํ๋์ง ํ์ธํ  ์ ์์ต๋๋ค.
* ๋จ์ ํ์คํธ๋ ๊ธฐ๋ฅ์ ๋ํ ๋ถํ์ค์ฑ์ ๊ฐ์์ํฌ ์ ์์ต๋๋ค.

### 2.2. Spring boot ํ์คํธ์ฝ๋๋ ์ด๋ป๊ฒ ์์ฑํด์ผ ํ๋์?

#### 2.2.1. Given-when-then

ํ์คํธ ์ฝ๋๋ ์ผ๋ฐ์ ์ผ๋ก given-when-then ํ์์ผ๋ก ์์ฑํฉ๋๋ค.
given ๋จ๊ณ์์ ํ์คํธ๋ฅผ ์ํด ์ค๋นํ๊ณ  when ๋จ๊ณ์์ ์ค์ ๋ก ์ก์ํ๋ ํ์คํธ๋ฅผ ์คํํ ํ then ๋จ๊ณ์์ ํ์คํธ๋ฅผ ๊ฒ์ฆํฉ๋๋ค.

#### 2.2.2. Given-when-then ์ฐ์ต

์ด๋ฒ ์ฃผ์ ์ค์ตํ๋ ๊ฒ์๊ธ์ด ์ ๋๋ก ์ ์ฅ๋์๋์ง ํ์ธํ๊ณ  ๋ถ๋ฌ์ค๋ ์ฝ๋์๋๋ค.

```java
// given
String title = "ํ์คํธ ๊ฒ์๊ธ";
String content = "ํ์คํธ ๋ณธ๋ฌธ";

postsRepository.save(Posts.builder()
    .title(title)
    .content(content)
    .author("ei654028@gmail.com")
    .build());

// when
List<Posts> postsList = postsRepository.findAll();

//then
Posts posts = postsList.get(0);
assertThat(posts.getTitle()).isEqualTo(title);
assertThat(posts.getContent()).isEqualTo(content);
```

### 2.3. Lombok์ผ๋ก ์๋ฐ๋ฅผ ๋ ํธํ๊ฒ ์จ๋ด์๋ค

**Lombok์ ์๋ฐ์์ DTO, Domain ๋ฑ์ ๋ง๋ค ๋ ๋ฐ๋ณต์ ์ผ๋ก ๋ง๋ค์ด์ผ ํ๋ ๋ฉค๋ฒ ํ๋ ์์ฑ์ ์ฝ๋๋ฅผ ์ค์ด๋ ๋ผ์ด๋ธ๋ฌ๋ฆฌ ์๋๋ค.**
Getter, Setter, ToString ๋ฑ ๋ค์ํ ์ฝ๋๋ฅผ ์๋์์ฑ ํด ์ค๋๋ค.
lombok์ ์ ์ฉํ๋ฉด ์ฝ๋์ ๊ฐ๋์ฑ์ด ๋์์ ธ ์ผ๋ช ์ฝ๋ ๋ค์ด์ดํธ๋ก ๋ถ๋ฆฌ๊ธฐ๋ ํฉ๋๋ค.

## 3. Java Persistence Api

### 3.1. JPA๊ฐ ๋ฌด์์ธ๊ฐ์?

**Java Persistence Api๋ ์๋ฐ ORM ๊ธฐ์ ์ ๋ํ API ์๋๋ค.**
๋ณธ๊ฒฉ์ ์ผ๋ก ๊ฐ์ฒด์งํฅ ๊ฐ๋ฐ์ ํ๊ฒ ๋๋ฉด์ ์ ํ๋ฆฌ์ผ์ด์์ ๊ฐ์ฒด์งํฅ ์ธ์ด์ ๊ด๊ณํ DB๋ก ๊ตฌ์ฑ๋์์ต๋๋ค.

๊ทธ๋ฌ๋ ์ด ์กฐํฉ์ ์๋ฐ ๊ฐ์ฒด๋ฅผ SQL๋ก, SQL์ ์๋ฐ ๊ฐ์ฒด๋ก ๋ฐ๊พธ๋ ๊ณผ์ ์ด ๋ฐ๋ณต๋์ด ์ง๋ฃจํ ์ฝ๋๊ฐ ๋ฐ๋ณต๋๋ค๋ ๋ฌธ์ ๊ฐ ์์์ต๋๋ค.
๋๋ถ์ด ์๋ฐ์ SQL๊ฐ์๋ **ํจ๋ฌ๋ค์ ๋ถ์ผ์น ๋ฌธ์ **๊ฐ ์กด์ฌํฉ๋๋ค.
์๋ฐ๋ ์ถ์ํ, ์บก์ํ, ์ ๋ณด ์๋์ ํตํด ๊ฐ์ฒด์ ๊ธฐ๋ฅ๊ณผ ์์ฑ์ ํ ๊ณณ์์ ๊ด๋ฆฌํ๋ ค๋ ํจ๋ฌ๋ค์์ ๊ฐ์ง๋๋ค.
๋ฐ๋ฉด ๊ด๊ณํ DB๋ ์ด๋ป๊ฒ ๋ฐ์ดํฐ๋ฅผ ์ ์ฅํ ์ง์ ์ง์คํ ๊ธฐ์ ์ด๋ฏ๋ก ๊ฐ๋ฐ์๋ค์ ์ ์ฐจ ๋ฐ์ดํฐ๋ฒ ์ด์ค ๋ชจ๋ธ๋ง์ ์น์คํ๊ฒ ๋์์ต๋๋ค.

JPA๋ ๊ฐ๋ฐ์๊ฐ ๊ฐ์ฒด์งํฅ์ ์ผ๋ก ํ๋ก๊ทธ๋๋ฐํ ๊ฒ์ ๊ด๊ณํ ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ๊ฑธ๋ง๊ฒ ๋์  SQL๋ฌธ์ ์์ฑํด์ ์คํํฉ๋๋ค.
๋ฐ๋ผ์ JPA๋ฅผ ์ฌ์ฉํ ํ๋ก๊ทธ๋จ์ ์์ฐ์ฑ์ด ๋์์ง๊ณ  ์ ์ง๋ณด์๊ฐ ์ฌ์์ก์ต๋๋ค.

### 3.2. JPA๋ฅผ ์ ์ฉํด๋ด์๋ค

JPA๋ ์ธํฐํ์ด์ค์ด๋ฏ๋ก ์ด๋ฅผ ์ฌ์ฉํ๊ธฐ ์ํด ๊ตฌํ์ฒด๊ฐ ํ์ํฉ๋๋ค(e.g., Hibernate, Eclipse Link).
๋ํ ๊ตฌํ์ฒด๋ฅผ ๋์ฑ ์ฝ๊ฒ ์ฌ์ฉํ๊ธฐ ์ํด Spring Data JPA๋ผ๋ ๋ชจ๋์ ์ฌ์ฉํฉ๋๋ค.
> JPA <- Hibernate <- Spring Data JPA

๋ํ ๋ชจ๋์ ์ฌ์ฉํ๋ฉด Spring Data JPA๋ Hibernate ์ธ์ ๋ค๋ฅธ ๊ตฌํ์ฒด๋ก ๊ต์ฒดํ๋ ์์๊ณผ
๊ด๊ณํ ๋ฐ์ดํฐ๋ฒ ์ด์ค ์ธ์ ๋ค๋ฅธ ์ ์ฅ์(e.g., MongoDB)๋ก ๊ต์ฒดํ๋ ์์์ ์ค๋ฒํค๋๋ฅผ ์ค์ฌ์ค๋๋ค.

### 3.3. ๊ฒ์๊ธ ๋ฑ๋ก API๋ฅผ ๋ง๋ค์ด๋ด์๋ค

๊ฒ์๊ธ ๋ฑ๋ก ๊ธฐ๋ฅ์ ๋ง๋ค๊ธฐ ์ํด ์๋ ์ธ ํ์ผ์ ๋ง๋ค์ด์ผ ํ์ต๋๋ค.

* web ํจํค์ง ๋ด์ PostApiController.java
* web.dto ํจํค์ง ๋ด์ PostsSaveRequestDto.java
* service.posts ํจํค์ง ๋ด์ PostsService.java

~~์์ฝ๊ฒ๋ ๋๋ ํ ๋ฆฌ ๊ตฌ์กฐ๊ฐ ์ ์ด๋ ๊ฒ ๋์ด์ผ ํ๋์ง,
๊ฐ ํด๋์ค๊ฐ ์ด๋ค ์ญํ ์ ํ๋์ง ์จ์ ํ ํ์ํ์ง ๋ชปํด์ ๋ชจ๋ ์ ๋ฆฌํ์ง ๋ชปํ  ๊ฒ ๊ฐ์ต๋๋ค.
์ถํ์ ๋ด์ฉ ์ถ๊ฐํ๊ฒ ์ต๋๋ค.~~

### 3.4. ํ์คํธ ์ฝ๋๋ก JPA๊ฐ ์ ๋์๊ฐ๋์ง ํ์ธํด๋ณผ๊น์?

์ ๋ ์คํ๋ง ๋ถํธ ํ๋ก์ ํธ์ test ํด๋ ๋ด์ ์์ ์ฐ์ตํ๋ given-when-then ๋ฐฉ์์ผ๋ก ํ์คํธ ์ฝ๋๋ฅผ ์์ฑํ์ต๋๋ค.

```java
 @Test
    public void Posts_๋ฑ๋ก๋๋ค() throws Exception{
        //given
        String title = "title";
        String content = "content";

        PostsSaveRequestDto requestDto =
                PostsSaveRequestDto.builder()
                    .title(title)
                    .content(content)
                    .author("author")
                    .build();

        String url = "http://localhost:"+port+"/api/v1/posts";

        //when
        ResponseEntity<Long> responseEntity = restTemplate
            .postForEntity(url, requestDto, Long.class);

        //then
        assertThat(responseEntity.getStatusCode()).isEqualTo(HttpStatus.OK);
        assertThat(responseEntity.getBody()).isGreaterThan(0L);
        List<Posts> all = postsRepository.findAll();
        assertThat(all.get(0).getTitle()).isEqualTo(title);
        assertThat(all.get(0).getContent()).isEqualTo(content);
    }
```

## 4. Template Engine

**ํํ๋ฆฟ ์์ง์ด๋ ํํ๋ฆฟ ์์๊ณผ ํน์  ๋ฐ์ดํฐ ๋ชจ๋ธ์ ๋ฐ๋ฅธ ์๋ ฅ ์๋ฃ๋ฅผ ํฉ์ฑํด ๊ฒฐ๊ณผ ๋ฌธ์๋ฅผ ์ถ๋ ฅํ๋ ์ํํธ์จ์ด๋ฅผ ๋งํฉ๋๋ค.**
๊ทธ ์ค ์น ํํ๋ฆฟ ์์ง์ด๋ ์น ํํ๋ฆฟ๊ณผ ์ปจํ์ธ  ์ ๋ณด๋ฅผ ์ฒ๋ฆฌํ๊ธฐ ์ํด ์ค๊ณ๋ ์ํํธ์จ์ด์๋๋ค.
๋๋ถ๋ถ์ ํํ๋ฆฟ ์์ง์ html๋ณด๋ค ๊ฐ๋จํ ๋ฌธ๋ฒ์ ์ฌ์ฉํ๊ณ  ์ฌ์ฌ์ฉ์ฑ์ด ๋์ต๋๋ค.
๋ํ ํ๋์ ํํ๋ฆฟ์ผ๋ก ์ฌ๋ฌ ํ์ด์ง๋ฅผ ๋ ๋๋งํ  ์ ์์ต๋๋ค.

### 4.1. Server Side vs Client Side

#### 4.1.1. Server Side Template Engine

**์๋ฒ ์ฌ์ด๋ ํํ๋ฆฟ ์์ง์ DB ํน์ API์์ ๊ฐ์ ธ์จ ๋ฐ์ดํฐ๋ฅผ ๋ฏธ๋ฆฌ ์ ์๋ ํํ๋ฆฟ์ ๋ฃ์ด ์๋ฒ์์ html์ ๊ทธ๋ฆฝ๋๋ค.**
html ์ฝ๋์์ ๊ณ ์ ์ ์ผ๋ก ์ฌ์ฉ๋๋ ๋ถ๋ถ์ ํํ๋ฆฟ์ผ๋ก ๋ง๋ค์ด๋๊ณ  ๋์ ์ผ๋ก ์์ฑ๋๋ ๋ถ๋ถ๋ง ํํ๋ฆฟ์ ์์ค ์ฝ๋๋ฅผ ๋ผ์๋ฃ๋ ๋ฐฉ์์ผ๋ก ๋์ํฉ๋๋ค.

#### 4.1.2. Client Side Template Engine

html ํํ๋ก ์ฝ๋๋ฅผ ์์ฑํด ๋์ ์ผ๋ก DOM์ ๊ทธ๋ฆฌ๊ฒ ํด์ฃผ๋ ์ญํ ์ ํฉ๋๋ค.
ํด๋ผ์ด์ธํธ์์๋ ๊ณตํต์ ์ธ ํ๋ ์์ ๋ฏธ๋ฆฌ ํํ๋ฆฟ์ผ๋ก ๋ง๋ค๊ณ  ์๋ฒ์์ ํ์ํ ๋ฐ์ดํฐ๋ฅผ ๋ฐ์ ์ ์ ํ ์์น์ replaceํฉ๋๋ค.

### 4.2. Mustache

์ ๋ Spring Boot ํ๋ก์ ํธ์ Mustache๋ผ๋ ๋งํฌ์ ์ธ์ด๋ฅผ ์ฌ์ฉํ  ๊ฒ์๋๋ค.
"์คํ๋ง ๋ถํธ์ AWS๋ก ํผ์ ๊ตฌํํ๋ ์น์๋น์ค"์์๋ mustache๋ฅผ ์ฌ์ฉํ๋ ์ด์ ๋ฅผ ๋ค์๊ณผ ๊ฐ์ด ์๊ฐํฉ๋๋ค.

* mustache๋ ์๋ง์ ์ธ์ด๋ฅผ ์ง์ํ๋ ๊ฐ์ฅ ์ฌํํ ํํ๋ฆฟ ์์ง์๋๋ค.
* ๋ฌธ๋ฒ์ด ๋ค๋ฅธ ํํ๋ฆฟ ์์ง๋ณด๋ค ์ฌํํฉ๋๋ค.
* ๋ก์ง ์ฝ๋๋ฅผ ์ฌ์ฉํ  ์ ์์ด View์ ์๋ฒ์ ์ญํ ์ด ๋ชํํ๊ฒ ๋ถ๋ฆฌ๋ฉ๋๋ค.
๋ง์ฝ ํํ๋ฆฟ ์์ง์์ ๋๋ฌด ๋ง์ ๊ธฐ๋ฅ์ ์ ๊ณตํ๋ฉด api, ํํ๋ฆฟ ์์ง, js๊ฐ ์๋ก ๋ก์ง์ ๋๋ ๊ฐ์ ธ ์ ์ง๋ณด์๊ฐ ์ด๋ ค์์ง๋ค๋ ๋จ์ ์ด ์์ต๋๋ค.
* mustach.js์ mustache.java๋ฅผ ๋ ๋ค ์ง์ํด, ํ๋์ ๋ฌธ๋ฒ์ผ๋ก ํด๋ผ์ด์ธํธ/์๋ฒ ํํ๋ฆฟ์ผ๋ก ๋ชจ๋ ์ฌ์ฉ ๊ฐ๋ฅํฉ๋๋ค.

### 4.3. Mustache๋ฅผ ์ฌ์ฉํด๋ด์๋ค

๋ฐ๋ณต์ ์ผ๋ก ์ฌ์ฉ๋๋ ์ฝ๋๋ ๋ณ๋์ ํ์ผ๋ก ๋ถ๋ฆฌํ์ฌ ํ์ํ ๊ณณ์์ ๊ฐ์ ธ๋ค์ฐ๋๋ก ๋ ์ด์์ ๋ฐฉ์์ผ๋ก ์ถ๊ฐํฉ๋๋ค.
์ ๋ ์ฑ์ ๋ฐ๋ผ header์ footer ํ์ผ์ ๋ง๋ค์์ต๋๋ค.

* css๋ ํ๋ฉด์ ๊ทธ๋ฆฌ๋ ์ญํ ์ด๋ฏ๋ก ๋จผ์  ๋ก๋ฉ์ํค๊ธฐ ์ํด header์์ ๋ถ๋ฆ๋๋ค.
* js๋ ์ฉ๋์ด ํด์๋ก ๋ก๋ฉ์ด ๋๋ ค body ๋ถ๋ถ์ ์คํ์ด ๋ฆ์ด์ง๊ธฐ ๋๋ฌธ์ footer์ ๋ก๋๋ค.
* bootstrap.js์ jquery.js์ ์์กดํ๊ธฐ ๋๋ฌธ์ footer ๋ด์์๋ ์๋์ ์์นํฉ๋๋ค.

```mustache
//header.mustache
<!DOCTYPE HTML>
<html>
<head>
    <title>์คํ๋ง๋ถํธ ์น์๋น์ค</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />

    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</head>
<body>
```

```mustache
//footer.mustache
<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

<!--index.js ์ถ๊ฐ-->
<script src="/js/app/index.js"></script>
</body>
</html>
```

์ด์  mustache ํ์ผ์ ์ด์ฉํด html์ ๊ตฌ์ฑํด๋ด์๋ค. ์ฝ๋์ ์ฌ์ฌ์ฉ์ฑ์ด ๋์์ก์ต๋๋ค.

```mustache
{{>layout/header}}

<h1> ์๋ํ์ธ์ ์ฌ๋ฌ๋ถ! </h1>

{{>layout/footer}}
```

## 5. References

Section 1

* <https://elevatingcodingclub.tistory.com/25>
* <https://futurecreator.github.io/2016/06/18/spring-boot-get-started/>
* <https://mckdh.tistory.com/entry/%EA%B0%9D%EC%B2%B4%EC%A7%80%ED%96%A5%EC%9D%98-%ED%83%84%EC%83%9D-%EB%94%94%EC%9E%90%EC%9D%B8%ED%8C%A8%ED%84%B4%EA%B3%BC-%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC>
* <https://freestrokes.tistory.com/79>
* <https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:dev3.6:dep:build_tool:gradle>
* <https://madplay.github.io/post/what-is-gradle>
* <https://willbesoon.tistory.com/93>
* <https://docs.gradle.org/current/userguide/plugins.html>
* <https://doughman.tistory.com/19>
* <https://webfirewood.tistory.com/129>
* <https://docs.gradle.org/current/userguide/core_dependency_management.html>
* <https://limdevbasic.tistory.com/12>
* <https://docs.gradle.org/current/userguide/java_testing.html>

Section 2

* <https://brunch.co.kr/@springboot/418>
* <https://martinfowler.com/bliki/GivenWhenThen.html>
* <https://woowabros.github.io/study/2018/03/01/spock-test.html>
* <https://brunch.co.kr/@springboot/292>
* <https://goddaehee.tistory.com/95>

Section 3

* <https://velog.io/@adam2/JPA%EB%8A%94-%EB%8F%84%EB%8D%B0%EC%B2%B4-%EB%AD%98%EA%B9%8C-orm-%EC%98%81%EC%86%8D%EC%84%B1-hibernate-spring-data-jpa>
* <https://gmlwjd9405.github.io/2019/08/03/reason-why-use-jpa.html>

Section 4

* <https://gmlwjd9405.github.io/2018/12/21/template-engine.html>
* <https://insight-bgh.tistory.com/252>

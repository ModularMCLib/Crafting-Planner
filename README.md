<h1 align="center">Crafting Planner</h1>

<p align="center">
  使用 Kotlin 和 Java 的合成规划库。<br>
  A Kotlin-first JVM library for crafting planning.
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-AGPL--3.0-blue?style=for-the-badge" alt="License"></a>
  <a href="https://discord.gg/HwnF3RTPtH"><img src="https://img.shields.io/badge/Discord-Join-5865F2?logo=discord&amp;logoColor=white&amp;style=for-the-badge" alt="Discord"></a>
</p>

<p align="center">
  <a href="#简体中文">简体中文</a> · <a href="#english">English</a>
</p>

## 分支 / Branches

| 分支 / Branch | Java | 模块 / Module |
| --- | --- | --- |
| [`main`](https://github.com/ModularMCLib/Crafting-Planner/tree/main) | `21` | `core` |

## 简体中文

Crafting Planner 是 Kotlin 优先的 JVM 规划库，可与 Java 源码混编，用于承载共享领域类型、请求与结果契约、验证逻辑和后端 SPI。

首期 Gradle 模块为 `core`。后续将 JVM 规划实现提取到 Core 契约之后，再添加 `backend-jvm` 模块。

### 环境要求

- JDK 21
- Gradle Wrapper 从系统环境变量 `GRADLE_USER_HOME` 读取缓存路径

### 构建

```powershell
.\gradlew.bat :core:assemble
```

## English

Crafting Planner is a Kotlin-first JVM library that supports mixed Kotlin and Java sources. It defines shared domain types, request and result contracts, validation, and a backend SPI.

The initial Gradle module is `core`. A `backend-jvm` module is planned once the JVM planner is separated from the core contracts.

### Requirements

- JDK 21
- The Gradle Wrapper uses the `GRADLE_USER_HOME` environment variable for its cache.

### Build

```powershell
.\gradlew.bat :core:assemble
```

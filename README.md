# Crafting Planner

Crafting Planner 是独立的 Java 规划库，用于承载共享领域类型、请求与结果契约、验证逻辑和后端 SPI。

首期 Gradle 模块为 `core`。后续将 JVM 规划实现提取到 Core 契约之后，再添加 `backend-jvm` 模块。

## 环境要求

- JDK 21
- Gradle Wrapper 从系统环境变量 `GRADLE_USER_HOME` 读取缓存路径

## 构建

```powershell
.\gradlew.bat :core:assemble
```

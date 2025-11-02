MopClient V1.0.0 构建指南

1. 确保你已在 FCL 或电脑上安装了 Java 17。
2. 在项目根目录下使用 Gradle Wrapper 构建：
   - Linux / macOS / FCL：
       ./gradlew build
   - Windows：
       gradlew.bat build
3. 构建完成后，生成的 jar 文件在：
       build/libs/MopClient-1.0.0.jar
4. 将 jar 文件放入 Minecraft 的 mods 文件夹即可。
5. 若使用 FCL，可直接在终端进入项目目录执行：
       ./gradlew build
   FCL 已内置 JDK 17 和 Gradle Wrapper。
6. 项目结构：
   MopClient/
   ├─ build.gradle
   ├─ gradle.properties
   ├─ settings.gradle
   ├─ gradlew
   ├─ gradlew.bat
   ├─ gradle/ (Gradle Wrapper 相关)
   └─ src/main/...

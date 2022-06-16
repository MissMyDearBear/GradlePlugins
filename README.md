## 自定义GradlePlugin

### 自动生成工程
```
# 在HelloPlugin目录下，使用 gradle init 命令创建构建
$ gradle init

Select type of project to generate:
  1: basic
  2: application
  3: library
  4: Gradle plugin
  
# 🤤😍🤩 我们要的东西出现了，选4 Gradle 插件
Enter selection (default: basic) [1..4] 4

Select implementation language:
# 实现语言我们选择 Groovy，你可以选择你自己熟悉的语言
  1: Groovy
  2: Java
  3: Kotlin
Enter selection (default: Java) [1..3] 1

# DSL(Domain-specific language 特定领域语言)，也就是我们编译脚本语言，我们同样选 Groovy
Select build script DSL:
  1: Groovy
  2: Kotlin
Enter selection (default: Groovy) [1..2] 1

Project name (default: hello):
Source package (default: hello): com.bear.plugin
```

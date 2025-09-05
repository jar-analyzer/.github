# Jar Analyzer

Jar Analyzer

- 一个 `JAR` 包分析工具
- 完善美观的 `GUI` 支持（现代化 `Java GUI` 界面，可拖拽，明暗橙三主题，十种风格）
- 基础分析（支持 `Jar/War/Classes` 输入，支持多文件，支持嵌套 `FatJar`）
- 黑白名单配置（构建数据库和搜索功能都支持黑白名单过滤，支持精确类名和包名过滤）
- 反编译（内置 `Fernflower` 改进版本双击反编译，使用 `JavaParser` 精确定位方法位置）
- 方法调用关系搜索（构建方法调用关系数据库，可搜方法定义与方法引用，支持精确和模糊搜索）
- 方法调用链 `DFS` 算法分析（支持 **正向/反向** 调用链分析，基于 `DFS` 算法的深度调用链追踪）
- 简单的模拟 `JVM` 污点分析实现，可验证 `DFS` 算法推导方法调用链可行性（beta）
- 字符串搜索（搜索 `LDC` 指令，支持模糊搜索和精确搜索，可定位具体方法，联动调用进行分析）
- `Java Web` 组件入口分析（`Java Servlet/Filter` 组件分析，`Spring` 入口信息一键分析）
- `CFG` 程序分析（方法内部控制流可视化，基本块划分与展示，异常处理流程分析）
- `JVM` 栈帧分析（局部变量表与操作数栈状态跟踪，运行时数据流静态分析）
- 自定义表达式搜索（基于 `SpEL` 的多种语法组合搜索，用于搜索漏洞 `Gadget` 等）
- 常见安全分析功能（支持简单的 `SCA` 分析，敏感信息泄漏分析，可能的 `gadget` 分析）
- 应急响应分析功能（一键提取序列化数据中的恶意 `class` 反编译，一键提取 `BCEL` 代码）
- 测试功能：不同于 `IDEA` 等工具的源码级调试，实现了字节码级别的单步动态调试（仅初步实现）

项目

- [Jar Analyzer V2](https://github.com/jar-analyzer/jar-analyzer) (主要开发维护，保持长期更新)
- [Class Obfuscator](https://github.com/4ra1n/class-obf) (有空时维护，保持长期更新)
- [Jar Obfuscator V2](https://github.com/jar-analyzer/jar-obfuscator) (作者精力有限，暂不维护)
- [Jar Analyzer V1 GUI](https://github.com/jar-analyzer/jar-analyzer-v1-gui) (已有 V2 新版本，老版本不再维护)
- [Jar Analyzer V1 CLI](https://github.com/jar-analyzer/jar-analyzer-v1-cli) (已有 V2 新版本，老版本不再维护)

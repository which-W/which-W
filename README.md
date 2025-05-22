## Hi there 👋

# <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="36" height="36" alt="C++" /> 突出C++专业性的项目集展示

在当今的软件开发领域，C++ 以其高效、灵活和强大的性能，始终占据着重要的地位。本项目集充分展示了本人在C++领域的专业能力和丰富经验，涵盖了从基础语法学习到实际项目开发的多个方面。下面将为您详细介绍各个项目。

## 项目总览

| 项目名称                                                     | 功能                                                         | 技术栈                       | 项目链接                                            |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------- | --------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="18" height="18" alt="C++" /> CPP_learn | 记录学习C++的基础语法，STL，网络编程，并发编程，QT等内容。包含基础C++知识和相关stl使用，以及一些简单项目的储存。2025/3/2 添加部分聊天系统内容，完成部分的ui设计，注册页面的代码基本完成。 | C++                          | [CPP_learn](https://github.com/which-W/CPP_learn)   |
| <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="18" height="18" alt="C++" /> LogSystem | 一个基于C++的异步日志系统，采用多生产者单消费者模型，日志文件过大时会自动划分，支持文件输出和终端输出两种功能。后续计划添加多消费者，多线程并发处理日志队列消息。 | C++（89.5%）、CMake（10.5%） | [LogSystem](https://github.com/which-W/LogSystem)   |
| <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="18" height="18" alt="C++" /> TaskSystem | 一个简单的任务处理系统，可当作任务处理的基础。通过nlomann的json库保存文件，将用户输入的任务长久保存；通过字符串在终端输入任务，采用CRTP的多态方法；使用Wrapper包裹，让Command可以通过CRTP的方式绑定相关TaskManager函数；实现日志多消费者，多线程并发处理日志。 | C++（99.9%）、CMake（0.1%）  | [TaskSystem](https://github.com/which-W/TaskSystem) |

## 项目详细介绍

### <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="24" height="24" alt="C++" /> CPP_learn

#### 项目简介

CPP_learn 项目是本人学习C++过程中的知识宝库，它记录了从基础语法到高级特性的学习历程。通过这个项目，不仅可以系统地回顾C++的核心知识，还能看到如何将这些知识应用到实际的小项目中。例如，在2025年3月2日，项目中添加了部分聊天系统的内容，完成了部分UI设计，注册页面的代码也基本完成，这展示了对C++在网络编程和界面设计方面的应用能力。

#### 功能特点

- **全面的知识覆盖**：涵盖了C++的基础语法、标准模板库（STL）、网络编程、并发编程以及QT等多个重要领域。
- **实际项目应用**：包含了一些简单的项目实例，帮助理解如何将理论知识应用到实际开发中。
- **持续更新**：随着学习的深入，项目会不断添加新的内容和功能。

### <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="24" height="24" alt="C++" /> LogSystem

#### 项目简介

LogSystem 是一个基于C++开发的异步日志系统，它采用了多生产者单消费者模型，能够高效地处理日志记录。当日志文件过大时，系统会自动进行划分，确保日志管理的高效性。同时，该系统支持文件输出和终端输出两种方式，方便不同场景下的使用。

#### 功能特点

- **异步处理**：采用多生产者单消费者模型，提高了日志记录的效率，减少了对主线程的影响。
- **自动划分**：当日志文件达到一定大小时，系统会自动进行划分，避免文件过大导致的管理困难。
- **多输出方式**：支持文件输出和终端输出两种方式，满足不同用户的需求。
- **可扩展性**：后续计划添加多消费者和多线程并发处理日志队列消息的功能，进一步提升系统的性能。

### <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="24" height="24" alt="C++" /> TaskSystem

#### 项目简介

TaskSystem 是一个简单而实用的任务处理系统，它可以作为任务处理的基础框架。通过使用nlomann的json库，系统能够将用户输入的任务长久保存。在任务处理方面，采用了CRTP的多态方法，并使用Wrapper包裹，让Command可以通过CRTP的方式绑定相关TaskManager函数，实现了日志的多消费者和多线程并发处理。

#### 功能特点

- **持久化存储**：通过json库将用户输入的任务保存到文件中，确保任务数据的持久化。
- **多态处理**：采用CRTP的多态方法，提高了代码的灵活性和可维护性。
- **并发处理**：实现了日志的多消费者和多线程并发处理，提升了系统的性能。

## 安装步骤

由于各个项目的依赖和环境要求可能不同，具体的安装步骤请参考各个项目的README文件。一般来说，可能需要安装C++编译器、CMake等工具。
 <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cmake-colored.svg" width="18" height="18" alt="CMake" />

## 使用方法

同样，各个项目的使用方法也有所不同。请参考各个项目的README文件，里面会有详细的使用说明和示例。
 <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/terminal-colored.svg" width="18" height="18" alt="Terminal" />

## 贡献指南

如果您对这些项目感兴趣，并希望参与贡献，欢迎按照以下步骤进行：

1. Fork本项目。
2. 创建一个新分支: `git checkout -b feature - branch`。
3. 提交代码: `git commit -m "Add new feature"`。
4. 推送到分支: `git push origin feature - branch`。
5. 发起Pull Request。
   <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" width="18" height="18" alt="Git" />

## 许可证信息

本项目集遵循[MIT许可证](https://opensource.org/licenses/MIT)，您可以自由使用、修改和分发这些项目，但请保留许可证信息。
 <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/license-colored.svg" width="18" height="18" alt="License" />

## 总结

通过这些项目，充分展示了本人在C++领域的专业能力和技术水平。从基础语法的学习到实际项目的开发，每一个项目都凝聚了对C++的深入理解和实践经验。希望这些项目能够对您有所帮助，也欢迎您提出宝贵的意见和建议。

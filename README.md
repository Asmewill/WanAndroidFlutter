# wan_android_flutter

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.



## 项目运行环境

1. Flutter version 3.32.8

2. Dart version 3.8.1

3. JDK 17

## 常用命令
1.flutter clean

2.flutter pub get

3.flutter run


GetX 是 Flutter 的一个超轻量且强大的解决方案，它不仅仅是状态管

## GetX理库，而是一个完整的应用架构框架。它整合了高性能状态管理、
智能依赖注入和便捷路由管理三大核心功能，旨在解决传统 Flutter 开发中的多个痛点.

⚡️ 状态管理：实现响应式编程，状态变化时自动更新 UI。它不依赖 BuildContext，让状态管理更独立。相比 setState、BLoC 等方案，
GetX 的代码更简洁，样板代码极少。

🧩 依赖注入 (DI)：GetX 使用 Get.put() 注入实例，用 Get.find() 获取，无需 BuildContext。它支持懒加载，即用即创建，
并在不用时自动从内存中移除，有效管理资源，避免内存泄漏。

🧭 路由管理：导航无需 BuildContext，只需 Get.to(NextPage())。它还支持中间件、命名路由、动态URL参数等高级功能，同时提供
Snackbar、Dialog、BottomSheet的简易调用方法。

额外功能丰富：GetX 还提供国际化、主题切换、本地存储 (GetStorage)、工具类 (GetUtils)等内置功能
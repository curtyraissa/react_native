# React Native Fundamentals

React Native is an open-source framework that allows you to create mobile apps for iOS and Android using JavaScript and React. It enables code sharing across platforms, providing a native experience and flexibility to customize platform-specific behaviors. It can also be used to develop apps for desktop and web.

Some examples of companies that use React Native: Facebook, Instagram, Airbnb, Uber, Tesla, Discord and others.

### Expo vs React Native CLI: Differences and Workflows

1. **CLI (React Native CLI)** is the official command-line tool of React Native, offering more control and flexibility over the project's configuration and customization. With it, you manually configure the native details of the app.

2. **Expo** is a tool that simplifies development, allowing you to create React Native apps without native configuration. It provides ready-made libraries and resources but may be limited in advanced customizations.

   1. **Manager Workflow (Expo Managed Workflow)**: This is the default Expo workflow, where the development environment is managed by Expo itself. It simplifies the process because you don't need to configure native details (Android/iOS). However, you are limited to the libraries and APIs that Expo offers.

   1. **Bare Workflow (Expo Bare Workflow)**: In this workflow, you use Expo, but with more control over the native code, allowing you to integrate custom native libraries. This workflow is ideal when you need more flexibility and want to use the full power of React Native with custom configurations.

[Set up your environment](https://reactnative.dev/docs/set-up-your-environment)   
[Prepare seu ambiente de desenvolvimento](https://react-native.rocketseat.dev/)

<details>
  <summary>Create the Project with Expo</summary>
   
#### creating with npx
1. **Run the following command to create a new React Native project with Expo**:
   ```bash
   npx create-expo-app@latest --template
   ```
2. Select the Navigation Option with TypeScript:

   1. Navigation: Choosing the navigation template automatically configures the necessary dependencies for navigation in your app, such as React Navigation, which is one of the most popular libraries for navigation in React Native.
   1. TypeScript: Opting for TypeScript provides static typing, which helps avoid common development errors, making the code safer and easier to understand, especially in larger projects.
      
3. Enter the App Name:
You will be prompted to enter the name of your app. This name will be used to identify your project both in the code and in the Expo interface.

#### creating with expo init
1. **Run the following command to create a new React Native project with Expo using npm**:
   ```bash
   expo init <project_name> --npm
   ```
2. Choose the Blank (TypeScript) option:
Blank (TypeScript): Selecting this option sets up a minimal project template with TypeScript, providing a clean starting point for your app with the benefits of static typing and better code maintainability.
</details>

# Mobiilirakendused

## Important questions (31.08.2022)

1. Why?
2. How?
3. What?
4. When?

## How to learn

Use Google and Youtube search engines. Learn to search for answers for your questions. 

Try: 
1. https://www.google.com/?q=how%20to%20create%20mobile%20applications
2. https://www.youtube.com/results?search_query=how+to+create+mobile+applications

Usually Youtube provides very good answers, so step by step, you get smarter, for what to search for.

(Ok, we do some tasks in class, but Youtube is much smarter, than your teacher.)

## Native Platforms

### iOS

#### Native tool

https://developer.apple.com/swift/

#### Alternative tools for Windows:

Running either limited set of functionality, or in Webbrowser.

1. https://www.swift.org/blog/swift-on-windows/
2. https://medium.com/@illescasDaniel/run-swift-on-windows-11-in-2021-675d703e7a91
3. https://www.developer.com/microsoft/an-intro-to-swift-programming-on-windows-even/


### Android

1. https://developer.android.com/studio
2. https://developer.android.com/jetpack
3. https://developer.android.com/kotlin
4. https://developer.android.com/games


### Summary of native platforms

To have fast application, that consumes less battery, native solutions are usually better, providing additional features (like running in background) etc.


## Cross platform native tools for generating AppStore / Google Play applications

For application with GUI development:

1. https://www.sam-solutions.com/blog/cross-platform-mobile-development/ (summary list)
2. https://kotlinlang.org/docs/multiplatform-mobile-getting-started.html
3. https://reactnative.dev/

For game development:

1. https://www.slant.co/topics/4241/~3d-game-engines-for-ios
2. https://unity.com/developer-tools


## Just using plain HTML/Web2.0 

1. https://www.w3schools.com/html/html_responsive.asp
2. https://tailwindcss.com/
3. https://nextjs.org/

Web2.0 application will work in web browser, on any device.


## Task:

1. Create yourself a Github account (for example github.com/your_user_name)
2. Create yourself a new public repository and name it your_user_name.github.io (for example for me it is mxrguspxrt.github.io)
3. Visit https://mxrguspxrt.github.io/ and your site
4. Create yourself a simple homepage using Markdown or HTML
    1. https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
    2. https://github.com/mxrguspxrt/mxrguspxrt.github.io (see this as an example and then 4.3)
    3. https://www.w3schools.com/html/html_responsive.asp
5. On this simple homepage write a essay on a subject: "Why I am learning in this school, how I hope it helps me in the future, who I want to be when I grow up"
6. Task 5 will be graded on scale of 1-5 before next class. Send me link to your_user_name.github.io.


## Make teams + pickup startup topic + Start with Figma design (7.09.2022)

By the next class:
1. Have team
2. Have idea for startup and Figma landing page design
3. Next class we start with dev env setup and programming!


## React Native (With Expo) (14.09.2022)

Today, we will be installing React Native with Expo.

Install Expo:
https://docs.expo.dev/get-started/installation/

Read documentation + Install React Native:
https://reactnative.dev/docs/environment-setup


1. Let's install support for Android: https://developer.android.com/studio (Download Studio + run the installer)
2. Let's install support for IOS: https://developer.apple.com/xcode/ (Download XCode + run the installer)
3. Let's install support for web: `npx expo install react-native-web@~0.18.7 react-dom@18.0.0 @expo/webpack-config@^0.17.0 # (these are required dependecies)`

```
npx create-expo-app Hello
cd Hello

npm run android
# https://docs.expo.dev/workflow/android-studio-emulator (here are steps you need to do)

npm run ios
# this part will be skipped, if you are on Windows machine. But you can test on some OSX machine on your own.

npx expo install react-native-web@~0.18.7 react-dom@18.0.0 @expo/webpack-config@^0.17.0 # (these are required dependecies)
npm run web
```

Ideally, you will have Android and web running, maybe iOS also. If you have any problems, ask teacher or co-student for help.


Task:
1. Implement at least 1 element (for example Text or Button from your Figma design).
2. Upload code for Expo project + Link to Figma to Github
3. Send the teacher's email the link to Github project 

# JJ_ReactNative_Inventory_App


## Table Of Contents:
- [Types of Testing](#Types-Of-Testing)
  - [Unit Testing](#Unit-Testing)
  - [Component Testing](#Component-Testing)
  - [End to End Testing](#Performance-Testing)
  - [Testing Best Practices](#Testing-Best-Practices)
- [Things to Consider](#Considerations)
- [Useful Links](#Useful-Links)

### Unit Testing:
Unit testing we could use any tools at our disposal i.e. Jest, Mocha, Jasmine etc.. as you are technically testing Vanilla Javascript code


### Component Testing:
Enzyme + Jest
Shallow vs Deep Rendering for Testing components 

### End to End Testing:
Appium (Not %100 on React) Potential issues with IOS Simulations (So we could look into webdriver or iwebdriver)

UI Automation: Detox (React Native Friendly but potential issues with Android), Cypress

### Things to Consider:
Testing with real devices/simulators

Testing React Components ('Mounting')

Mocks

Test Driven Development

Snapshot testing?

Testing Pyramid: UI/E2E (Test the entire system) - Component - Unit (for functions)

E2E testing slow to run and test and you don't get feedback as frequently. Aim for the test result to be stable and fast

Architecture Matters: Seperate your code into single reponsibility principle. If you have components, the compontents should do one thing, render the view. And keep logic seperate. 

Aim to get instant feedback from bugs (Unit test) You can check each component seperately but it doesn't necessary mean that it will work all togheter. Hence we need a mixture of everything to get the best testing coverage. 


### Useful Links:
[https://www.youtube.com/watch?v=cUSUJXAvt6k](https://www.youtube.com/watch?v=cUSUJXAvt6k)

[React Native Testing tools](https://medium.com/@ronak8036/react-native-testing-tools-f38d715adb57)

[Testing in react native with jest and detox](https://pillow.codes/testing-in-react-native-jest-detox-d7b3b79a166a)
[detox grey box e2e](https://hackernoon.com/detox-gray-box-end-to-end-testing-framework-for-mobile-apps-196ccd9564ce)
[detox vid from reddit](https://www.reddit.com/r/reactnative/comments/9zn26x/automated_end_2_end_greybox_testing_in_react/)

[E2E](https://medium.com/@reime005/react-native-end-to-end-testing-d488e010e39f)
# React Native

## [getting started with react native](https://facebook.github.io/react-native/docs/getting-started)

1.  Name three Core Components of React Native and describe what they do.

The three core components of React Native are _Views, Native Components, and Core Components_. Views are the foundational building blocks of Mobile UI. Views encompass everything from text, to buttons, to inputs to complex components. Native Components are the components that come from and are ready-to-use components for building React-Native applications, written in javascript rather than the phone's language. Finally, Core components are the basic, base, UI Components that React native supplies for building apps

2.  What problem does React Native solve (why call it native)?

React Native solves the problem of having to create applications that have _native_ support on multiple devices written in different languages. It is called 'native' because it takes in a base format of javascript code and translates to the native language, components, and API's of the device running the app.

3.  What are the building blocks of a React Native app? How does that compare to a React app?
    | REACT NATIVE UI COMPONENT | ANDROID VIEW | IOS VIEW | Web HTML |
    | --- | --- | --- | --- |
    | `<View>` | `<ViewGroup>` | `<UIView>` | A non-scrolling `<div>` |
    | `<Text>` | `<TextView>` | `<UITextView>` | `<p>` |
    | `<Image>` | `<ImageView>` | `<UIImageView>` | `<img>` |
    | `<ScrollView>` | `<ScrollView>` | `<UIScrollView>` | `<div>` |
    | `<TextInput>` | `<EditText>` | `<UITextField>` | `<input type="text">` |

    In react native components are made to be very generic and less semantic. View, text, image, etc. In react there are a lot of semantic tags and various types of boxes and buttons and inputs with sometimes unassuming names. React Native then takes these generic Tags and compiles them to the native language of the device running the program. Normal react leaves it as is because its built for the web browser by default

## [expo](https://expo.io/)

1.  What solution does expo provide?

Expo provides a framework/ecosystem of tools, and packages with all you need to work with react native. It provides a framework and packages for working with the app stores and supports deployment nad updates and insights and so much more

2.  Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the **managed** workflow.

3.  What is the difference between React Native and Expo?

Expo is a framework built over react native, like NextJs to React, React Native is the part that runs apps, expo does the heavy lifting and sets guidelines.

## [expo snack](https://snack.expo.io/)

1.  Checkout this tool. What does snack allow you to do?

Expo Snack allows you to work with React-Native without causing a large overhead on your machine, with live updates and even syncing updates to your mobile device for live testing. Brilliant, powerful.

## [ejecting](https://docs.expo.io/versions/latest/expokit/eject)

1.  What does "eject" mean within the context of Expo?

'Eject' to bare workflow, where you jump between workflows and move into the bare workflow (No longer utilizing Expo's Tools and features but writing react native on your own without as much help and direction), where you can continue to use Expo APIs but have access and full control over your native Android and iOS projects.

2.  When should you not eject?

When you have not run into a feature that requires full control over the logic of your project

3.  Why might you choose to eject?

When you need more control to do specific tasks and you are comfortable writing 'bare' react native code for the time being to accomplish that task

## [react native basics](https://facebook.github.io/react-native/docs/tutorial)

### Additional Questions

1.  Looking ahead at this module's [course schedule](https://codefellows.github.io/code-401-javascript-guide/curriculum/#module-9), What do you look forward to learning?

React native seems AAMAAZZINNGGG and It looks like it solves A LOT of problems. Why don't we all just program in react native all the time?

2.  What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-41/)


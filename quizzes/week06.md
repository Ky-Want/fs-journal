# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
main.js
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
Vue components are written as a combination of JavaScript objects that manage the app's data and an HTML-based template syntax that maps to the underlying DOM structure,
while a page 
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
You can use the v-repeat directive to repeat a template element based on an Array of objects on the ViewModel.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
a template (which is like HTML), styles and JavaScript
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov 
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
Vue Router helps link between the browser's URL/History and Vue's components allowing for certain paths to render whatever view is associated with it.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
AppState can tell you if the app is in the foreground or background, and notify you when the state changes. AppState is frequently used to determine the intent and proper behavior when handling push notifications.
The state object is where you store property values that belongs to the component. When the state object changes, the component re-renders.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Vue. js developer responsibilities include writing user-side logic with JavaScript, developing user-facing web applications and components. They also need to write robust, secure, scalable code and coordinate with other software developers and project managers.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App. vue : Your root Vue component, which contains the entire application. main. js : the entry point of the entire application's JavaScript code.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
In Vue. js, we can add an inline style to our element by binding the style attribute in the HTML tag. For reference, :style is shorthand for v-bind:style . Inline styling can be done in two ways: using object syntax or array syntax.Feb
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
In Vue, we use data to track changes to a particular property that we'd like to be reactive. Computed properties allow us to define a property
```
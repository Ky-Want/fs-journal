# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
- HTML Binding: It is the way of having some string data stored as any HTML to be used within any div tag. So the content of the div tag would be as per the HTML we have bound to it. The Syntax to use HTML binding is by using the v-html directive and specifying the data property to it. The v-html directive is used to update an element’s innerHTML with our data.

Example: In the below example, we have enclosed the string with the <b> tag. If we used v-text to bind the name data, it would show output along with the tags. But to actually apply the HTML element, we need v-html.


- Text Binding: It is used when we need to bind the content of any HTML in Vue. The syntax for using text binding is by using the v-text directive in any HTML element and a data property should be assigned to it. For instance, the data inside the <script> tag can be displayed with the help of the<template> tag that contains the v-text directive having the value that is to be rendered.

Example: In the below example, we have bound the data that is the name having the value, with the v-text directive, declared in the <div> tag.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
An SPA (Single-page application) is a web app implementation that loads only a single web document, and then updates the body content of that single document via JavaScript APIs such as XMLHttpRequest and Fetch when different content is to be shown.
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
- Quick Loading Time. A page taking over 200 milliseconds to load can significantly affect your online business and, eventually, sales. 
- Seamless User Experience. SPAs deliver an experience like a desktop or mobile app. 
- Ease in Building Feature-rich Apps. 
- Uses Less Bandwidth.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted is called when there is no active component instance to be associated with. Lifecycle injection APIs can only be used during execution of setup(). If you are using async setup(), make sure to register lifecycle hooks before the first await statement.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
Vue v-model is a directive that creates a two-way data binding between a value in our template and a value in our data properties. A common use case for using v-model is when designing forms and inputs. We can use it to have our DOM input elements be able to modify the data in our Vue instance.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
The v-on directive executes functions on a specific event. This can be a custom event or a standard JavaScript event, such as click , hover , or mouseenter .
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
Conditional Rendering in Vue makes it easy to toggle the presence of any element in the DOM based on a certain condition. The directives v-if and v-else are used for this purpose. The v-if directive can be used to conditionally render a block.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The purpose of this key attribute is to give "a hint for Vue's virtual DOM algorithm to identify VNodes when diffing the new list of nodes against the old list" (from Vue. js Docs)
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
A slot is a placeholder inside a web component that users can fill with their own markup 
```
# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
main.js is the entry point for the app, but you could think of the index.html as the entrypoint as well since this is where everything is loaded from and the first thing presented to the user.
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
Components are reusable Vue instances with custom HTML elements. Components can be reused as many times as you want or used in another component, making it a child component. Data, computed, watch, and methods can be used in a Vue component. 

A page is made up of different nested components. When using a build step, we typically define each Vue component in a dedicated file using the .vue extension - known as a Single-File Component (SFC for short)

```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
I think that this question is referring to the vue version of a for loop, this is called v-for() in vue, and can iterate over a collection of data and access getter methods to repeat elements in the html. generally speaking however it is the components that are used like templates to repeat elements. an example in class was using a form which we abstracted into a single component, for both the new car creation form, as well as the current car edit form. We also use the new <slot> as a specific target for repeated or changing data in an element.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
Components in Vue are composed of three parts; a template (which is like HTML), styles and JavaScript. These can be split into multiple files or the same
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The Liskov substitution principle: "Functions that use pointers or references to base classes must be able to use objects of derived classes without knowing it. i.e. design by contract.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
the loadPage component is used in the router to mount routes to specific pages.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
the state is the reactive object in a single local component, while the AppState contains reactive objects for the entire app.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
just as in previous projects, it is the service layers job to perform business logic and to make changes to the appstate, and send requests to the server.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
app.vue
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
style, scoped
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
vue uses reactive objects to watch for changes, reactive({}) is used for objects, ref() is used for primitive values these work in tandem with computed() which returns the changes.
watchEffect also watches for any state changes though I am not entirely certain why we use one versus the other.
```
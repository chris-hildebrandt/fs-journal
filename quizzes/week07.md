# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
Data binding is a technique used to bind data sources from the provider and consumer together and synchronize them at the time of retrieval. In a data binding process, whenever data is changed, it is reflected automatically by the elements bound to the data.

The term data binding is also used in cases where an outer representation of data in an element changes, and the underlying data is automatically updated to reflect this change.

in vue, we have to manipulate the class list and inline styles of an element. We already know that the class list and inline style are attributes so we can use v-bind to handle them. Vue.js provides special enhancements when we use v-bind with class and style. The expressions can also evaluate to objects or arrays along with strings.

```
**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
single page application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Sites with single page applications are more efficient in terms of processing, they can cost less than traditional MPA sites, and they demand less time from developers because they can use repetitive layouts and act as "content on demand" apps.

Here are some other considerations:

1. General speed
MPAs constantly send server requests that are then processed as a database query. The database responds the server processes the query, and ultimately the pages are rendered. That’s a lot of patty-caking that slows down page loads.

SPA sites, on the other hand, download everything up front, so the back and forth is eliminated; new information is loaded as a single page rather than as a process that requires requesting more HTML pages within the site architecture. Higher speed and efficiency are achieved with the help of JSON; the end result is instant access to all features and functions of the site with no delay.

Also, sometimes it's faster to navigate among pages with an SPA due to caching (more on that below) and minimized data volumes. Only the required data is transmitted back and forth; even if a user needs the uploaded data, the application will download just the missing parts. So, the whole process is quicker compared with MPAs that load pages at every request.

2. Caching capabilities
SPAs request data from the server just one time, upon initial download, so caching works better; if a user has a poor internet connection, site data can be accessed with the server when the connection improves.

Also, even if the SPA is a landing page and the browser downloads the data only once, at some point it will check to see the cached data has changed or not. When something changes, an application retrieves it asynchronously.

3. UX
Single page applications also provide a better overall user experience. With an MPA, users have to click through links and menus to get the information they're looking for, but with an SPA, the user just has to scroll. This feature makes SPAs particularly well-suited to mobile environments.

Moreover, with an SPA, a user can access a page even with a poor internet connection, and it's generally easier to interact with an SPA from any device. Without the need for a page refresh, the experience is continuous, and navigation is faster overall because page elements are reused.

source: https://www.itechart.com/blog/pros-cons-of-single-page-applications/

```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted basically runs code when the component is loaded, although the timing is more specific than that, and there are other options for the timing as well such as onDestroyed.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
v-model is used to sync data between forms on the frontend and the state elements that correlate with the forms. it is a convenient shorthand in vue for user-input syncing. As such I have used it extensively for all of my forms in vue. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
to attach a listener to an element

The event type is denoted by the argument. The expression can be a method name, an inline statement, or omitted if there are modifiers present.

When used on a normal element, it listens to native DOM events only. When used on a custom element component, it listens to custom events emitted on that child component.

When listening to native DOM events, the method receives the native event as the only argument. If using inline statement, the statement has access to the special $event property: v-on:click="handle('ok', $event)".

v-on also supports binding to an object of event / listener pairs without an argument. Note when using the object syntax, it does not support any modifiers.

source:https://vuejs.org/api/built-in-directives.html#v-on
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-else, v-else-if, v-on, v-for, v-show, etc. you can also do style bindings for attributes like "d-none"
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```

```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```

```
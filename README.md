# React (JavaScript library)

From Wikipedia, the free encyclopedia

[Jump to navigation](https://en.wikipedia.org/wiki/React_(JavaScript_library)#mw-head)[Jump to search](https://en.wikipedia.org/wiki/React_(JavaScript_library)#searchInput)

For the open-source mobile application framework, see  [React Native](https://en.wikipedia.org/wiki/React_Native "React Native").

React

[![React-icon.svg](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/220px-React-icon.svg.png)](https://en.wikipedia.org/wiki/File:React-icon.svg)

[Original author(s)](https://en.wikipedia.org/wiki/Programmer "Programmer")

Jordan Walke

[Developer(s)](https://en.wikipedia.org/wiki/Programmer "Programmer")

[Meta](https://en.wikipedia.org/wiki/Meta_Platforms "Meta Platforms")  and community

Initial release

May 29, 2013; 8 years ago[[1]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-initialrelease-1)

[Stable release](https://en.wikipedia.org/wiki/Software_release_life_cycle "Software release life cycle")

18.1.0[[2]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-wikidata-00a5afa777b9be0ce90332e2bfeb2e4385e29b88-v3-2) [![Edit this on Wikidata](https://upload.wikimedia.org/wikipedia/en/thumb/8/8a/OOjs_UI_icon_edit-ltr-progressive.svg/10px-OOjs_UI_icon_edit-ltr-progressive.svg.png)](https://www.wikidata.org/wiki/Q19399674?uselang=en#P348 "Edit this on Wikidata")  / 26 April 2022; 13 days ago

[Repository](https://en.wikipedia.org/wiki/Repository_(version_control) "Repository (version control)")

-   [github.com/facebook/react](https://github.com/facebook/react)  [![Edit this at Wikidata](https://upload.wikimedia.org/wikipedia/en/thumb/8/8a/OOjs_UI_icon_edit-ltr-progressive.svg/10px-OOjs_UI_icon_edit-ltr-progressive.svg.png)](https://www.wikidata.org/wiki/Q19399674#P1324 "Edit this at Wikidata")

Written in

[JavaScript](https://en.wikipedia.org/wiki/JavaScript "JavaScript")

[Platform](https://en.wikipedia.org/wiki/Computing_platform "Computing platform")

[Web platform](https://en.wikipedia.org/wiki/Web_platform "Web platform")

[Type](https://en.wikipedia.org/wiki/Software_categories#Categorization_approaches "Software categories")

[JavaScript library](https://en.wikipedia.org/wiki/JavaScript_library "JavaScript library")

[License](https://en.wikipedia.org/wiki/Software_license "Software license")

[MIT License](https://en.wikipedia.org/wiki/MIT_License "MIT License")

Website

[reactjs.org](https://reactjs.org/)

**React**  (also known as  **React.js**  or  **ReactJS**) is a  [free and open-source](https://en.wikipedia.org/wiki/Free_and_open-source_software "Free and open-source software")  [front-end](https://en.wikipedia.org/wiki/Front_end_and_back_end "Front end and back end")  [JavaScript library](https://en.wikipedia.org/wiki/JavaScript_library "JavaScript library")[[3]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-react-3)  for building  [user interfaces](https://en.wikipedia.org/wiki/User_interfaces "User interfaces")  based on UI components. It is maintained by  [Meta](https://en.wikipedia.org/wiki/Meta_Platforms "Meta Platforms")  (formerly Facebook) and a community of individual developers and companies.[[4]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-4)[[5]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-5)[[6]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-6)  React can be used as a base in the development of  [single-page](https://en.wikipedia.org/wiki/Single-page_application "Single-page application"), mobile, or server-rendered applications with frameworks like  [Next.js](https://en.wikipedia.org/wiki/Next.js "Next.js"). However, React is only concerned with state management and rendering that state to the  [DOM](https://en.wikipedia.org/wiki/Document_Object_Model "Document Object Model"), so creating React applications usually requires the use of additional libraries for routing, as well as certain client-side functionality.[[7]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-7)[[8]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-8)

## Contents

-   [1Basic usage](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Basic_usage)
-   [2Notable features](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Notable_features)
    -   [2.1Declarative](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Declarative)
    -   [2.2Components](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Components)
    -   [2.3Functional components](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Functional_components)
    -   [2.4Class-based components](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Class-based_components)
    -   [2.5Virtual DOM](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Virtual_DOM)
    -   [2.6Lifecycle methods](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Lifecycle_methods)
    -   [2.7JSX](https://en.wikipedia.org/wiki/React_(JavaScript_library)#JSX)
    -   [2.8Architecture beyond HTML](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Architecture_beyond_HTML)
    -   [2.9React hooks](https://en.wikipedia.org/wiki/React_(JavaScript_library)#React_hooks)
        -   [2.9.1Rules of hooks](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Rules_of_hooks)
-   [3Common idioms](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Common_idioms)
    -   [3.1Unidirectional data flow](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Unidirectional_data_flow)
-   [4Future development](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Future_development)
-   [5History](https://en.wikipedia.org/wiki/React_(JavaScript_library)#History)
-   [6Licensing](https://en.wikipedia.org/wiki/React_(JavaScript_library)#Licensing)
-   [7See also](https://en.wikipedia.org/wiki/React_(JavaScript_library)#See_also)
-   [8References](https://en.wikipedia.org/wiki/React_(JavaScript_library)#References)
-   [9External links](https://en.wikipedia.org/wiki/React_(JavaScript_library)#External_links)

## Basic usage[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=1 "Edit section: Basic usage")]

The following is a rudimentary example of React usage in HTML with  [JSX](https://en.wikipedia.org/wiki/React_(JavaScript_library)#JSX "React (JavaScript library)")  and JavaScript.

The  `Greeting`  function is a React component that displays the famous introductory ''Hello, world".

When displayed in a web browser, the result will be a rendering of:

## Notable features[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=2 "Edit section: Notable features")]

![](https://upload.wikimedia.org/wikipedia/en/thumb/f/f2/Edit-clear.svg/40px-Edit-clear.svg.png)

This article  **is written like  [a manual or guidebook](https://en.wikipedia.org/wiki/Wikipedia:What_Wikipedia_is_not#GUIDE "Wikipedia:What Wikipedia is not").** Please help  [rewrite this article](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit)  from a descriptive,  [neutral point of view](https://en.wikipedia.org/wiki/Wikipedia:Neutral_point_of_view "Wikipedia:Neutral point of view"), and remove advice or instruction.  _(September 2021)_ _([Learn how and when to remove this template message](https://en.wikipedia.org/wiki/Help:Maintenance_template_removal "Help:Maintenance template removal"))_

### Declarative[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=3 "Edit section: Declarative")]

React adheres to the  [declarative programming](https://en.wikipedia.org/wiki/Declarative_programming "Declarative programming")  paradigm. Developers design views for each state of an application, and React updates and renders components when data changes. This is in contrast with  [imperative programming](https://en.wikipedia.org/wiki/Imperative_programming "Imperative programming").[[9]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-schwarzm%C3%BCller-9)

### Components[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=4 "Edit section: Components")]

React code is made of entities called  [components](https://en.wikipedia.org/wiki/Component-based_software_engineering "Component-based software engineering"). These components are reusable and must be formed in the SRC folder following the Pascal Case as its naming convention (capitalize camelCase). Components can be rendered to a particular element in the  [DOM](https://en.wikipedia.org/wiki/Document_Object_Model "Document Object Model")  using the React DOM library. When rendering a component, one can pass the values between components through "props":[[10]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-10)

export default Example;

In the above example, the  `name`  property with the value "Gulshan" has been passed from the  `Example`  component to the  `Tool`  component.

Also the  `return`  section is wrapped in a tag because there is a limitation in the  `return`  function, it can only return a single value. So all JSX elements and components are bound into a single tag.

The two primary ways of declaring components in React are through function components and class-based components.

### Functional components[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=5 "Edit section: Functional components")]

Function components are declared with a function that then returns some JSX.

const Greeter = () => <div>Hello World</div>;

### Class-based components[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=6 "Edit section: Class-based components")]


Where class components are all about the use of classes and the lifecycle methods, functional components have hooks to deal with state management and other problems which arise when writing code in React.

### Virtual DOM[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=7 "Edit section: Virtual DOM")]

Another notable feature is the use of a virtual  [Document Object Model](https://en.wikipedia.org/wiki/Document_Object_Model "Document Object Model"), or virtual DOM. React creates an  [in-memory](https://en.wikipedia.org/wiki/In-memory_processing "In-memory processing")  data-structure cache, computes the resulting differences, and then updates the browser's displayed DOM efficiently.[[11]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-workingwiththebrowser-11)  This process is called  **reconciliation**. This allows the programmer to write code as if the entire page is rendered on each change, while the React libraries only render subcomponents that actually change. This selective rendering provides a major performance boost.[[12]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-:0-12)  It saves the effort of recalculating the CSS style, layout for the page and rendering for the entire page.[[12]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-:0-12)

### Lifecycle methods[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=8 "Edit section: Lifecycle methods")]

Lifecycle methods for class-based components use a form of  [hooking](https://en.wikipedia.org/wiki/Hooking "Hooking")  that allows the execution of code at set points during a component's lifetime.

-   `shouldComponentUpdate`  allows the developer to prevent unnecessary re-rendering of a component by returning false if a render is not required.
-   `componentDidMount`  is called once the component has "mounted" (the component has been created in the user interface, often by associating it with a  [DOM](https://en.wikipedia.org/wiki/Document_Object_Model "Document Object Model")  node). This is commonly used to trigger data loading from a remote source via an  [API](https://en.wikipedia.org/wiki/API "API").
-   `componentWillUnmount`  is called immediately before the component is torn down or "unmounted". This is commonly used to clear resource-demanding dependencies to the component that will not simply be removed with the unmounting of the component (e.g., removing any  `setInterval()`  instances that are related to the component, or an "[eventListener](https://en.wikipedia.org/wiki/Event_(computing) "Event (computing)")" set on the "document" because of the presence of the component)
-   `render`  is the most important lifecycle method and the only required one in any component. It is usually called every time the component's state is updated, which should be reflected in the user interface.

### JSX[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=9 "Edit section: JSX")]

Main article:  [JSX](https://en.wikipedia.org/wiki/JSX_(JavaScript) "JSX (JavaScript)")

[JSX](https://en.wikipedia.org/wiki/JSX_(JavaScript) "JSX (JavaScript)"), or JavaScript Syntax Extension, is an extension to the JavaScript language syntax.[[13]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-13)  Similar in appearance to HTML, JSX provides a way to structure component rendering using syntax familiar to many developers. React components are typically written using JSX, although they do not have to be (components may also be written in pure JavaScript). JSX is similar to another extension syntax created by Facebook for  [PHP](https://en.wikipedia.org/wiki/PHP "PHP")  called  [XHP](https://en.wikipedia.org/wiki/XHP "XHP").


### Architecture beyond HTML[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=10 "Edit section: Architecture beyond HTML")]

The basic architecture of React applies beyond rendering HTML in the browser. For example, Facebook has dynamic charts that render to  `<canvas>`  tags,[[14]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-14)  and Netflix and  [PayPal](https://en.wikipedia.org/wiki/PayPal "PayPal")  use universal loading to render identical HTML on both the server and client.[[15]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-paypal-isomorphic-reactjs-15)[[16]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-netflix-isomorphic-reactjs-16)

### React hooks[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=11 "Edit section: React hooks")]

Hooks are functions that let developers "hook into" React state and lifecycle features from function components.[[17]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-17)  Hooks do not work inside classes — they let you use React without classes.[[18]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-18)

React provides a few built-in hooks like  `useState`,[[19]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-19)  `useContext`,  `useReducer`  ,  `useMemo`  and  `useEffect`.[[20]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-20)  Others are documented in the Hooks API Reference.[[21]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-21)  `useState`  and  `useEffect`, which are the most commonly used, are for controlling state and side effects respectively.

#### Rules of hooks[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=12 "Edit section: Rules of hooks")]

There are rules of hooks[[22]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-22)  which describe the characteristic code pattern that hooks rely on. It is the modern way to handle state with React.

1.  Hooks should only be called at the top level (not inside loops or if statements).
2.  Hooks should only be called from React function components and custom hooks, not normal functions or class components.

Although these rules can't be enforced at runtime, code analysis tools such as  [linters](https://en.wikipedia.org/wiki/Lint_(software) "Lint (software)")  can be configured to detect many mistakes during development. The rules apply to both usage of hooks and the implementation of custom hooks,[[23]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-23)  which may call other hooks.

## Common idioms[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=13 "Edit section: Common idioms")]

React does not attempt to provide a complete "application library". It is designed specifically for building user interfaces[[3]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-react-3)  and therefore does not include many of the tools some developers might consider necessary to build an application. This allows the choice of whichever libraries the developer prefers to accomplish tasks such as performing network access or local data storage. Common patterns of usage have emerged as the library matures.

### Unidirectional data flow[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=14 "Edit section: Unidirectional data flow")]

To support React's concept of unidirectional data flow (which might be contrasted with  [AngularJS](https://en.wikipedia.org/wiki/AngularJS "AngularJS")'s bidirectional flow), the Flux architecture was developed as an alternative to the popular  [model–view–controller](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller "Model–view–controller")  architecture. Flux features  _actions_  which are sent through a central  _dispatcher_  to a  _store_, and changes to the store are propagated back to the view.[[24]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-flux-24)  When used with React, this propagation is accomplished through component properties. Since its conception, Flux has been superseded by libraries such as  [Redux](https://en.wikipedia.org/wiki/Redux_(JavaScript_library) "Redux (JavaScript library)")  and MobX.[[25]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-25)

Flux can be considered a variant of the  [observer pattern](https://en.wikipedia.org/wiki/Observer_pattern "Observer pattern").[[26]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-26)

A React component under the Flux architecture should not directly modify any props passed to it, but should be passed callback functions that create  _actions_  which are sent by the dispatcher to modify the store. The action is an object whose responsibility is to describe what has taken place: for example, an action describing one user "following" another might contain a user id, a target user id, and the type  `USER_FOLLOWED_ANOTHER_USER`.[[27]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-27)  The stores, which can be thought of as models, can alter themselves in response to actions received from the dispatcher.

This pattern is sometimes expressed as "properties flow down, actions flow up". Many implementations of Flux have been created since its inception, perhaps the most well-known being  [Redux](https://en.wikipedia.org/wiki/Redux_(JavaScript_library) "Redux (JavaScript library)"), which features a single store, often called a  [single source of truth](https://en.wikipedia.org/wiki/Single_source_of_truth "Single source of truth").[[28]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-28)

## Future development[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=15 "Edit section: Future development")]

Project status can be tracked via the core team discussion forum.[[29]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-29)  However, major changes to React go through the Future of React repository issues and  [pull requests](https://en.wikipedia.org/wiki/Pull_request "Pull request").[[30]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-30)[[31]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-31)  This enables the React community to provide feedback on new potential features, experimental APIs and JavaScript syntax improvements.

## History[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=16 "Edit section: History")]

React was created by Jordan Walke, a software engineer at Facebook, who released an early prototype of React called "FaxJS".[[32]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-32)[[33]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-papp-33)  He was influenced by  [XHP](https://en.wikipedia.org/wiki/XHP "XHP"), an  [HTML](https://en.wikipedia.org/wiki/HTML "HTML")  component library for  [PHP](https://en.wikipedia.org/wiki/PHP "PHP"). It was first deployed on Facebook's  [News Feed](https://en.wikipedia.org/wiki/News_Feed "News Feed")  in 2011 and later on  [Instagram](https://en.wikipedia.org/wiki/Instagram "Instagram")  in 2012.[[34]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-34)  It was open-sourced at JSConf US in May 2013.[[33]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-papp-33)

[React Native](https://en.wikipedia.org/wiki/React_Native "React Native"), which enables native  [Android](https://en.wikipedia.org/wiki/Android_(operating_system) "Android (operating system)"),  [iOS](https://en.wikipedia.org/wiki/IOS "IOS"), and  [UWP](https://en.wikipedia.org/wiki/Universal_Windows_Platform "Universal Windows Platform")  development with React, was announced at Facebook's React Conf in February 2015 and open-sourced in March 2015.

On April 18, 2017, Facebook announced React Fiber, a new set of internal algorithms for rendering, as opposed to React's old rendering algorithm, Stack.[[35]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-35)  React Fiber was to become the foundation of any future improvements and feature development of the React library.[[36]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-36)[_[needs update](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style/Dates_and_numbers#Chronological_items "Wikipedia:Manual of Style/Dates and numbers")_]  The actual syntax for programming with React does not change; only the way that the syntax is executed has changed.[[37]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-techcrunch-37)  React's old rendering system, Stack, was developed at a time when the focus of the system on dynamic change was not understood. Stack was slow to draw complex animation, for example, trying to accomplish all of it in one chunk. Fiber breaks down animation into segments that can be spread out over multiple frames. Likewise, the structure of a page can be broken into segments that may be maintained and updated separately. JavaScript functions and virtual  [DOM](https://en.wikipedia.org/wiki/Document_Object_Model "Document Object Model")  objects are called "fibers", and each can be operated and updated separately, allowing for smoother on-screen rendering.[[38]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-github-38)

On September 26, 2017, React 16.0 was released to the public.[[39]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-39)

On February 16, 2019, React 16.8 was released to the public.[[40]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-40)  The release introduced React Hooks.[[41]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-41)

On August 10, 2020, the React team announced the first release candidate for React v17.0, notable as the first major release without major changes to the React developer-facing API.[[42]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-42)

Versions

Version

Release Date

Changes

0.3.0

29 May 2013

Initial Public Release

0.4.0

20 July 2013

Support for comment nodes  `<div>{/* */}</div>`, Improved server-side rendering APIs, Removed React.autoBind, Support for the key prop, Improvements to forms, Fixed bugs.

0.5.0

20 October 2013

Improve Memory usage, Support for Selection and Composition events, Support for getInitialState and getDefaultProps in mixins, Added React.version and React.isValidClass, Improved compatibility for Windows.

0.8.0

20 December 2013

Added support for rows & cols, defer & async, loop for  `<audio>`  &  `<video>`, autoCorrect attributes. Added onContextMenu events, Upgraded jstransform and esprima-fb tools, Upgraded browserify.

0.9.0

20 February 2014

Added support for crossOrigin, download and hrefLang, mediaGroup and muted, sandbox, seamless, and srcDoc, scope attributes, Added any, arrayOf, component, oneOfType, renderable, shape to React.PropTypes, Added support for onMouseOver and onMouseOut event, Added support for onLoad and onError on  `<img>`  elements.

0.10.0

21 March 2014

Added support for srcSet and textAnchor attributes, add update function for immutable data, Ensure all void elements don't insert a closing tag.

0.11.0

17 July 2014

Improved SVG support, Normalized e.view event, Update $apply command, Added support for namespaces, Added new transformWithDetails API, includes pre-built packages under dist/, MyComponent() now returns a descriptor, not an instance.

0.12.0

21 November 2014

Added new features Spread operator ({...}) introduced to deprecate this.transferPropsTo, Added support for acceptCharset, classID, manifest HTML attributes, React.addons.batchedUpdates added to API, @jsx React.DOM no longer required, Fixed issues with CSS Transitions.

0.13.0

10 March 2015

Deprecated patterns that warned in 0.12 no longer work, ref resolution order has changed, Removed properties this._pendingState and this._rootNodeID, Support ES6 classes, Added API React.findDOMNode(component), Support for iterators and immutable-js sequences, Added new features React.addons.createFragment, deprecated React.addons.classSet.

0.14.1

29 October 2015

Added support for srcLang, default, kind attributes, and color attribute, Ensured legacy .props access on DOM nodes, Fixed scryRenderedDOMComponentsWithClass, Added react-dom.js.

15.0.0

7 April 2016

Initial render now uses document.createElement instead of generating HTML, No more extra  `<span>`s, Improved SVG support,  `ReactPerf.getLastMeasurements()`  is opaque, New deprecations introduced with a warning, Fixed multiple small memory leaks, React DOM now supports the cite and profile HTML attributes and cssFloat, gridRow and gridColumn CSS properties.

15.1.0

20 May 2016

Fix a batching bug, Ensure use of the latest object-assign, Fix regression, Remove use of merge utility, Renamed some modules.

15.2.0

1 July 2016

Include component stack information, Stop validating props at mount time, Add React.PropTypes.symbol, Add onLoad handling to  `<link>`  and onError handling to  `<source>`  element, Add  `isRunning()`  API, Fix performance regression.

15.3.0

30 July 2016

Add React.PureComponent, Fix issue with nested server rendering, Add xmlns, xmlnsXlink to support SVG attributes and referrerPolicy to HTML attributes, updates React Perf Add-on, Fixed issue with ref.

15.3.1

19 August 2016

Improve performance of development builds, Cleanup internal hooks, Upgrade fbjs, Improve startup time of React, Fix memory leak in server rendering, fix React Test Renderer, Change trackedTouchCount invariant into a console.error.

15.4.0

16 November 2016

React package and browser build no longer includes React DOM, Improved development performance, Fixed occasional test failures, update batchedUpdates API, React Perf, and  `ReactTestRenderer.create()`.

15.4.1

23 November 2016

Restructure variable assignment, Fixed event handling, Fixed compatibility of browser build with AMD environments.

15.4.2

6 January 2017

Fixed build issues, Added missing package dependencies, Improved error messages.

15.5.0

7 April 2017

Added react-dom/test-utils, Removed peerDependencies, Fixed issue with Closure Compiler, Added a deprecation warning for React.createClass and React.PropTypes, Fixed Chrome bug.

15.5.4

11 April 2017

Fix compatibility with Enzyme by exposing batchedUpdates on shallow renderer, Update version of prop-types, Fix react-addons-create-fragment package to include loose-envify transform.

15.6.0

13 June 2017

Add support for CSS variables in style attribute and Grid style properties, Fix AMD support for addons depending on react, Remove unnecessary dependency, Add a deprecation warning for React.createClass and React.DOM factory helpers.

16.0.0

26 September 2017

Improved error handling with introduction of "error boundaries", React DOM allows passing non-standard attributes, Minor changes to setState behavior, remove react-with-addons.js build, Add React.createClass as create-react-class, React.PropTypes as prop-types, React.DOM as react-dom-factories, changes to the behavior of scheduling and lifecycle methods.

16.1.0

9 November 2017

Discontinuing Bower Releases, Fix an accidental extra global variable in the UMD builds, Fix onMouseEnter and onMouseLeave firing, Fix <textarea> placeholder, Remove unused code, Add a missing package.json dependency, Add support for React DevTools.

16.3.0

29 March 2018

Add a new officially supported context API, Add new packagePrevent an infinite loop when attempting to render portals with SSR, Fix an issue with this.state, Fix an IE/Edge issue.

16.3.1

3 April 2018

Prefix private API, Fix performance regression and error handling bugs in development mode, Add peer dependency, Fix a false positive warning in IE11 when using Fragment.

16.3.2

16 April 2018

Fix an IE crash, Fix labels in User Timing measurements, Add a UMD build, Improve performance of unstable_observedBits API with nesting.

16.4.0

24 May 2018

Add support for Pointer Events specification, Add the ability to specify propTypes, Fix reading context, Fix the  `getDerivedStateFromProps()`  support, Fix a testInstance.parent crash, Add React.unstable_Profiler component for measuring performance, Change internal event names.

16.5.0

5 September 2018

Add support for React DevTools Profiler, Handle errors in more edge cases gracefully, Add react-dom/profiling, Add onAuxClick event for browsers, Add movementX and movementY fields to mouse events, Add tangentialPressure and twist fields to pointer event.

16.6.0

23 October 2018

Add support for contextType, Support priority levels, continuations, and wrapped callbacks, Improve the fallback mechanism, Fix gray overlay on iOS Safari, Add  `React.lazy()`  for code splitting components.

16.7.0

20 December 2018

Fix performance of React.lazy for lazily-loaded components, Clear fields on unmount to avoid memory leaks, Fix bug with SSR, Fix a performance regression.

16.8.0

6 February 2019

Add Hooks, Add  `ReactTestRenderer.act()`  and  `ReactTestUtils.act()`  for batching updates, Support synchronous thenables passed to React.lazy(), Improve useReducer Hook lazy initialization API.

16.8.6

27 March 2019

Fix an incorrect bailout in useReducer(), Fix iframe warnings in Safari DevTools, Warn if contextType is set to Context.Consumer instead of Context, Warn if contextType is set to invalid values.

16.9.0

9 August 2019

Add  React.Profiler  API for gathering performance measurements programmatically. Remove unstable_ConcurrentMode in favor of unstable_createRoot

16.10.0

27 September 2019

Fix edge case where a hook update wasn't being memoized. Fix heuristic for determining when to hydrate, so we don't incorrectly hydrate during an update. Clear additional fiber fields during unmount to save memory. Fix bug with required text fields in Firefox. Prefer Object.is instead of inline polyfill, when available. Fix bug when mixing Suspense and error handling.

16.10.1

28 September 2019

Fix regression in Next.js apps by allowing Suspense mismatch during hydration to silently proceed

16.10.2

3 October 2019

Fix regression in react-native-web by restoring order of arguments in event plugin extractors

16.11.0

22 October 2019

Fix mouseenter handlers from firing twice inside nested React containers. Remove unstable_createRoot and unstable_createSyncRoot experimental APIs. (These are available in the Experimental channel as createRoot and createSyncRoot.)

16.12.0

14 November 2019

React DOM - Fix passive effects (`useEffect`) not being fired in a multi-root app.

React Is - Fix  `lazy`  and  `memo`  types considered elements instead of components

16.13.0

26 February 2020

Features added in React Concurrent mode.

Fix regressions in React core library and React Dom.

16.13.1

19 March 2020

Fix bug in legacy mode Suspense.

Revert warning for cross-component updates that happen inside class render lifecycles

16.14.0

14 October 2020

Add support for the new JSX transform.

17.0.0

20 October 2020

"No New Features" enables gradual React updates from older versions.

Add new JSX Transform, Changes to Event Delegation

17.0.1

22 October 2020

React DOM - Fixes a crash in IE11

17.0.2

22 March 2021

React DOM - Remove an unused dependency to address the  `SharedArrayBuffer`  cross-origin isolation warning.

18.0.0

29 March 2022

Concurrent React, Automatic batching, New Suspense Features, Transitions, Client and Server Rendering APIs, New Strict Mode Behaviors, New Hooks  [[43]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-43)

## Licensing[[edit](https://en.wikipedia.org/w/index.php?title=React_(JavaScript_library)&action=edit&section=17 "Edit section: Licensing")]

The initial public release of React in May 2013 used the  [Apache License 2.0](https://en.wikipedia.org/wiki/Apache_License_2.0 "Apache License 2.0"). In October 2014, React 0.12.0 replaced this with the  [3-clause BSD license](https://en.wikipedia.org/wiki/BSD_licenses#3-clause "BSD licenses")  and added a separate PATENTS text file that permits usage of any Facebook patents related to the software:[[44]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-44)

> The license granted hereunder will terminate, automatically and without notice, for anyone that makes any claim (including by filing any lawsuit, assertion or other action) alleging (a) direct, indirect, or contributory infringement or inducement to infringe any patent: (i) by Facebook or any of its subsidiaries or affiliates, whether or not such claim is related to the Software, (ii) by any party if such claim arises in whole or in part from any software, product or service of Facebook or any of its subsidiaries or affiliates, whether or not such claim is related to the Software, or (iii) by any party relating to the Software; or (b) that any right in any patent claim of Facebook is invalid or unenforceable.

This unconventional clause caused some controversy and debate in the React user community, because it could be interpreted to empower Facebook to revoke the license in many scenarios, for example, if Facebook sues the licensee prompting them to take "other action" by publishing the action on a blog or elsewhere. Many expressed concerns that Facebook could unfairly exploit the termination clause or that integrating React into a product might complicate a startup company's future acquisition.[[45]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-45)

Based on community feedback, Facebook updated the patent grant in April 2015 to be less ambiguous and more permissive:[[46]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-46)

> The license granted hereunder will terminate, automatically and without notice, if you (or any of your subsidiaries, corporate affiliates or agents) initiate directly or indirectly, or take a direct financial interest in, any Patent Assertion: (i) against Facebook or any of its subsidiaries or corporate affiliates, (ii) against any party if such Patent Assertion arises in whole or in part from any software, technology, product or service of Facebook or any of its subsidiaries or corporate affiliates, or (iii) against any party relating to the Software. [...] A "Patent Assertion" is any lawsuit or other action alleging direct, indirect, or contributory infringement or inducement to infringe any patent, including a cross-claim or counterclaim.[[47]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-47)

The  [Apache Software Foundation](https://en.wikipedia.org/wiki/Apache_Software_Foundation "Apache Software Foundation")  considered this licensing arrangement to be incompatible with its licensing policies, as it "passes along risk to downstream consumers of our software imbalanced in favor of the licensor, not the licensee, thereby violating our Apache legal policy of being a universal donor", and "are not a subset of those found in the [Apache License 2.0], and they cannot be sublicensed as [Apache License 2.0]".[[48]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-48)  In August 2017, Facebook dismissed the Apache Foundation's downstream concerns and refused to reconsider their license.[[49]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-49)[[50]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-50)  The following month,  [WordPress](https://en.wikipedia.org/wiki/WordPress "WordPress")  decided to switch its Gutenberg and Calypso projects away from React.[[51]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-51)

On September 23, 2017, Facebook announced that the following week, it would re-license Flow,  [Jest](https://en.wikipedia.org/wiki/Jest_(JavaScript_framework) "Jest (JavaScript framework)"), React, and Immutable.js under a standard  [MIT License](https://en.wikipedia.org/wiki/MIT_License "MIT License"); the company stated that React was "the foundation of a broad ecosystem of open source software for the web", and that they did not want to "hold back forward progress for nontechnical reasons".[[52]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-52)

On September 26, 2017, React 16.0.0 was released with the MIT license.[[53]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-53)  The MIT license change has also been backported to the 15.x release line with React 15.6.2.[[54]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-54)

### Q.1) What is Emmet ?

> Emmet is a free add-on for your text editor. It allows you to type shortcuts that are then expanded into full pieces of code. By using Emmet, developers type less, they save both on keystrokes and time. Also relying on Emmet's auto completion means fewer typos and missing tags, leading to more robust and valid files

### Q.2) Difference between a Library and Framework?

* Library:
> A library is a collection of pre-written code or software modules that provide specific functionalities,such as data manipulation, networking, or user interface components. It typically consists of a set of functions, classes, or methods that developers can use to perform specific tasks in their programs. Libraries are usually focused on providing reusable code for specific purposes, and developers can include them in their projects by importing or linking to the library. Libraries often offer flexibility and allow developers to choose which components or functions to use based on their needs.

* Libraries:
> * NumPy: A popular library for numerical computing in Python. It provides efficient array manipulation and mathematical operations.
> * React: A JavaScript library for building user interfaces. It enables developers to create reusable UI components and efficiently manage component state.
> * Pandas: A library for data manipulation and analysis in Python. It offers high-level data structures and functions to handle and analyze structured data.
> * Retrofit: A library for making HTTP requests in Android applications. It simplifies the process of interacting with RESTful APIs by providing a high-level abstraction.

* Framework:
> A framework, on the other hand, is a more comprehensive and structured software tool that provides a foundation or skeleton for building applications. It includes a set of libraries, tools, and conventions that guide developers in designing and developing applications within a specific domain. Frameworks define the overall structure, architecture, and flow of an application, and they often impose certain constraints or rules to enforce best practices. Developers build their applications by extending or customizing the framework's predefined classes, methods, and components.

* Frameworks:
> * Django: A high-level Python web framework that follows the Model-View-Controller (MVC) architectural pattern. It provides a complete solution for building web applications, including an ORM, templating engine, and routing system.
> * Ruby on Rails: Also known as Rails, it is a web application framework written in Ruby. Rails follows the convention-over-configuration principle and provides a set of tools and libraries for building database-backed web applications.
> * Angular: A TypeScript-based framework for building dynamic web applications. Angular provides a robust structure for creating complex, single-page applications with features like data binding, dependency injection, and component-based architecture.
> * Express.js: A minimalist web application framework for Node.js. It simplifies the creation of server-side applications and APIs by providing a lightweight and flexible set of features for routing, middleware handling, and request/response handling.

### Q.3) What is CDN? Why do we use it?

* CDN (Content Delivery Network)

> CDN stands for Content Delivery Network. It is a distributed network of servers strategically placed in multiple locations around the world to deliver web content efficiently to users.

> The main purpose of using a CDN is to enhance the performance, reliability, and scalability of delivering web content, such as images, videos, HTML files, and other static or dynamic assets, to end users. Here are some of the key reasons why CDN is used:

> 1. **Improved website performance**: By placing servers closer to end users, a CDN reduces the network latency and minimizes the distance that data needs to travel. This results in faster content delivery, reduced page load times, and improved overall website performance. Users experience quicker access to content, which is crucial for a positive user experience.

> 2. **Global reach**: CDNs have a network of servers spread across various geographical locations worldwide. This enables them to serve content from the server that is closest to the user, reducing the distance data needs to travel and improving the response time. CDNs ensure that users in different regions can access content quickly and reliably.

> 3. **Scalability and high availability**: CDNs are designed to handle high volumes of traffic and sudden spikes in demand. By distributing the load across multiple servers, they can efficiently handle increased traffic without overloading the origin server. CDNs also provide redundancy, ensuring high availability by automatically routing traffic to an alternative server if one server becomes unavailable.

> 4. **Bandwidth optimization**: CDNs help reduce the bandwidth usage of the origin server. When a user requests content, the CDN delivers it from its cache if it is already stored there. This reduces the load on the origin server and conserves bandwidth, especially for static content that doesn't change frequently.

> 5. **DDoS mitigation**: CDNs can provide protection against Distributed Denial of Service (DDoS) attacks by absorbing and mitigating malicious traffic. By distributing the traffic across multiple servers, a CDN can better handle and filter out unwanted requests, ensuring the availability of the website during an attack.

>Overall, CDNs offer significant performance improvements, global reach, scalability, and high availability.



### Q.4) Why is React known as React?

> React is called React because it was designed to be a declarative, efficient, and flexible JavaScript library for building user interfaces.

> The name "React" was chosen because the library was designed to allow developers to "react" to changes in state and data within an application, and to update the user interface in a declarative and efficient manner.

> React was developed by Facebook and released in 2013, and it has since become one of the most popular JavaScript libraries for building web and mobile applications. It is used by many companies and organizations around the world, and it has a large and active developer community.

### Q.5) What is crossorigin in script tag?

> As we know that HTML introduces many elements and attribute that have some definition and specification that will be used for the enhancement of web development. In this article, we will learn how to use crossorigin attributes in HTML.

> The purpose of crossorigin attribute is used to share the resources from one domain to another domain. Basically, it is used to handle the CORS request. It is used to handle the CORS request that checks whether it is safe to allow for sharing the resources from other domains. The resources may include Audio, Video, Images, Link or external script that specifies whether to support a cross-origin request or not.

> * CORS: It stands for cross-origin resource sharing. It is a mechanism by which one webpage requests to another domain for fetching out the resource like audio, video, script, etc. from the third party server without leaking their credentials information. 

> * Values: This attribute contains two values which are given below – <br/>
 > anonymous: It has a default value. It defines a CORS request which will be sent without passing the credential information. <br/>
 > use-credentials: A cross-origin request will be sent with credentials, cookies, and certificate.

### Q.6) What is diference between React and ReactDOM
## Difference between React and ReactDOM

> React and ReactDOM are two separate packages in the React ecosystem, each serving a different purpose.

> 1. **React**: React is the core library for building user interfaces. It provides the foundation for creating reusable UI components and managing their state. React is responsible for the declarative syntax, virtual DOM diffing algorithm, component lifecycle methods, and other essential features for building UIs.

> 2. **ReactDOM**: ReactDOM is a package specifically designed for rendering React components into the DOM (Document Object Model). It serves as the bridge between React and the browser's DOM. ReactDOM provides methods and APIs for rendering React elements and components, manipulating the DOM, and handling events.



### Q.7) What is difference between react.development.js and react.production.js files via CDN?

### Q.8) What is async and defer?

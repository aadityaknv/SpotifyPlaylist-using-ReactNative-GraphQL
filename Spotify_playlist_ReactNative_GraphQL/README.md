# Code a playlist app with GraphQL and React Native

## Introduction to Today's Workshop

Using Node.js to develop a program which will be deployed using Expo Client and will fetch data from a Sandbox Repository running a GraphQL database, finally developing this into a working application. <br/>

![functional diagram](https://user-images.githubusercontent.com/32713072/57015916-4f833000-6c28-11e9-9b68-f290b13a98d1.png)

## Node.js

Node.js is an *asynchronous* event-driven open-source, cross-platform run-time environment that executes JavaScript code outside of a browser. Node.js, lets developers use JavaScript to write command line tools and for *server-side* scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser.

**Npm** is a package manager for the JavaScript programming language. It is the default package manager for the JavaScript runtime environment Node.js.


## React Native

React Native is a JavaScript framework for writing real, natively rendering mobile applications for iOS and Android. It’s based on React, Facebook’s JavaScript library for building user interfaces, but instead of targeting the browser, it targets mobile platforms. In other words: web developers can now write mobile applications that look and feel truly *native* to all from the comfort of a JavaScript library that we already know. React Native makes it easy to simultaneously develop for both Android and iOS.

## Expo Client 

- Expo is a toolkit that wraps around React Native projects to remove dependency on Xcode/Android SDK 
- It allows for quick testing and pre-release deployment 
- Additional UI components, access to more device functionality 
- Push notifications are easy to deploy

## GraphQL 

GraphQL is an open-source data query and manipulation language for APIs, and a runtime for fulfilling queries with existing data. GraphQL was developed internally by Facebook in 2012 before being publicly released in 2015. 

It provides an efficient, powerful and flexible approach to developing web APIs, and has been compared and contrasted with other web service architectures. It allows clients to define the structure of the data required, and exactly the same structure of the data is returned from the server, therefore preventing excessively large amounts of data from being returned

A graph database is a database that uses graph structures for semantic queries with nodes, edges and properties to represent and store data. A key concept of the system is the graph (or edge or relationship), which directly relates data items in the store a collection of nodes of data and edges representing the relationships between the nodes. The relationships allow data in the store to be linked together directly, and in many cases retrieved with one operation. Graph databases hold the relationships between data as a priority. Querying relationships within a graph database is fast because they are perpetually stored within the database itself. Relationships can be intuitively visualized using graph databases, making it useful for heavily inter-connected data.

Graph databases are part of the NoSQL databases created to address the limitations of the existing relational databases. While the graph model explicitly lays out the dependencies between nodes of data, the relational model and other NoSQL database models link the data by implicit connections. Graph databases, by design, allow simple and fast retrieval of complex hierarchical structures that are difficult to model in relational systems. Graph databases are similar to 1970s network model databases in that both represent general graphs, but network-model databases operate at a lower level of abstraction and lack easy traversal over a chain of edges.

GraphQL is a syntax that describes how to ask for data and is generally used to load data from a server to a client. GraphQL has three main characteristics:

- It lets the client specify exactly what data it needs.
- It makes it easier to aggregate data from multiple sources.
- It uses a type system to describe data.

Apollo Client is the best way to use GraphQL to build client applications. The client is designed to help you quickly build a UI that fetches data with GraphQL and can be used with any JavaScript front-end.

Apollo Server is the best way to quickly build a production-ready, self-documenting API for GraphQL clients, using data from any source.

It's open-source and works great as a stand-alone server, an addon to an existing Node.js HTTP server, or in "serverless" environments

We also used **CodeSandBox** for running the Apollo server. CodeSandbox is an online editor that's built for web application development. It makes it easier by doing most configuration for you.


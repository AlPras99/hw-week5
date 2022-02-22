# GraphQL by Example
More and more teams are choosing GraphQL instead of (or along with) REST for their web APIs. GraphQL queries give clients great flexibility in the way they request data from the server, preventing issues such overfetching or underfetching of data, and allowing multiple resources to be retrieved in a single request.

## Installation Apollo Server
Version 3.0 of Apollo Server — the library used to write GraphQL servers — was released in July 2021. The videos in this course were recorded using the previous version, i.e. Apollo Server 2.x. There are only a few differences between v2 and v3, and all the concepts explained in the course remain valid.
However v3 does not include by default some features that are available out of the box with v2, such as the GraphQL Playground, a visual tool to test GraphQL queries in the browser. To be able to follow the examples exactly as they are shown in the videos, please install Apollo Server 2.x and not the latest version.
<ol>
  <li>In the next lecture, "Defining a Schema", when the following command is shown:
  ```npm install apollo-server graphql```
  <h3><img width="570" alt="image" src="https://user-images.githubusercontent.com/85268103/155055362-955df667-6947-4159-a76e-a582c42141f5.png"></h3></li>
  <li>please run the following instead:
  ```npm install apollo-server@^2.25.3 graphql@^15.7.2```
    <h3><img width="687" alt="image" src="https://user-images.githubusercontent.com/85268103/155056154-d6634a86-71fb-44ff-83b0-ee478b72b3e2.png"></h3></li>
  <li>In Section 2, in the "Configuring Apollo Server with Express" lecture, instead of:
  ```npm install apollo-server-express graphql```
    <h3><img width="643" alt="image" src="https://user-images.githubusercontent.com/85268103/155056315-1ddb7462-2865-4ba7-b905-ebe199456d4d.png"></h3></li>
  <li>please run:
  ```npm install apollo-server-express@^2.25.3 graphql@^15.7.2```
    <h3><img width="664" alt="image" src="https://user-images.githubusercontent.com/85268103/155056386-26e5a5c6-6521-4df5-be6e-9ebbef4cdbe3.png"></h3></li>
</ol>

# RUN
```node server.js```

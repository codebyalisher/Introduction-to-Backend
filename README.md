**Introduction to Backend :**
![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/bd10fa63-dc82-4d81-ab2e-152bb18578f0)


\-How the internet works

What is a web server and how does it work

\-What are websites and webpages

\-What is a web browser and how does it work

\-Web hosting

Introduction to Internet Protocols

\-Introduction to HTTP

\-Webpages, Websites and Web Apps

\-Developer tools

\-Frameworks and libraries

\-APIs and services

\-What is a an IDE

\-What is Hyper Text Markup Language

\-HTML documents

\-Introduction to the DOM

\-Web accessibility

✒️

\-Working with libraries

\-Introduction to responsive design

\-Static and dynamic content

\-Single page applications

\-What is React

\-How React works

\-Component hierarchy

**General Backend Architecture :**
![Screenshot (19)](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/0cb046be-1138-47ca-9f15-57edc8f19de8)


**Front End/UI layer**

**API Layer**

**Middle Ware Layer Business Logic layer**

**Data Storage Layer Da Database Layer**

**Security Layer Third Party /External layer**

**Front end/ui layer:** This layer makes request to the api layer .it sends requests to the endpoint defined in the api layer.it also sends and receive the data from the api layer.

**Api Layer:** This layer acts as gateway between business logic layer and UI layer. It also can be connected with middleware layer to perform authentication tasks. It is Connected to the Business Logic layer which contains logic code and after processing task ,it receives the response and sends back to the ui layer.

**Business Logic Layer:** It is the one of the most important layer which contains the logic code to handle the data, database ,storage layer, and third party layer.This layer serves as the brain of the app to handle and process the different layer task .

**Database layer:** This layer stores the data and receive the request from the business logic layer to perform the db operations. It receives the request and after compilation the query ,send the data back to the business logic layer.

**External/ Third Party layer:** through this layer app is integrated with the external app by making api request and passes the data back to the business logic layer.

**Data Storage layer:** Provides Caching for faster data retrieved and storage ,sends cached record to the business logic layer when it request from the business logic layer.

**Security Layer:** Receives the request from api layer and process them to ensure the security measures are applied between front end and middleware.

**This was the General Backend Architecture and Now lets see the Web app architechre layers.**

**Here is the Web App Architecture:**

![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/7c1c6008-570e-47dd-b204-77ceac61b743)

**Modern Application Architechre:**

![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/4d56f9f9-0d63-4e6c-8fea-6d72483a754f)


**1-Route:** REST methods that responds the endpoints.

**Endpoints:** is a URL on which client can access the data/source.

**Backend consists**: Backend-Language, web server, Apis, Database It requires the knowledge of Setup, configuration, Resources.

**Difference between Server-Side-Rendering(SSR) and Client-side Rendering(CSR):**

**Server-Side-Rendering(SSR):** Here it is considered as a chef that make things ready to serve. It is a source which hold all the information about the website and serve when it is needed.

**Client-Side-Rendering(CSR):** You can consider it as your own kitchen where chef which is server here sends you the ingredients and you cook/render it in your own kitchen/browser. It is necessary for websites to change the content without page reloads.

**How Internet Works?:**

When machines/computers are connected to each other through interconnected switch and these switches are connected further to the switches to the rest of the world computers through wires or satellite or any other signal provider source .This mechanism of connectivity is called Internet .As in the diagrams

![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/9f4e2216-c75c-45f1-84fe-d19e07084fe2)
![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/8a79315d-1197-4fd9-a60d-6e2a549fd5a3)


![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/ec4220c1-7540-4a89-90b0-ae69d962dcfb) ![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/d25930c9-1218-47b2-847f-7b1c8eb32849)

**What is the server?**

The machine/processor that serve or response any other machine is called Server. Server also connected to the internet or they installed at the data center to provide the different services.![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/88dc568b-b9fb-4ee1-aef9-db8678c4efc3)
 img1.Data Center(Server Rack)![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/bdb42669-35b1-444d-a866-ef700c6b9175) ![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/5727cc0e-6edc-4cb9-b914-172715eda839)

Img 2: Data center 3-Server

**Data center** is the collection of the servers racks where Hardware Devices or Processors or Machines kept in these server racks in which our data is stored in these machines which are commonly known as **servers.** These server racks are the rectangle or vertical box where machines are installed. These Servers serve the different services not just to store the data but also many other services like cloud computing etc. They can run the code which is called **software.** They are also Connected to the internet through wires or satellite.

**Types of Servers:** They can be different types: **1) web servers** which can host webs, databases, Security etc. Handle web requests. This is also called the client server model.

![Screenshot (18)](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/3a481f1b-4e85-4243-9f18-da51b0f4c016)


In the above diagram client sends the request and receives the response through the browser to the server to access the content of the deployed website on this server.

**Webpages:** It is a document that display images, text, and other content.

**Website:** is a collection of webpages.

**Developing webpage:** HTML,CSS, JS

⇒**how browser display content**: It is software pit sends request to server by URL which contain protocol, domain name, file path/webpage .i e.http://domainame/webpage

**How request/response circle work:** client send the request and receive te response.

![Screenshot (18)](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/a643c0f3-6e1f-4365-9b4f-6a46f0da9e12)


**What is the Hosting:** It is simple to deploy or to put the website of individual or companies online on internet or server of any providing hosting companies.

**How does hosting works:** you can see the working in the diagram

![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/f1d00814-eba7-485f-9d5d-02931adebc39)


**=)Types of Hosting:**

**Shared Hosting:** In this type of hosting all the computers or machines use only one server for services.

**VPS/private hosting:** This hosting provides virtual machines separately for all the services buyer.

**Dedicated hosting:** This hosting provides a specific server to only one buyer

**Cloud hosting:** It is widely used services bcz it provides physical and virtual servers if one got suck then other starts providing the services.

![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/05cb22d8-ddb8-4d00-b8b0-910ed3d584a8)

![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/20b2c4e1-e5f1-488a-b116-3f6681fa35fc)


IP 041=127.0.1.23 → mean through four dot

→ **How IP address works:** IP versions: IP06 =1:1:27:01:23:26:5:6-through six dot

Internet assign IP to each connected machines and hence machines sends their data to each other using IP through IP packet series. IP Packet contains IP header (Contains destination IP and source Ip) and pay load(IP data). It also contain TCP ad UDP in order of wrong order, lost of Packets. They ensure packets/data arrive in order, don't damages / corrupted, lost during transit.

**⇒ HTTP:** Through then web browser can communicate to the hosting server. It is request-response based protocol i.e can load or access HTML, pages, Text, imager' etc.

**⇒ HTTP composition:** POST/GET/PUT/PATCH/DELETE and Headers .These method tells the action which will be done by client. Headers can also contain additional information.

→ **HTP response.** It contain message body content of webpage, Status Code

**⇒difference between website and webapplication:** difference is of interaction and dynamic

→ **Frameworks, Libraries, APIS** (Browser API, Restful API, Third Party API)→ Browser provides itself API to make new services like DOM API, Geolocation API, fetch API, Canvas API, History and web storage API.

**Refracturing:** Changing the structure of code without changing code functionalities is called Refracturing i-e definition and calling functions..

=) **How HTML came into being:** 1991 Berner Lee thought how to show the information to all the devices over net.

**HTML →** it is text file with Specific structure. As it is text file , so when it is in webpage formatting it is called HTML documents. in html file the first tag which is \<! DocType html\>which is telling that this document file now a html file/page

**=) DOM:** Everything is object of document, when it used. We have to change the object dynamically in Dom Tree. i.e. in this diagram we can see the DOM of html ![]![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/fcb53062-13ca-414a-a51d-9a877784f5db)


**=) JavaScript:** we can update or response the value/object action, Clicking, scrolling, Enabling/disabling button and much more. Also, I can update the value of the object by using JavaScript with DOM or simply DOM can be used.

**=) Accessibility:** Think at the start of project how or what to who to allow the access of web content. **Dependency/ Packages:** dependencies can depend on multiple dependencies, to handle this complexity npm comes into the field through which we can also use the version of dependency

. =\> **Bundle up:** To bundle all HTML, CSS, JS Files in a single file, if these are large the bundle can be made many. This split the dependency into many bundles.

**Set Rules for responsive design:** Fluid image, Flexible Grid, Media query These Three we used to design responsive design.

**=\> Static-Content**: The data stored on the web server transferred to the browser.

**dynamic-content:** The application server /backend generate the data on behalf of action and then sends to the web server. i.e. application serverweb serverbrowser.

**-⇒ Application server/backend:** It perform complex tasks like computing logic, Interacting with database and check permissions. To improve performance different application server has different purpose. It has limitation to response the click per second.

![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/cd9ed62e-2ca2-4e1f-bb5c-bd29494780a6)![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/922c60e6-4201-4e50-aa61-c3a79ea2300b)
⇒ **Caching:** Are stored copy of dynamic content readily available upon request. i.e. First image is web caching and Second image is about the database caching.

**React**: for SPA (single page Application) comes with built in component. A component is a small piece of code for UI. i. e on a page if we have to show the list of user with their icon and detail, we will use of REACT just like Flutter widgets. A browser read the component as DOM. So react DOM comes which act as virtual DOM mean ,the component/element has to update first it is updated in virtual DOM then in browser DOM se see its effects. Image

![image](https://github.com/codebyalisher/Introduction-to-Backend/assets/62823194/9ddb9849-788a-442c-ab6d-7fd05f91ebdd)


Everything on the webpage is a component.

⇒ **Component Hirarchy:** each component is added to the app component

Here component can be considered as rows, columns, text, videos, search etc.

**SPA:** **Two approaches** to show the content in the page in browser, **bundling** (to show the css, html, JS files immediately ), **Lazy loading** (necessary HTML,CSS, JS Content is sent by server to browser).

**\* IN SPA:** HTML page can be requested to server and it will display on the whole screen, similarly, We can do this in template view, where rest content will be same but the requested page or it's content is displayed inside the template view. SPA can also Show all the pages or one or few when loaded on browser.

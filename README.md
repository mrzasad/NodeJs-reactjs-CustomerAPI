<h1>Components</h1>
Customer portal consists of three fundamental components:<br/>
1. Front-end: Written on ReactJS<br/>
2. Back-end REST API: Implemented on Node.js<br/>
3. Database server: Mongo Database<br/>


<h1>Deployment Procedure</h1><br/>
1. Open nodejsserver folder and open startapi.js file to change db server url if required.<br/>

2. Open nodejsserver folder in terminal and run the following commands:<br/>
<strong>npm install</strong><br/>
<strong>node startapi.js</strong><br/>
server will start listening for API calls at localhost:3001<br/>

3. Open reactdemoapp folder in terminal and run the following commands:<br/>
<strong>npm install</strong><br/>
<strong>npm start</strong><br/>

Browser window will be open showing home page at localhost:3000.<br/>

4. Click Add and enter details of customers. On successful data submission, it will redirect to the list of customers.<br/>

5. Click Edit at the end of each row to edit any individual user.<br/>

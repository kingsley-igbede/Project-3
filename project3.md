## Step 1 - Backend Configuration

*Update ubuntu*

`sudo apt update`

*Upgrade ubuntu*

`sudo apt upgrade`

*Ubuntu Status*

`sudo systemctl status`

![ubuntu status](./images/ubuntu-status.jpg)

*Node.js software location*

`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`

*Install Node.js*

`sudo apt-get install -y nodejs`

*Verify Node.js*

`node -v`

`npm -v`

![verify nodejs](./images/verify-nodejs.jpg)

*Application Code Setup - Create a new directory for your To-Do project:*

`mkdir Todo`

`ls`

`ls -lih`

`cd Todo`

![Todo Directory](./images/todo-directory.jpg)


*Initialize Project*

`npm init`

`ls`

![project initialize](./images/initialize-project.jpg)


### Step 2 - Install Express JS

*Install it using npm*

`npm install express`

![install express](./images/install-express.jpg)

*create file*

`touch index.js`

`ls`

![create file](./images/create-file.jpg)

*Install dotenv*

`npm install dotenv`

![install dotenv](./images/dotenv.jpg)

*Open the index.js file with the command below*

`vim index.js`

*Start server*

`node index.js`

![server update](./images/server-running.jpg)

*Access server on browser on port 5000*

`http://<PublicIP-or-PublicDNS>:5000`

![access server](./images/access-server.jpg)

*Creating routes*

`mkdir routes`

`cd routes`

*create a file api.js*

`touch api.js`

*Open the file with the command below*

`vim api.js`


### Step 3 - Models

*Install Mongoose*

`npm install mongoose`

![install mongoose](./images/mongoose.jpg)

*Create a new folder models*

`mkdir model`

`cd model`

`mkdir model && cd model && touch todo.js`

`vim todo.js`

### Step 4 - MongoDB Database

*Create a file in your Todo directory and name it .env*

`touch .env`

`vi .env`

*Add the connection string to access the database*

`DB = 'mongodb+srv://<username>:<password>@<network-address>/<dbname>?retryWrites=true&w=majority'`

*Update the index.js to reflect the use of .env*

`vim index.js`

*Start your server using the command*

`node index.js`

![database conected](./images/database-connected.jpg)

*Testing Backend Code without Frontend using RESTful API*


*create a POST request on Postman to the API*

`http://<PublicIP-or-PublicDNS>:5000/api/todos.`

![postman](./images/postman.jpg)

![POST request](./images/postman-POST.jpg)

*Perform a GET request on Postman to the API*

`http://<PublicIP-or-PublicDNS>:5000/api/todos.`

![GET request](./images/postman-GET.jpg)

*Perform a DELETE request on Postman to the API*

To delete a task – i sent the ID as a part of DELETE request

![DELETE request](./images/postman-DELETE.jpg)

![DB status](./images/DB-DELETE-status.jpg)















































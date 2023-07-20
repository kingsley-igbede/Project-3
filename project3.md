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




















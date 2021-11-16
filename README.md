
<h3>cloud topology diagram</h3>

<img src="https://user-images.githubusercontent.com/83788264/141863654-2b3db699-db23-4ff7-aff8-a2a408e34782.png" width=500 height=300>


In our cloud provider we can see the topology to stage & production

<img src="https://user-images.githubusercontent.com/83788264/141863894-c385fd28-4252-44d8-8e55-f88457a42d54.png" width=500 height=200>
<br>

<h3>login into VM </h3>

`ssh -p PORT user@ip (loadbalncer ip)`

`sudo apt-get update`

`sudo apt install docker.io`

`sudo chmod 777 docker.sock`

`install agent pool from Azure DevOps on on vm in one machine in the staging or production`

<img src="https://user-images.githubusercontent.com/83788264/141866462-9d4ab140-e6bd-4586-9f1e-9a04625d5126.png" width=200 height=200>

`install from Azure DevOps envirment script on ant machine for each group `

`located in azure devops pipline envirement`

<img src="https://user-images.githubusercontent.com/83788264/141866822-9bce7e20-0644-4275-99b1-108ee34d195c.png" width=200 height=300>

<img src="https://user-images.githubusercontent.com/83788264/141866628-ca9debe8-4ef8-4053-bea5-0edcb42d414c.png" width=200 height=300>

`create container registry in Azure`

<img src="https://user-images.githubusercontent.com/83788264/141867903-c12d06e9-d53a-4261-8cde-10f8dbd5ddca.png" width=800 height=100>

`choose where you want to take the repository`

<img src="https://user-images.githubusercontent.com/83788264/141867175-402cbd5c-7e96-443b-a64b-03f8f6c7b48c.png" width=600 height=400>



<img src="https://user-images.githubusercontent.com/83788264/141867420-aaa1cb42-6e97-426d-9d06-ca0819f1e120.png" width=700 height=200>


`azure-pipline.yaml`

`ci-cd pipline`

<img src="https://user-images.githubusercontent.com/83788264/141868587-b20fce34-2d0b-4d90-80d0-b4de8d1f7f28.png" width=700 height=200>

`config commit to master will need approval`

<img src="https://user-images.githubusercontent.com/83788264/141868820-89f241ff-3747-44bd-9a83-5f9bcc7def30.png" width=700 height=200>
<img src="https://user-images.githubusercontent.com/83788264/141869036-f9ca56b2-7563-49c9-acfc-7f0c60dd601f.png" width=400 height=200>
<img src="https://user-images.githubusercontent.com/83788264/141869205-4e019b93-3864-4919-b5e7-2225eb3f40e9.png" width=600 height=200>





# Node.js Weight Tracker

![Demo](docs/build-weight-tracker-app-demo.gif)

This sample application demonstrates the following technologies.

* [hapi](https://hapi.dev) - a wonderful Node.js application framework
* [PostgreSQL](https://www.postgresql.org/) - a popular relational database
* [Postgres](https://github.com/porsager/postgres) - a new PostgreSQL client for Node.js
* [Vue.js](https://vuejs.org/) - a popular front-end library
* [Bulma](https://bulma.io/) - a great CSS framework based on Flexbox
* [EJS](https://ejs.co/) - a great template library for server-side HTML templates

**Requirements:**

* [Node.js](https://nodejs.org/) 12.x or higher
* [PostgreSQL](https://www.postgresql.org/) (can be installed locally using Docker)
* [Free Okta developer account](https://developer.okta.com/) for account registration, login

## Install and Configuration

1. Clone or download source files
1. Run `npm install` to install dependencies
1. If you don't already have PostgreSQL, set up using Docker
1. Create a [free Okta developer account](https://developer.okta.com/) and add a web application for this app
1. Copy `.env.sample` to `.env` and change the `OKTA_*` values to your application
1. Initialize the PostgreSQL database by running `npm run initdb`
1. Run `npm run dev` to start Node.js

The associated blog post goes into more detail on how to set up PostgreSQL with Docker and how to configure your Okta account.


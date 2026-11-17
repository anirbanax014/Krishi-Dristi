<h1 align="center">Krishi Dristi</h1>

<div align="center">



 
</div>



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#-table-of-contents)

This folder contains most of the backend. The backend follows a microservice architecture, there are many microservices nd these services communicate with each other through HTTP requests and the fronend communicates with the frontend via an API-gateway. The authentication service uses mongoDB and redis cache for user authentication. THe dl service uses ResNet9 as Deep Learning Model and flask server for deploying this model into an API, while the nginx acts as an API gateway.


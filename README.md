# fullstack_developer_capstone

## Full Stack Developer Capstone Project

This project is a full-stack car dealership application developed as part of the IBM Full Stack Developer Capstone Project.

The application provides a web-based platform for browsing car dealerships, viewing dealership information, viewing dealer reviews, searching dealerships by state, submitting reviews, and analyzing review sentiment.

## Project Name

**fullstack_developer_capstone**

## Technologies Used

* React.js
* Django
* Python
* Node.js
* Express.js
* MongoDB
* Flask
* TextBlob
* Docker
* Kubernetes
* GitHub Actions
* HTML
* CSS
* Bootstrap
* JavaScript

## Application Features

### User Features

* User registration
* User login and logout
* Browse dealerships
* Search dealerships by state
* View dealership details
* View dealership reviews
* Submit dealership reviews
* Sentiment analysis of reviews

### Dealership Features

* Display dealership information
* Display dealership location
* Display dealership contact information
* Display dealership reviews
* Filter dealerships by state
* Retrieve dealer information through REST APIs

### Admin Features

* Django administration interface
* Manage application data
* Manage users and application records

## Application Architecture

The application uses multiple components:

* **React Frontend** — Provides the user interface.
* **Django Backend** — Handles the main web application and user functionality.
* **Node.js / Express** — Provides dealership and review REST APIs.
* **MongoDB** — Stores dealership and review data.
* **Flask Sentiment Service** — Performs sentiment analysis on review text.
* **Docker** — Containerizes the application services.
* **Kubernetes** — Deploys and manages the application containers.
* **GitHub Actions** — Performs automated code linting and CI/CD tasks.

## Main API Endpoints

The application includes endpoints for:

* `/djangoapp/login`
* `/djangoapp/logout`
* `/fetchDealers`
* `/fetchDealer/<dealer_id>`
* `/fetchDealers/<state>`
* `/fetchReviews/dealer/<dealer_id>`
* `/djangoapp/get_cars`
* `/analyze/<text>`

## Running the Application

The application can be run using Docker and Docker Compose.

```bash
docker compose up --build
```

After the containers are running, the individual services communicate through their configured application ports.

## Project Objective

The objective of this project is to demonstrate full-stack development skills by integrating frontend development, backend development, REST APIs, databases, authentication, sentiment analysis, containerization, Kubernetes deployment, and continuous integration.

## Author

**Rohit Sudhir Nikam**

B.Tech Computer Engineering
VIT Pune

## License

This project was developed for educational and academic purposes as part of the IBM Full Stack Developer Capstone Project.

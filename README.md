# Movie Recommender

## Overview
Movie Recommender is a dynamic web platform designed to help users search, explore, and manage movies through a personalized recommendation experience. The platform uses user preferences, ratings, and watch history to suggest movies tailored to individual interests.


---
## Why This Project? 

Traditional movie platforms provide access to movie information but often lack personalized interaction and scalable user-centric features. This project focuses on improving user experience through recommendation-driven functionality, secure authentication, and better system organization.

The application enables users to:
- Search and explore movies
- Maintain watched history
- Manage personalized wishlists
- Review and rate movies
- Receive personalized movie recommendations

---
## Improvements Made

### Database Integration  
Replaced local file references with database-driven storage  
Improved scalability and maintainability for movie and user data  
Addressed limitations of CSV-based storage systems

---

### Docker Containerization  
Implemented Docker support for simplified deployment  
Created Docker Compose configurations for streamlined setup  
Improved consistency across development and deployment environments

---

### Database Integration  
Replaced local file references with database-driven storage  
Improved scalability and maintainability for movie and user data  
Addressed limitations of CSV-based storage systems

---

### Kubernetes Configuration  
Added YAML configuration files for Kubernetes deployment  
Tested deployment using Minikube  
Improved scalability support for larger environments  

---

### Two-Factor Authentication (My Contribution)  
Implemented Two-Factor Authentication (2FA) for improved account security  
Added an additional verification layer during user authentication  
Enhanced protection for user login workflows

---

### Organized Wishlist (My Contribution)  
Improved wishlist organization and movie management  
Enabled users to maintain cleaner and more structured collections  
Enhanced overall usability and user experience

---

### Automated Testing (My Contribution)  
Expanded automated test coverage for backend endpoints and workflows  
Improved reliability and maintainability of the application  
Added testing support for newly implemented features 

---

## Tech Stack

**Frontend**
- HTML5  
- CSS3  
- JavaScript

**Backend**  
- Python  
- Flask  

**Database**
- SQLite   

---

**DevOps & Deployment**  
- Docker  
- Docker Compose  
- Kubernetes  
- Minikube

---

**Testing**
- Automated API and endpoint testing


## Project Structure
```bash
MovieRecommender/
├── .github/                 # GitHub workflows/config
├── .idea/                   # IDE configuration files
├── asset/                   # Static assets and resources
├── badges/                  # Project badges and status assets
├── Code/                    # Main application source code
├── data/                    # Dataset and movie-related data
├── experiment_results/      # Experimental/testing outputs
├── instance/                # Instance-specific configuration/data
├── myenv/                   # Virtual environment
├── test/                    # Automated test cases
├── docker-compose.yml       # Docker Compose configuration
├── Dockerfile               # Docker container setup
├── flask-app.yaml           # Kubernetes/Flask deployment config
├── requirements.txt         # Python dependencies
├── setup.py                 # Project setup configuration
├── README.md                # Project documentation
└── .gitignore               # Git ignore rules
```

---


## How to Run the Project

1. Clone repository
   ```bash
   git clone https://github.com/nikhita003/MovieRecommender.git
   
2. Install dependencies
   ```bash
   pip install -r requirements.txt

3. Run application
   ```bash
   python app.py

4. Docker Deployment
    ```bash
   docker-compose up



## Features
- User authentication and account management
- Movie search and exploration
- Personalized movie recommendations
- Wishlist management
- Watched history tracking
- Movie ratings and reviews
- Secure authentication workflows
- Containerized deployment support


## Features
- Implemented Two-Factor Authentication (2FA) for improved account security
- Developed organized wishlist functionality for better movie management
- Expanded automated testing coverage for improved reliability
- Collaborated on deployment modernization using Docker and Kubernetes


## Future Improvements
- Add advanced review systems using star-based or graded reviews
- Expand scalability with larger cloud-based database systems
- Introduce user comments and social interaction features
- Improve recommendation accuracy using machine learning models
- Deploy across multiple cloud regions for high availability



## License

MIT License

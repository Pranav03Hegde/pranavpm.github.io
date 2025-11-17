# Hi, I'm Pranav P M 

I’m a B.Tech 2025 graduate interested in Data Engineering, ML basics and Python development.  
I like working on small projects that help me understand how data flows, how models are built, and how simple deployment works.
I enjoy experimenting and trying to build things on my own.

---

## Skills (Beginner → Intermediate)
**Languages:**  
- Python (scripting, basic automation)  
- SQL (joins, aggregations, window functions)

**Data & ML:**  
- Pandas (data cleaning, transformation)  
- Basic Machine Learning (Logistic Regression, SVM, KNN)  
- ETL pipeline basics  
- Simple data validation

**Cloud & DevOps:**  
- AWS S3 & EC2 (beginner)  
- Docker (container basics)  
- Git & GitHub (version control, CI/CD basics)

**Databases:**  
- MySQL  
- MongoDB  

---

## Projects

### 1. Insurance Risk Prediction (End-to-End ML Pipeline)
This is the project where I learned the most.  
I worked on everything from reading raw data to preparing the data, training models and creating a small API.

What I did:
- Designed a clean and scalable project template using Python packaging + modular code structure
- Set up MongoDB Atlas to store the raw dataset and wrote scripts to ingest and validate data
- Performed detailed EDA and data preprocessing (encoding, scaling, schema checks, splitting, etc.)
- Trained and tuned a Random Forest model using RandomizedSearchCV
- Stored and versioned the model automatically in AWS S3
- Built a complete prediction pipeline + Flask API to serve predictions
- Containerized the app using Docker
- Implemented CI/CD using GitHub Actions, where:
- every push builds a new Docker image
- pushes it to AWS ECR
- automatically deploys it on an EC2 instance via a GitHub self-hosted runner

#### Key learnings:
- Class imbalance can completely spoil model performance even if the overall accuracy looks good
- CI/CD removes so many manual steps — it feels like “magic” when deployment happens automatically
- Cloud services (IAM, S3, ECR, EC2) are essential parts of a modern ML workflow
- Logging, exception handling, and version control are as important as the model itself
  
I learned that building a model is actually the easiest part, the real challenge is making it reliable and deployable.
This project helped me understand the overall workflow from data to model to API.

🔗 *[Repo link](https://github.com/Pranav03Hegde/Vehicle-Insurance-Prediction)*

---

### 2. Lung Disease Detection (Machine Learning + Image Processing)

This was one of the first projects where I worked with image data instead of normal CSV files.  
My main aim was to understand how medical images can be preprocessed and used to train simple ML models.

#### What I built and learned:
- Preprocessed X-ray images by resizing, normalizing and converting them into a format suitable for ML models
- Explored different feature extraction and preprocessing techniques
- Trained two classic ML models (SVM and KNN) and compared their accuracy
- Built a small Flask interface where an X-ray image can be uploaded to get a prediction
- Organized the project with separate modules for preprocessing, model loading and prediction

#### Why this project was helpful
Until this project, I had only worked with tabular data.  
Trying out image classification taught me:

- how images are represented numerically  
- how preprocessing affects model performance  
- how to structure ML projects neatly  
- how to build a simple end-to-end workflow (image → model → result)  

It also helped me get more comfortable with Flask and connecting a model to a user interface.

🔗 *[Repo link](https://github.com/Pranav03Hegde/lung_disease_prediction_system)*

---

### 3. HR Management System (PHP + MySQL)

This was a web-based project I built mainly to understand how backend systems and database-driven applications work.  
I used PHP for almost all the backend logic and MySQL for storing employee information.

#### What I built and how it works:
- Created two separate login systems:  
  - **Employee login** – for applying leave, viewing profile, etc.  
  - **Admin/Employer login** – for approving/rejecting leave requests and managing employee details  
- Designed simple pages using **HTML and CSS** for forms and dashboards  
- Wrote PHP scripts to handle authentication, leave submission, approval flow and profile updates  
- Stored employee information (name, phone number, email, location, department etc.) in a MySQL database  
- Used separate PHP files on the admin side to track and manage all employee-related actions  
- Implemented basic CRUD operations for employee data

#### What this project taught me:
This project helped me understand:
- how backend and frontend connect through form submissions  
- how data flows from UI → PHP → MySQL and back  
- the importance of organizing backend code into modules  
- how login systems, sessions and role-based access work in web apps

It was a good starting point for learning how real web applications store and manage data.

🔗 *[Repo link](https://github.com/Pranav03Hegde/HRMS)*


---

## My goal
I want to start my career where I can keep learning and work on data-related projects.  
I enjoy understanding how things work from the basics and improving slowly.

---

## Connect with me
*[LinkedIn](www.linkedin.com/in/pranav108)*  
*[Email](prannavpm@gmail.com)* 
*[GitHub](https://github.com/Pranav03Hegde)*

# SDTS-A25-CS070
Documentation and supporting assets for project review and submission purposes.

![alt_text](https://github.com/moonstone00/SIDETS-A25-CS070/blob/main/assets/logo-sdts.png?raw=true)

# **SDTS : Smart Deposit Targeting System** 

#### Use this website to avoid calling customers carelessly.

This repository is the Capstone Project in [Asah Dicoding](https://www.dicoding.com/asah) 2025. This application helps sales to avoid contacting random customers and contact customers whoe are likely to take desposits.  

## Our Team
| Name                            | Bangkit-ID    | Path                     |
| -------------                   | ------------- | ------------------------ |
| Andreas Rameladi                | M891D5Y0219   | Machine Learning         |
| Fauzi Hendrawan                 | M891D5Y0622   | Machine Learning         |
| Muhammad Helmi Arrizal          | R891D5Y1289   | React & Back-End with AI |
| Muhammad Ghifani Ikhsan         | R891D5Y1279   | React & Back-End with AI |
| Wahyu Hidayat                   | R891D5Y1949   | React & Back-End with AI |

## Usage
### How to use this website:
  #### Sales:
  - Open a browser and type localhost:5173.
  - On the login screen, enter your NIP (nomor induk pegawai) and password.
  - If you don't have an account then you can't log in
  - There is no registration here because, only sales people who work at the bank.
  - After logging in, you can check the table to cantact customers.
  - Look at the priority column to determine whether you should call or chat. 
  - Click the number to make contact.
  #### Admin:
  - Admin can register sales data via Swagger.
  - Open a browser and type http://localhost:5000/api-docs/#/
  - In the admin role there is an additional page, namely predict-nasabah.
  - When making a prediction, the admin must enter customer data and sales NIP, so that only one sales person can contact the customers.

### What is the meaning of the chart?
  - There is an annual graph to see traffic per year.
  - There is an week grap to see traffic per week.
  - There is a doughnut chart to see the percentage of yes and no.

## About
- Predicts customers who are likely to subscribe to deposit products using Machine Learning
- Helps the sales team prioritize customers for calls and follow-up actions
- Presents data visualizations in the form of charts and tables
- Provides an interactive dashboard to monitor prediction results and statistics
  
## 📸 Screenshots
||||
|:----------------------------------------:|:-----------------------------------------:|:-----------------------------------------: |
| ![](../splash.png) | ![](../onboarding.png) | ![](../login.png) |
| ![](../home.png) | ![](../diagnose.png) | ![](../result.png) |

## Built With 🛠
### Frontend
- [React](https://react.dev/) – A JavaScript library for building component-based user interfaces.
- [Material UI (MUI)](https://mui.com/) – A modern Material Design–based UI component library for React.
- [TanStack Query](https://tanstack.com/query/latest) – A library for handling server state, data fetching, caching, and mutations (GET, POST, PUT, DELETE).
- [Formik](https://formik.org/) – A library for managing and handling forms in React.
- [Yup](https://github.com/jquense/yup) – A schema-based validation library for form data validation.
- [Axios](https://axios-http.com/) – A promise-based HTTP client for communicating with REST APIs.

### Backend
- [Express.js](https://expressjs.com/) – A Node.js backend framework for building RESTful APIs.
- [Multer](https://github.com/expressjs/multer) – Middleware for handling multipart/form-data and file uploads.
- [JSON Web Token (JWT)](https://jwt.io/) – Token-based authentication mechanism.
- [PostgreSQL](https://www.postgresql.org/) – A relational database management system.

### Machine Learning Microservice
- [FastAPI](https://fastapi.tiangolo.com/) – A fast and lightweight Python framework for building APIs.
- [Uvicorn](https://www.uvicorn.org/) – An ASGI server for running FastAPI applications.
- [XGBoost](https://xgboost.readthedocs.io/) – A machine learning algorithm based on gradient boosting.
- [Pandas](https://pandas.pydata.org/) – A library for data manipulation and analysis.
- [NumPy](https://numpy.org/) – A numerical computing library.
- [Joblib](https://joblib.readthedocs.io/) – A library for serializing and loading machine learning models.

# Django, InfluxDB & Grafana Data Platform

This repository presents selected work from a software engineering project involving web development, time-series data storage and data visualisation.

The project combined Django, InfluxDB and Grafana to create a system where users could work with stored data, generate visualisations and interact with dashboards through a web application.

---

## Project Overview

The system was designed as a web-based data platform combining:

- Django for backend development
- InfluxDB for time-series data storage
- Grafana for dashboards and visualisation
- JavaScript for frontend interaction
- REST-style communication between system components

The project required different technologies to work together as one application rather than as separate standalone tools.

---

## My Contribution

My main contributions included:

- Backend development using Python and Django
- Working with InfluxDB for time-series data storage
- Supporting data retrieval and processing
- Integrating Grafana dashboards into the application
- Working with different chart and visualisation types
- Supporting CSV data export
- Debugging application and login-related issues
- Improving integration between backend and frontend components
- Updating documentation and testing project functionality
- Collaborating with team members using Git and GitHub

---

## Technologies

- Python
- Django
- InfluxDB
- Grafana
- JavaScript
- HTML / CSS
- REST APIs
- Git
- GitHub

---

## System Architecture

The project combined several components:

```text
User
  │
  ▼
Django Web Application
  │
  ├── Application Logic
  │
  ├── Data Processing
  │
  └── API / Backend Services
  │
  ▼
InfluxDB
  │
  ▼
Grafana
  │
  ▼
Dashboards and Visualisations
```

Django handled the main application logic, while InfluxDB was used for time-series data storage and Grafana provided interactive visualisations.

---

## Key Features

### Data Storage

The system used InfluxDB to store and retrieve time-series data.

This allowed the application to work efficiently with data containing timestamps and changing values over time.

### Grafana Dashboards

Grafana was used to create dashboards and visualise stored data.

Different visualisation types could be used depending on the dataset and user requirements.

### Web Application

Django provided the backend for the web application and connected the different parts of the system.

The project involved working with backend logic, user interaction and integration between multiple services.

### Data Export

The application supported exporting selected data to CSV files for further analysis or external use.

### Dashboard Integration

Grafana visualisations were integrated into the web application so users could access data and dashboards through a single interface.

---

## Screenshots

### Dashboard

![Grafana Dashboard](screenshots/grafana_dashboard.png)

### Web Application

![Web Application](screenshots/web_application.png)

---

## Challenges

One of the main challenges was integrating several independent technologies into a single working system.

Issues could occur at different layers, including:

- Django backend logic
- Database queries
- Grafana configuration
- Frontend integration
- Authentication and login behaviour

Debugging therefore required understanding how information moved through the entire application rather than looking at only one component.

---

## What I Learned

This project gave me practical experience in:

- Building backend applications using Django
- Working with time-series databases
- Integrating multiple software services
- Creating and working with dashboards
- Debugging full-stack application issues
- Working with APIs and data flows
- Collaborating on a larger software project using Git and GitHub

It also improved my understanding of how backend applications, databases and visualisation platforms work together in a real software system.

---

## Repository Structure

```text
django-influxdb-grafana-project/
│
├── screenshots/
│   ├── grafana_dashboard.png
│   └── web_application.png
│
├── src/
│   └── Selected application source code
│
├── docs/
│   └── Project documentation and architecture
│
├── .gitignore
└── README.md
```

---

## Project Note

This repository is a portfolio version of a university team project.

It contains selected work related to my own contribution. Private configuration files, credentials and material that I am not permitted to share publicly are not included.

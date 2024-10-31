# Jobster API

A backend API built for a job management application using Node.js and Express.js. The frontend of this application is pre-built; this project focuses on implementing backend functionalities like CRUD operations, user role restrictions, API rate limiting, database population, and job application statistics.

## Features

* **CRUD Operations** - Allows users to create, read, update, and delete job listings.
* **Test User Role** - Includes a test user role with restricted CRUD permissions to prevent unauthorized actions.
* **API Rate Limiting** - Limits the number of requests to prevent abuse.
* **Database Population** - Enables easy population of the database with mock data for testing and development.
* **Job Stats and Insights** - Uses MongoDB Aggregation Pipeline to generate monthly job application statistics.

## Tech Stack

* **Node.js** - JavaScript runtime environment
* **Express.js** - Web framework for building REST APIs
* **MongoDB** - NoSQL database for storing job data
* **Mongoose** - MongoDB object modeling for Node.js
* **express-rate-limit** - Middleware to control request rates and limit abuse
* **Moment.js** - Library for date formatting and job statistics
* **Mockaroo** - Tool for generating mock data

## Usage

* **CRUD Operations:** Manage job listings with endpoints for creating, reading, updating, and deleting jobs.
* **Test User Restrictions:** The test user has restricted CRUD capabilities to limit potential misuse.
* **API Rate Limiting:** Limits the number of requests to the API within a 15-minute window to prevent abuse.
* **Aggregation Pipeline for Stats:** Provides insights on monthly applications for analyzing trends over time.

## Sample Data
For testing purposes, you can use Mockaroo to generate mock data in JSON format to populate your database.

# Mochi Restaurant App

## Project Overview
Mochi Restaurant App is a full-featured application designed for restaurant management. This app allows restaurant owners to manage their menus, take orders, track inventory, and more.

## Features
- User Authentication
- Menu Management
- Order Tracking
- Inventory Management
- Responsive Design

## Setup Guide

### Prerequisites
Before setting up the project, ensure you have the following installed:
- Node.js (version X.X.X)
- npm (version X.X.X)
- MongoDB (version X.X.X)

### Installation Steps
1. **Clone the Repository**  
   Clone this repo to your local machine using:
   ```bash
   git clone https://github.com/Arafat23ta/restaurent-app.git
   cd restaurent-app
   ```

2. **Install Dependencies**  
   Run the following command to install all necessary dependencies:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**  
   Create a `.env` file in the root directory and add the following variables:
   ```bash
   DB_URI=mongodb://localhost:27017/mochi
   PORT=3000
   ```

4. **Start the App**  
   To start the application, run:
   ```bash
   npm start
   ```
   The app will be running on `http://localhost:3000`

### Usage
- Register as a new user or log in as an existing user.
- Navigate through the app to manage menus, view orders, and track inventory.

## Project Structure
- `/models` - Contains Mongoose models for database collections
- `/routes` - Includes route handlers for API endpoints
- `/views` - Contains HTML templates for rendering views
- `/public` - Contains static files such as CSS and JS

## Contribution
If you want to contribute to this project, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
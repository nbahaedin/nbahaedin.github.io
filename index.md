---
layout: "default"
title: "CarbonWise: Track Your Carbon Footprint Effortlessly 🌍📊"
description: "Track your carbon footprint with CarbonWise, a web app for logging activities, setting goals, and gaining insights on sustainability. 🌍💻"
---
# CarbonWise: Track Your Carbon Footprint Effortlessly 🌍📊

[![Latest Release](https://img.shields.io/github/v/release/nbahaedin/CarbonWise-Carbon-Tracker)](https://github.com/nbahaedin/CarbonWise-Carbon-Tracker/releases)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
CarbonWise is a comprehensive web application designed to help individuals track, analyze, and reduce their carbon footprint. The app offers intelligent activity logging, goal setting, and community engagement features to promote sustainable living. Users can monitor their daily activities and see how they impact the environment.

## Features
- **Activity Logging**: Log daily activities and track their carbon impact.
- **Goal Setting**: Set personalized goals to reduce your carbon footprint.
- **Community Engagement**: Join a community of like-minded individuals focused on sustainability.
- **Data Visualization**: Use interactive charts to analyze your carbon footprint over time.
- **Responsive Design**: Access the application on any device, whether it's a phone, tablet, or desktop.
- **User Authentication**: Secure sign-up and login through Supabase authentication.

## Technologies Used
- **Next.js**: A React framework for building server-rendered applications.
- **React Hooks**: For managing state and side effects in functional components.
- **TypeScript**: For type safety and better development experience.
- **PostgreSQL**: A robust database for storing user data and activity logs.
- **Tailwind CSS**: A utility-first CSS framework for styling.
- **Shadcn UI**: A component library for building user interfaces.
- **Recharts**: For data visualization through charts.
- **Supabase**: For backend services and authentication.

## Installation
To set up the CarbonWise application locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/nbahaedin/CarbonWise-Carbon-Tracker.git
   cd CarbonWise-Carbon-Tracker
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env.local` file in the root directory and add the following variables:
   ```env
   DATABASE_URL=your_database_url
   SUPABASE_URL=your_supabase_url
   SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Run the Application**
   ```bash
   npm run dev
   ```
   Open your browser and go to `http://localhost:3000`.

## Usage
Once the application is running, you can create an account or log in. Start logging your daily activities, set goals, and engage with the community. Use the dashboard to visualize your carbon footprint and track your progress.

### Logging Activities
To log an activity:
1. Navigate to the "Log Activity" section.
2. Fill in the details of your activity.
3. Click "Submit" to save.

### Setting Goals
To set a goal:
1. Go to the "Goals" section.
2. Enter your target reduction in carbon emissions.
3. Save your goal to track your progress.

### Community Engagement
Join discussions, share tips, and motivate others in the community section. Participate in challenges to further reduce your carbon footprint.

## API Routes
The application exposes several API routes for logging activities and fetching data. Below are some key routes:

- **POST /api/log-activity**: Log a new activity.
- **GET /api/activities**: Fetch all logged activities.
- **GET /api/goals**: Retrieve user goals.
- **POST /api/set-goal**: Set a new goal.

For more detailed API documentation, please refer to the `docs` folder in the repository.

## Contributing
We welcome contributions from the community. If you want to contribute to CarbonWise, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them.
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your forked repository.
   ```bash
   git push origin feature/your-feature-name
   ```
5. Create a pull request.

Please ensure your code adheres to the existing style and includes appropriate tests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, feel free to reach out:

- **GitHub**: [nbahaedin](https://github.com/nbahaedin)
- **Email**: your-email@example.com

Check out the [Releases](https://github.com/nbahaedin/CarbonWise-Carbon-Tracker/releases) section for the latest updates and downloads.
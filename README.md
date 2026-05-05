# colorwar

## Overview

**colorwar** is an interactive scoring and scheduling application for Camp Robin Hood color war, **Green and White**. It provides a comprehensive platform for managing activities, tracking scores between Green and White teams, and displaying real-time results across multiple days of competition.

## app.html - Main Application

### Functionality

The `app.html` file contains a fully-featured single-page application that serves as the central hub for the competition. It includes three main views and multiple scoring modes:

#### 1. **Judge View (Default)**
- Displays a daily timeline/schedule of all activities
- Day picker for navigating between competition days
- Shows scheduled activities organized by time period (Morning, Rest Hour, Afternoon, Evening)
- Click activities to open scoring modals

#### 2. **Meet/All-Camp View**
- Dynamic scoring display for events
- Tracks total scores for Green vs White teams
- Shows event status and real-time point updates
- Accessible from the Judge view

#### 3. **Setup View**
- Add regular activities to the schedule
- Configure activity details (day, time period, group, activity type)
- View and manage the current schedule
- Easily set up the competition framework before it begins

### Scoring Modals

**Regular Activity Scorer**: For activities that accept custom numeric scores from both teams
- Input fields for Green and White team scores
- Displays activity rules
- Submit scores to update standings

**Standard Button Scorer**: Quick scoring for activities with simple win/loss/tie outcomes
- Green wins: 20 points to Green, 0 to White
- White wins: 0 points to Green, 20 to White  
- Tie: 10 points to each team

### Features

- **Real-time Score Tracking**: Global score display in header showing cumulative Green vs White points
- **Responsive Design**: Optimized for both mobile devices and desktop displays
- **Interactive UI**: Smooth animations, modal dialogs, and intuitive navigation
- **View Switching**: Easy toggle between Judge, Meet, and Setup views
- **Mobile-Friendly**: Stacked layouts on mobile, side-by-side on larger screens
- **Custom Styling**: Green and White team theming with custom fonts (Bungee display font, Inter body font)

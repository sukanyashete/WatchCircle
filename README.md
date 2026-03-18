# WatchCircle

WatchCircle is a full-stack social watchlist and group recommendations web application built for CS5610 Project 3. It combines a React frontend with a Node.js + Express backend using ES Modules and MongoDB (native driver) for storage.


# Authors

Kenil Jitendrakumar Patel

Sukanya Sudhir Shete


# Quick Links

Live Hosted Website (Demo): 

Design Document: 

Video Explanation on YouTube: 

How to use the application (Instructions): 

Presentation:


# Class

Course: CS5610 Web Development

Class Link: https://johnguerra.co/classes/webDevelopment_online_spring_2026/

Assignment: Project 3 - Full stack application with Node + Express + Mongo + React (hooks)


# Project Objective

WatchCircle helps users take the friction out of deciding what to watch by:
- Building and managing a personal watchlist across Hollywood, Bollywood, TV shows, and anime
- Filtering and searching by category, platform, and watch status
- Tracking episode progress, ratings, and review notes
- Creating groups to organize recommendations by social circle
- Pushing titles with notes and ratings to the right group of people

# Features

## Personal Watchlist (Sukanya)

- Add titles with name, category, platform, and status (Plan to Watch / Watching / Completed)
- Filter and search by category, status, or platform
- Update status, episode progress, rating, and review note
- Delete titles and view a stats summary with totals, category breakdown, and average rating

## Groups & Recommendations (Kenil)

- Create groups with a name and description to organize social circles
- View, edit, and delete groups
- Add recommendations to a group with title, category, note, and rating
- View all recommendations inside a group and delete outdated ones


# Tech Stack

Backend: Node.js + Express (ES Modules — import/export)

Database: MongoDB native driver (mongodb) — no Mongoose

Frontend: React with Hooks (client-side rendering)

No use of Mongoose, Axios, CORS, or template engines


# Prerequisites

Node.js 18+

npm 9+

MongoDB Atlas or local MongoDB instance


# Installation
```
git clone <this-repo-url>

cd WatchCircle

npm install
```
# Environment Variables
Create .env from .env.example:
```
bashcp .env.example .env
```
Set:
```
MONGODB_URI=your_mongodb_connection_string
PORT=3000
```


# Run Locally
Start production mode:
```
npm start
```
Start development mode:
```
npm run dev
```
Open:
```
http://localhost:3000
```


# Linting and Formatting
```
npm run lint
npm run format
```


# Deployment


# Screenshots


# License
MIT License (LICENSE)

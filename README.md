📘 KADIMA
Smart Campus Navigation and Virtual Tour Application

📌 Overview

KADIMA is a mobile application developed as a thesis project that provides smart campus navigation through shortest-path routing. The system allows users to select a starting location and destination within the campus and computes the most efficient path using graph-based algorithms.

This project demonstrates the practical implementation of routing algorithms in a real-world academic environment using modern mobile development technologies.

🎯 Objectives

The primary objectives of this project are:

To develop a mobile-based campus navigation system

To implement a shortest-path routing algorithm

To visualize navigation paths across multiple floors

To provide an intuitive and user-friendly interface

To demonstrate real-world application of graph theory concepts

🛠 Technologies Used

React Native – Mobile application development

Supabase – Backend database for storing nodes and connections

JavaScript – Core programming language

Dijkstra’s Algorithm – Shortest-path computation

🧠 System Description

KADIMA represents campus locations as nodes in a graph structure. Connections between locations are stored with corresponding distances. When a user selects a starting point and destination:

The system retrieves the relevant nodes and connections.

The shortest path is computed using Dijkstra’s Algorithm.

The optimal route is visualized on the selected building floor layout.

If necessary, floor transitions are handled dynamically.

✨ Features

📍 Select starting and destination locations

🗺 Multi-floor navigation support

🔄 Automatic shortest-path computation

📊 Node and path visualization

📱 Clean and responsive interface

📂 Project Structure
/src
  /screens
  /components
  /navigation
  /data
  /utils


screens – Floor layouts and navigation screens

components – Reusable UI components

navigation – App navigation configuration

data – Location nodes and connections

utils – Pathfinding logic and helper functions

⚙ Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/your-username/kadima.git

2️⃣ Navigate to Project Folder
cd kadima

3️⃣ Install Dependencies
npm install

4️⃣ Start the Development Server
npx expo start

🔐 Privacy & Data

KADIMA does not collect or store personally identifiable information.
The application uses Supabase to manage navigation-related data such as location nodes and path connections.

For more information, refer to the Privacy Policy linked in the repository.

📊 Academic Context

This application was developed as part of a Computer Science undergraduate thesis project. It focuses on applying graph theory and shortest-path algorithms in a practical campus navigation system.


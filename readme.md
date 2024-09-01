

# Description

This project serves as the backend for a YouTube-like platform, providing APIs for managing channels like adding, deleting, updating, subscribers, and subscriptions of a channel.


# Table of Contents

1. [Technologies Used](#technologies-used)
2. [Installation ](#installation)
3. [Features](#features)
4. [Routes](#routes)
5. [Folder Structure](#folder-structure)
6. [Acknowledgement](#acknowledgments)
7. [Project History](#project-history)
8. [Contributors](#contributors)
9. [License](#license)

 #Technologies Used
- Node.js 
- Express.js
- EJS 
- Mongoose 
- MongoDB
- HTML 
- CSS 
- Tailwind CSS 
- JavaScript 

# Installation

1. Clone the repository.
2. Navigate to the folder and run `npm install` to install backend dependencies.
3. Run `node index.js` to start the backend server.

# Features
- Lots of youtube backend api 
- A simple user interface for visualization 
- Free to use any api 

# Routes

| SN | Route | Method | Details |
|----|-------|--------|---------|
| 1  | [/yt/all](https://dharmendra-portfolio-lake.vercel.app/) | GET | Get all channels |
| 2  | [/yt/names](https://dharmendra-portfolio-lake.vercel.app/) | GET | Get all channel names |
| 3  | [/yt/:channelId/subscribers](https://dharmendra-portfolio-lake.vercel.app/)| GET | Get all subscribers of a channel |
| 4  | [/yt/:channelId/subscriptions](https://dharmendra-portfolio-lake.vercel.app/) | GET | Get all subscriptions of a channel |
| 5  | /yt/:channelId/subscribe | POST | Subscribe to a channel |
| 6  | /yt/addChannel | POST | Add a new channel |
| 7  | /channelId/delete | DELETE | Delete a channel |
| 8  | /channelId/update | PUT | Update a channel |

# Folder Structure

<pre>
|-- src
    |-- assets 
    |-- controllers 
    |-- data
    |-- models 
    |-- routes 
    |-- views
    |-- connectionDB.js 
|-- index.js
|-- package.json
|-- package-lock.json
</pre>

# Acknowledgments

- [EJS](https://ejs.co/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Express.js](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- Google



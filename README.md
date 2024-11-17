# T3A2: Full Stack App (Part A)

## MeetMyRoute

### Purpose

This application is designed to connect travelers with others who share similar travel interests or itineraries, whether they are fellow travelers or locals in their desination area. It aims to create a platform where travelers can find companionship, receive local insights, or even arrange meetups to enhance their travel experiences. By faciliating these connections, the app helps travelers feel more secure, get personalised travel tips, and enjoy shared experiences, especially those traveling alone.

### Functionality/Features

* User profiles:
    * Users create a profile where they share personal travel interests and bio information.
    * This profile is visible to others.
    * Users can set their profile status to either "Private", "Traveling", or "Local".

* Shared and private itinerary:
    * Users share upcoming travel plans by entering their destination(s) and travel dates.
    * Users add activities that are not shared publicly.

* Search and filtering:
    * Users can explore the community by searching for travelers with overlapping itineraries.
    * The app will have filters such as destination and date.

* Real-time chat and messaging:
    * A built-in chat feature allows users to connect and discuss plans, ask questions, or arrange meetups.

### Target Audience

The application is designed for all travelers but is particularly beneficial for solo travelers, who may seek companionship, security, or local guidance to enhance their journeys.

### Tech Stack

* Front-end
    * HTML
    * CSS
    * Javascript
    * React

* Back-end
    * Express
    * Node.js
    * Mongoose

* Database
    * MongoDB

* Deployment
    * Netlify - front-end
    * Render - back-end

* Project Management
    * Trello

* Diagramming
    * Draw.io

* Design
    * Figma

* DevOps
    * Visual Studio Code
    * Git
    * GitHub

### Competitor Research

We've identified two primary competitors in the travel companion space and took inpiration from: NomadHer and TripBFF.

* NomadHer
    * Target audience - female travelers.
    * Key features:
        * Community-focused - sharing stories and tips.
        * Social netowrking - connecting with like-minded individuals.
        * Travel buddy matching - finding companions with similar itineraries.

While we appreciated the community of NomadHer, we decided to make our app open to all travelers rather than focusing solely on one demographic. Additionally, although sharing stories and tips publicly is a valuable feature, we decided it was outside the scope of our project.

* TripBFF
    * Target audience - general travelers.
    * Key features:
        * Collaborative tip planning - creating and sharing itineraries.
        * Travel tips and advice - accessing expert insights.
        * Destination discovery - exploring new places.
        * Nearby traveler discovery - connecting with local travelers.
        * Travel tracking - monitoring progress and sharing experiences.
        * AI-powered trip planning - leveraging AI for personalised recommendations.

TripBFF, while it offers many features, one major differentiator is that TripBFF does not allow users to filter by travel dates, which our app will offer as a key advantage. This ability to search and filter by specific dates helps users find matches more precisely, making it easier to connect with others whose itineraries overlap.

In terms of design, both NomadHer and TripBFF feature light, clean interfaces with a dominant colour. We aim to maintain this minimalist approach in our app's design. While blue is a common choice for travel apps, symbolising trust and freedom, we opted for sunset orange to evoke warmth, excitement, and the thrill of exploration, aligning with the core values of our app.

### Dataflow Diagram
![Dataflow Diagram](./docs/dataflow-diagram.png)
<img width="64" height="64" alt="partiesicon6464" src="https://github.com/user-attachments/assets/8a0fbbde-348e-47cf-967e-4bb4da9cd5f3" />

# Parties
## Create and participate in parties.

# MVP Roadmap - Event and Party Management Service

This repository is the starting point for developing a full-fledged event and party management service. The MVP focuses on providing users with the ability to create, manage, and participate in events, parties, and gatherings.

## Table of Contents
- [Overview](#overview)
- [Tech Stack](#tech-stack) 
- [Features](#features)  
- [Roadmap](#roadmap)   (soon)

## Overview

The goal of this MVP is to build a service that allows users to:
- Create events (e.g., parties, gatherings).
- Manage events with details such as date, location, and description.
- Invite friends and participants via Telegram integration.
- Join events and track the upcoming activities.
- Chat with other participants and see the status of the event.
- Receive event tickets with QR codes.

## Tech Stack
The following technologies will be used to build the MVP:

- **Backend**: 
  - **Python** with **FastAPI** (for building the web API).
  - **PostgreSQL** (for database management).
  - **SQLAlchemy** (for ORM).
  - **Pydantic** (for request validation).
  - **Uvicorn** (for serving the FastAPI app).

- **Frontend**: 
  - **HTML/CSS** (with Tailwind CSS for styling).

- **Other**:
  - **Docker**.
  - **Telegram API** (for Telegram integration).

## Features

The MVP will include the following core features:

### 1. **User Registration and Authentication**
   - Create a new user profile.
   - Use a unique `user_id` for identifying users.
   - Integrate with Telegram to import user profile information.

### 2. **Event Management**
   - Create and manage events (e.g., party, gathering).
   - Add details like name, location, time, description, and organizer.
   - Allow users to RSVP for events by clicking "I'm going".

### 3. **Participant Management**
   - Add friends/participants to events.
   - Track the number of participants.
   - View a list of users attending the event.

### 4. **Event Feed**
   - Display a feed of upcoming events based on the user's location.
   - Sort events by time and popularity.

### 5. **Chat Integration**
   - Each event will have its own group chat for discussions.
   - Users can join the chat and interact with other participants.

### 6. **User Rating**
   - Users can get a rating for organizing an event (from participants).
   - Users can receive a rating as participants of events by the system itself (after scanning the QR code of the ticket or confirmation from the organizer that he participated).
   - The rating is visible to all users.
   - Organizers can set a filter for the minimum rating for signing up for a party.
   - Premium features will help you hide your rating(In the future).
     
### 7. **Ticket Generation**
   - Generate a ticket for users upon successful registration for an event.
   - Ticket will contain event details and a unique QR code.



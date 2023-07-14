# Project Plan

Pod Members: **José, Maria C., Thomás**

## Problem Statement and Description

Traveling often means fun and relaxation, but its planning can often get stressful when you have little knowledge of the place and too many options to choose from. Many times travelers have through many websites with recommendations, and curate their own list of places, and plan for each day. Our app tries to solve the pain of users that want travel itineraries given a couple of constraints, such as dietary. We aim to target from families that travel together, to groups of friends, or individuals going on solo trips.

The main purpose of this application is to help travelers to plan itineraries for each day of their trip. The target audience will go to our website and write a form about where they are going, when, what are their main constraints (number of people traveling with them, dietary restrictions). A plan will be generated using OpenAi API, in the format of a list of places divided by days, and time blocks in the day.

## User Roles and Personas

## User Roles

1. Family Traveller
2. Solo Traveler
3. Group of Friends

## User Personas

1. Family Traveller

**PERSONA 1**

Name: Sarah Thompson
Age: 35
Travel Experience: Moderate
Technological Proficiency: Average

Background:
Sarah is a busy working mother of two young children. She loves to travel with her family during holidays to explore new places and create lasting memories. However, planning the itinerary for their trips has always been a daunting task for her. With limited knowledge of the destination and multiple options to consider, she often ends up feeling overwhelmed and stressed. Sarah wishes there was a solution that could simplify the travel planning process and provide her with personalized itineraries based on her family's preferences and constraints.

Goals:
Find a user-friendly app that simplifies the travel planning process.
Generate personalized travel itineraries for her family based on their preferences and constraints.
Save time and reduce stress associated with itinerary planning.

Motivations:
Wants to create enjoyable and memorable experiences for her family.
Desires a hassle-free travel planning experience.
Aims to balance the preferences and needs of each family member while planning the itinerary.

Pain Points:
Limited knowledge about the travel destination and its attractions.
Overwhelmed by the abundance of options available during the planning phase.
Time-consuming process of curating a personalized itinerary manually.

**PERSONA 2**

Name: David Johnson
Age: 38
Travel Experience: Moderate
Technological Proficiency: Average

Background:
David is a dedicated father and a hardworking financial analyst. He enjoys going on family trips with his wife and two young children. As the primary planner for their vacations, David often feels overwhelmed with the task of creating a well-structured itinerary that caters to the preferences of each family member. He is looking for an app that can simplify the travel planning process, provide personalized recommendations, and ensure a smooth and enjoyable trip for his entire family.

Goals:
Discover family-friendly destinations and activities that appeal to both children and adults.
Create a balanced itinerary that includes a mix of educational, recreational, and cultural experiences.
Find accommodations that offer family-friendly amenities and are conveniently located.
Streamline the travel planning process and reduce stress associated with itinerary creation.

Motivations:
Values quality time spent with his family during vacations.
Desires a hassle-free travel planning experience.
Seeks activities and attractions that engage and entertain both children and adults.
Aims to create lasting memories and provide enriching experiences for his family.

Pain Points:
Difficulty in finding suitable activities and attractions for both children and adults.
Overwhelmed by the extensive research required to plan a family itinerary.
Limited knowledge of family-friendly accommodations and services in different destinations.
Challenges in balancing the preferences and needs of each family member.

## User Stories

1. As a parent I want all family members to enjoy the trip so I would want to go somewhere with many different options of food and leisure. I would appreciate it if the website had an option to select a family trip for my family where I can specify the age of my kids for instance and maybe the number of family members that are coming along the trip. I want the whole family (kids, wife/husband, grandparents) to enjoy the trip and have personalized experiences according to their wants and needs.
2. As an elderly I am not too good with technology, so I base my travel plans on books, which are normally outdated. Since I am not too tech savvy, I would appreciate a simple website that gives me direct prompts and quickly generates a list of places for me, with no need for registration or email confirmations.
3. As someone traveling for work, I have limited time to explore the city. Since I don’t know when I will have the opportunity to have some free time, I would like some way to have access to good places in the area of the city I am located at the moment, without having to plan ahead, so I can quickly get to places, as well as the ability to send the finished trip through email if I want to look at it again.
4. As a group of friends planning a trip, we want an app that can suggest activities and attractions suitable for our diverse interests, so that we can create a well-rounded itinerary that satisfies everyone. We want to have plans organized for every single day, so we know what time to wake up and what time we should go to bed.
5. As a solo traveler around the world, I want to be able to have short itineraries for when I hop from city to city, so I can quickly know good places to go and use the most of my time.

## Pages/Screens

![main page (1)](https://github.com/JMT-FTL/site-capstone/assets/81043486/78dd5b42-c27e-4294-932b-29e923b7b110)
![Form Page (2)](https://github.com/JMT-FTL/site-capstone/assets/81043486/6cd8ac7b-4fef-4453-b4c6-04112893646e)
![results page (2)](https://github.com/JMT-FTL/site-capstone/assets/81043486/25cba93e-1c36-4296-aa25-16c5bf034a04)
![Login (1)](https://github.com/JMT-FTL/site-capstone/assets/81043486/e27f3e71-5d37-4c51-b7ec-1b1c7f637554)
![Register (1)](https://github.com/JMT-FTL/site-capstone/assets/81043486/dd326c51-ff97-41be-92d1-c97fd61f9cd6)
![user page (2)](https://github.com/JMT-FTL/site-capstone/assets/81043486/658e2238-f34b-4e37-a25b-4ce668f9c25a)


## Data Model

For now we don't have any tables. A login and registration are stretch features of our project (since they are not necessay for it to work, and are deeply related to the feature of users saving their itineraries).

## Endpoints

| CRUD | HTTP Verb | Description | User Story |
| --- | --- | --- | --- |
| Create | POST | The user inputs a city, number of days of the trip, and its type through a form. The request body is made by the form’s input. The response will be the return of a model that uses the request body to create a prompt to the OpenAI API. The response will be an object with the trip’s itinerary. | 2 |
***Don't forget to set up your Issues, Milestones, and Project Board!***

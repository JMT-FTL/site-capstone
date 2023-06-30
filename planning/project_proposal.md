# Project Proposal

Pod Members: **José Martínez, Maria Carneiro, Thomás Kuhn**

## Problem Statement

Traveling often means fun and relaxation, but its planning can often get stressful when you have little knowledge of the place and too many options to choose from. Many times travelers have through many websites with recommendations, and curate their own list of places, and plan for each day.  Our app tries to solve the pain of users that want travel itineraries given a couple of constraints, such as dietary. We aim to target from families that travel together, to groups of friends, or individuals going on solo trips. 

## Description

The main purpose of this application is to help travelers to plan itineraries for each day of their trip. The target audience will go to our website and write a form about where they are going, when, what are their main constraints (number of people traveling with them, dietary restrictions). A plan will be generated using OpenAi API, in the format of a list of places divided by days, and time blocks in the day. 

## Expected Features List

**Key Features:**
Prompt Form + generate intinerary: where the user wants to go, their diet, what places they want to visit (museums, restaurants, clubs) 
create a list with bullet points for each day and time blocks in the day
Save and share itineraries 
**Extra Features:**
Create a map (Yelp/Google maps API): put pins on the map for every place generated on the list, and create a visual path

## Related Work

- https://www.forgemytrip.com/
We are using categories and we will limit the text input from the users. We are focusing on the user experience: instead of having the user writing a prompt and thinking about every single detail they want to include in their trip, we are going to give them a form with options they can select, such as a multi-select for categories of places they want to visit such as museums, clubs, beaches, restaurants etc. 

## Open Questions

- OpenAi, Google Maps API integration
- How to display things nicely on the frontend?
- Prompt engeneering -> how to get the information from the user and create good prompts to send to OpenAi API
- User experience -> which categories should we display? 

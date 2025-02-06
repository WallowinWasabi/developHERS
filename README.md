# DevelopHERS Website Project

## Project Overview
We are building a website for the DevelopHERS Discord community using a simple tech stack and hosted on Github Pages. The focus is on front-end development with minimal backend complexity, emphasizing collaboration and learning.

## Tech Stack & Hosting
- Hosting: GitHub Pages
- Possible Tech Stack:
- Core: HTML, CSS, JavaScript
  - Additional: Python (for potential backend needs)
  - Libraries & Frameworks: React, Three.js (for interactive visuals)

## Roles Assignment:
- Avril 
- Damaris 
- Nicole 
- Ruby
- Jazmin 
- TEN

## Website Features & Structure
### 1. Homepage
- Navigation Bar – A simple navbar for easy access to Home, Resources, Blog, Projects, Matchmaking, and FAQ.
- Mission Statement – Clearly define the purpose of DevelopHERS
- Introduction Section – Provide an overview of the community, its values, and goals.
- Sign-up Form – Allow visitors to join the Discord server or subscribe to updates.
- Community Spotlight Section: Highlight projects, achievements of members, interviews, or success stories.
  - Could include a mini interactive placeholder image that links to project page?
- Event Calendar: If DevelopHERS hosts coding challenges, study sessions, or talks, a small calendar section could be useful.
	
### 2. Resource Database
- A searchable and categorized collection of learning materials shared in the discord resource channel
- Includes links to useful podcasts, coding tutorials, books, and documentation.
- Members(not the public) can submit resources through a standardized form, and submissions will be reviewed before being added.
  - Not too sure, but might be worth looking into see if there's a way we can auto-pull resources shared in a specific channel to the website? Don't think it exists.
	- Organization method options
		- Language; JS, python, ruby etc
	  - Format; podcast, book, videos, courses, blog
		- Skill Level
		- Categoy; front-end, back-end, full-stack, UI/UX, Data Scient, Cyber Security etc
		- Free vs Paid
		- Platform; youtube, udemy, coursera etc
		- Maybe a voting system for most recommended or popular?
		- Recently Added
		- Certification availability
	
### 3. Blog Section
- Showcase articles written by community members.
- A submission form for members to submit articles for review before publishing.
	- Topics can include coding experiences, tutorials, and industry insights with sorting option similar to resources but maybe include
		- Date
		- Author
		- Popularity
		- Reading Time
		- Featured posts
	
### 4. Project Showcase
- Featured project at the top
- A section where members can display their coding projects.
- Could include filters for different programming languages or project types.
- Members can submit projects through a form, with basic moderation before they go live.
	- Might be worth while to create requirements for submission; role played, completely self completed, just to reduce the potential of plagiarism, etc

### 5. Matchmaking Interactive Map
- A visual tool to help members find coding partners, mentors, or collaborators.
- Functions as a "calling card" where members can list skills they have or are looking for.
	
### 6. FAQ & Getting Started
- A section answering common questions about the community and how to get involved.
- Could include a short guide on contributing to the site, Discord etiquette, and useful links.


# Matchmaking Interactive Map & Member Showcase Breakdown

Digging deeper into the map idea, I thought about taking it a step further! While keeping it a fun, interactive tool designed to help members connect with collaborators, mentors, and mentees in a visually engaging way, we could introduce a front-page map that serves as more of a showcase.

## Homepage Showcase Map (Public & Fun Visual)
- A separate map on the homepage featuring all opt-in members displayed as a bubble image. This would essentially serve as a community showcase, allowing visitors to see the growing network of DevelopHERS members.
- Clicking on an image for those who opt in could potentially showcase:
  - A featured project on the project's page.
  - A blog entry they’ve written.
  - A mini bio or other contributions to the site.
- A fun note on the homepage encourages members to explore, connect, and grow together.

## Interactive Matchmaking Map (Deeper Networking)
Requires a signup to the Discord (for privacy reasons).  
- A more functional, interactive map where members can actively seek out mentorships, collaborations, and learning partners.
- Members fill out a quick form to join, including:
  - Username and image
  - Skills they have
  - Skills they want to learn
  - Mentorship status (looking for a mentor, available to mentor, both)
  - Project interests (web development, open-source, game development, etc.)
  - Location (optional, for potential local networking)
- The system places them on the interactive map as a node, with lines connecting members based on shared skills, mentorship needs, or project interests.
- Users can click on bubbles to see details, send connection requests, or start conversations.
- Two possible viewing modes:
  - Graph network view (default) – Node-based visualization showing connections between members.
  - Directory view – A card-based format for structured browsing and filtering.



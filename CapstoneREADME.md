
# PDX Code Guild: Capstone Proposal

## Name

- ***Git Hook'd***

## Project Overview
- This project is designed to give a user a one stop shop to look up fish (hopefully fish they could catch locally according their zip code), and receive dietary and conservation information on those fish. I am hoping to help people find fisheries information that is helpful to them in picking locally sourced fish and seafood.

**The program will contain:**
- A text area to search for fish by zip code
-	It will return a list of fish endemic to that area
-	Once a fish species is selected, it will show:
-	An image of the fish
- Nutritional information about the fish
-	A taste profile of the fish
-	2 recipes containing fish species
-	The fish’s typical environment and distribution (including best way to fish for it)
-	The conservation status of the fish

## Features
- *“As a pescatarian, and an environmentalist, I want a place I can find locally sourced fish to prepare and their conservation status, because I want to help maintain healthy fish populations, but not give up eating seafood.”*

**Tasks:**
- Have an input for zip code
-	Have a list of local fish species present and be clickable links
-	Upon click, image and information will be displayed of selected fish
-	Display 2 links to top recipes in containing fish species
-	Have a links to Wikipedia and fisheries so people can find more information

## Data Models
- User
  - Username
  - Password
  - Email
  - Zip code
- FishFacts
  - Fish list
  - API for fish description
  - API for fish photo
  - API for 2 recipes
  
## Schedule
**Week 1: Build app**
- [ ] Find API’s to work with, including recipes where I can search by ingredient
- [ ]	Create Django app
- [ ]	Create user interface for username/password
- [ ]	Create fish zip code list

**Week 2: Design home page describing app with login and zip code**
-	[ ] Start working on UI portion of app
-	[ ] Build views for fish description and images
-	[ ] Create a “contact me” page with links to socials

**Week 3: Work on UX/UI interface/build recipe view**
-	[ ] Build the recipe view and interface
-	[ ] Work on aesthetic of site
-	[ ] Design a logo
-	[ ] Build navigation tool 

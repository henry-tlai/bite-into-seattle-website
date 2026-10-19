# Bite Into Seattle

A restaurant review blog with photos and an interactive map of Seattle. Built as a team project for a web development class.

## Purpose

Seattle has a huge and constantly changing restaurant scene, which makes it hard to find local favorites or know whether a place is worth the time and money. Bite Into Seattle helps visitors and locals decide where to eat, with reviews written from the perspective of the average diner and a more personal touch than the typical review site.

## Features

- **Reviews:** a blog-style page with a write-up and photos for each restaurant (12 reviews)
- **Interactive map:** reviewed restaurants are pinned on a map of Seattle. Clicking a pin shows where the restaurant is and links to its review, so users can pick a place in the part of town they want (downtown, Capitol Hill, around UW, and more).
- **Search:** a homepage search box that looks up restaurants by name
- **About us:** introduces the creators so visitors can get to know who is behind the site
- **Contact:** a contact form

## Team plan

The team coordinated weekly through a shared Teams chat and group messages, split tasks to keep the workload even, and brainstormed together. For the first milestone, each member sketched their own wireframe, and the final wireframe combined parts of all of them.

## Tech stack

HTML, CSS, JavaScript, [Plotly.js](https://plotly.com/javascript/) (map), [Fuse.js](https://www.fusejs.io/) (search)

## Run it locally

The map and search load `mapdata.json` with `fetch`, so open the site through a local server rather than double-clicking the HTML files:

```bash
cd Sprint
python3 -m http.server 8000
```

Then go to <http://localhost:8000/HTML/homepage/index.html>.

## Repo layout

```
Sprint/                  The website
  HTML/                  One folder per page (homepage, review, reviewarticles, location, about, contact)
  CSS/                   Stylesheets
  JavaScript/            Page scripts and mapdata.json (restaurant coordinates and links)
  img/                   Shared images
  fonts/                 Custom fonts
ICE/                     Separate in-class exercise (a mock newspaper page)
docs/project-plan.md     Full original project proposal and team plan
```

## Team

Team MAHI, a group of Seattle University Computer Science students:

- **M**oises
- **A**dela
- **H**enry
- **I**vanna

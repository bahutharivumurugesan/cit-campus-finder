# CIT Campus Finder — project starter pack

**Idea:** Chennai Institute of Technology students and visitors can search for a campus place and get a quick direction clue.

## Open the prototype

1. Download or copy this folder to your computer.
2. Double-click `index.html` to open it in Chrome, Edge, or another browser.
3. Search for places, choose a category, or tap a block on the campus illustration.

It is a self-contained demo: no account, installation, internet connection, or live location is needed.

## What is already included

- Search and category filters
- A place detail card with building, floor, landmark, and direction fields
- A clickable illustrative campus overview
- A suggestion form that saves draft corrections in this browser for demo purposes
- Example CIT places and clear prompts where on-campus details need verification
- A student survey, a data collection sheet, a project plan, and a LinkedIn draft

## What to do next

### 1. Validate the problem

Ask 5–10 CIT students, especially first-year students and visitors:

- Which campus place is hardest to find?
- When did you last need help finding it?
- What did you use to find it?
- Would a searchable map with block/floor directions help?

Use `student-survey.md`. Record responses without names unless people agree to share them.

### 2. Verify the campus details

Use `places.csv` as your collection sheet. Ask students or authorized staff to confirm each building, floor, landmark, and route. The included map is only an illustrative layout; it is **not** an official plan and its relative positions are not verified. Replace them with a campus-approved map or a map you create after checking locations on site. Do not publish room-level or restricted hostel details without permission.

### 3. Personalize the prototype

Open `index.html` in a text editor. Find the `const places=[` section near the bottom. Each entry has `name`, `category`, `block`, `floor`, `landmark`, and `route` values. Replace the “Please verify” text only after checking it. The clickable map buttons are in the `<div class="map">` section; keep its visual disclaimer until the positions are confirmed.

### 4. Demo it with students

Give a student three place-finding tasks. Track whether they find the right place, how long it takes, and where they get confused. Fix the confusing labels and directions, then repeat with a few more students.

### 5. Present it as a project

Use `project-outline.md` for your report/demo flow. Be honest about what is a working prototype and what still needs campus verification. Ask your faculty or college administration before calling it an official CIT map or using official logos/branding.

## Suggested project title

**CIT Campus Finder: A Searchable Campus Wayfinding Website**

## Limits of this starter version

This is a front-end prototype with sample content. It does not use GPS, indoor positioning, live routing, user accounts, or an official campus map. Directions and mapped positions need verification before real-world use.

The suggestion form stores entries only in the browser's local storage; it does not send them to the project team. To gather responses from other students, use the included survey or connect a form/database after deciding how submissions will be reviewed.

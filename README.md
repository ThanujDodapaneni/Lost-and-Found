# Campus Lost & Found

A responsive website where students and staff can report lost or found items on campus, search the board, and mark items as returned.

**Minor Project – Full Stack Development**

| | |
|---|---|
| Student | Thanuj D |
| USN | ENG25AD0103 |
| Section | B |
| Department | CSE (Artificial Intelligence & Data Science) |
| College | Dayananda Sagar University |

## Problem

Lost items on campus are reported through chat groups and notice boards. Posts get buried, can't be searched, and are never updated once an item is returned. This project gives the campus one searchable board for lost and found items.

## Features

- Post a lost or found item with name, category, location, date, contact and details
- Form validation with clear error messages
- Live search by item name, location or description
- Filter by type (lost / found) and category
- Mark items as returned, reopen or delete them
- Live counters for lost, found and returned items
- Data saved in the browser (localStorage) between visits
- Responsive layout, light and dark mode, keyboard-friendly

## Tech stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (Grid, Flexbox, CSS variables) |
| Logic | Vanilla JavaScript |
| Storage | Browser localStorage (JSON) |
| Font | Google Fonts (Sora) |

## Run locally

No installation needed. Download or clone the repository and open `index.html` in a browser.

```bash
git clone https://github.com/<your-username>/campus-lost-and-found.git
cd campus-lost-and-found
# then open index.html in your browser
```

## Deploy with GitHub Pages

1. Open the repository on GitHub, then go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose the `main` branch and the `/ (root)` folder, then click **Save**.
4. After a minute, your site is live at `https://<your-username>.github.io/campus-lost-and-found/`.

## Project structure

```
campus-lost-and-found/
├── index.html        # the website (HTML, CSS and JavaScript)
├── README.md
├── docs/
│   └── Campus_Lost_Found_Presentation.pptx
└── screenshots/      # add screenshots of the working site here
```

## Limitations and future scope

This version has no server, so each visitor only sees the items saved in their own browser. Planned improvements:

- Node.js and Express back end with MongoDB or SQLite
- Student login and verification
- Photo upload for items
- Email or SMS alerts on possible matches
- Admin panel for campus security

# GitHub Issues Tracker

<p align="center">
  <img src="./assets/github-logo.png" alt="GitHub Issues Tracker Logo" width="90" />
</p>

## Overview

GitHub Issues Tracker is a responsive web application for viewing and managing GitHub-like issues.  
It includes a login page, issue filtering, search, and a detailed modal view for each issue.

This project is built with HTML, Tailwind CSS, DaisyUI, and vanilla JavaScript.

## Live Demo

- Live Site: [GitHub Issues Tracker](https://github-iussue-tracker-siam7.netlify.app)
- Repository: [Khalid-Sifullah-Siam/Github-Issue_tracker](https://github.com/Khalid-Sifullah-Siam/Github-Issue_tracker)

## Features

- Simple login page with demo credentials
- Dynamic issue loading from API
- Filter issues by `All`, `Open`, and `Closed`
- Search issues by text
- Issue details modal
- Loading spinner while data is being fetched
- Active button highlight for better navigation
- Responsive layout for desktop and mobile
- Clean UI with Tailwind CSS and DaisyUI

## Tech Stack

- HTML5
- Tailwind CSS
- DaisyUI
- Vanilla JavaScript
- Font Awesome
- Google Fonts
- Programming Hero Open API

## API Reference

| Purpose | Endpoint |
| --- | --- |
| Get all issues | `https://phi-lab-server.vercel.app/api/v1/lab/issues` |
| Get single issue details | `https://phi-lab-server.vercel.app/api/v1/lab/issue/{id}` |

## Project Structure

```text
Github-Issue_tracker/
|-- assets/
|   |-- images/
|   `-- github-logo.png
|-- script/
|   |-- index.js
|   `-- main.js
|-- style/
|   `-- main.css
|-- index.html
|-- main.html
|-- GitHub Issues Tracker.fig
`-- README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Khalid-Sifullah-Siam/Github-Issue_tracker.git
```

2. Move into the project folder:

```bash
cd Github-Issue_tracker
```

3. Open `index.html` with Live Server or any static server.

## Demo Credentials

- Username: `admin`
- Password: `admin123`

## How It Works

- The app starts with a login page.
- After successful login, the main issue dashboard opens.
- Issues are loaded from the API and shown as cards.
- Users can filter issues by status.
- Users can search issues using the search box.
- Clicking an issue opens a modal with full details.
- A spinner shows while data is loading.

## Design Resource

- Figma file included in the project: `GitHub Issues Tracker.fig`

## Challenges Faced

- Handling API data and rendering it in the UI
- Keeping search and filter features simple and organized
- Showing issue details in a clean modal
- Making the layout responsive for different screen sizes

## Lessons Learned

- How to use `fetch()` with vanilla JavaScript
- How to manipulate the DOM to show dynamic data
- How to build a simple login flow
- How to create a responsive UI using Tailwind CSS and DaisyUI

## Future Improvements

- Add real authentication
- Add issue creation and editing
- Save favorite issues
- Improve error handling for failed API requests
- Add pagination for large issue lists

## Author

- Khalid Sifullah Siam
- GitHub: [Khalid-Sifullah-Siam](https://github.com/Khalid-Sifullah-Siam)

## License

This project currently does not include a `LICENSE` file.

## Project Photos

Below are the project screenshots from the `assets/images` folder, arranged serially.

**1. Project Photo 1**

<img src="./assets/images/Screenshot (87).png" alt="Project Photo 1" width="800" />

**2. Project Photo 2**

<img src="./assets/images/Screenshot (88).png" alt="Project Photo 2" width="800" />

**3. Project Photo 3**

<img src="./assets/images/Screenshot (89).png" alt="Project Photo 3" width="800" />

**4. Project Photo 4**

<img src="./assets/images/Screenshot (90).png" alt="Project Photo 4" width="800" />

**5. Project Photo 5**

<img src="./assets/images/Screenshot (91).png" alt="Project Photo 5" width="800" />

**6. Project Photo 6**

<img src="./assets/images/Screenshot (92).png" alt="Project Photo 6" width="800" />

**7. Project Photo 7**

<img src="./assets/images/Screenshot (93).png" alt="Project Photo 7" width="800" />

**8. Project Photo 8**

<img src="./assets/images/Screenshot (94).png" alt="Project Photo 8" width="800" />

**9. Project Photo 9**

<img src="./assets/images/Screenshot (95).png" alt="Project Photo 9" width="800" />

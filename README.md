# Waste Management and Sanitation Services

A front-end website for a waste management and sanitation service, designed to provide waste collection information, recycling guidance, pickup request forms, and collection schedule navigation.

## Live Demo

[Visit the Waste Management Website](https://subhransu-git.github.io/waste-management/index.html)

## Overview

The Waste Management and Sanitation Services website is a static web project focused on promoting cleaner communities and responsible waste disposal.

It provides a homepage with information about waste management, recycling tips, navigation menus, a pickup request page, and a collection schedule page with an embedded Google Map.

The project is built using HTML, CSS, and JavaScript.

## Features

### Homepage
- Introduction to waste management and sanitation services
- Navigation between website sections
- Recycling tips and waste segregation guidance
- Contact section
- Environmental branding and images

### Collection Schedule
- Area selection for Patia, Chandrasekharpur, Kalinganagar, and Khandagiri
- Waste type selection
- Address or postal code input
- Embedded Google Map centered on Bhubaneswar, Odisha
- Link to create a Google Calendar event

### Pickup Request
- Form for entering a name and pickup address
- Waste type selection:
  - General waste
  - Recyclable waste
  - Organic waste
  - Hazardous waste
- Pickup date selection
- Optional additional notes
- Request submission interface

### Contact Form
- Name and email fields
- Message field
- EmailJS integration for sending contact form submissions

### Styling and Navigation
- Custom CSS styling
- Dropdown navigation menus
- Environmental color theme
- Responsive layout rules

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and forms |
| CSS3 | Layout, styling, and navigation |
| JavaScript | Client-side interactions |
| EmailJS | Contact form email integration |
| Google Maps Embed | Map display on the schedule page |
| GitHub Pages | Website hosting |

## Project Structure

```text
waste-management/
├── assets/
│   ├── earth1.png
│   ├── article.jpg
│   └── tips.png
├── index.html
├── request.html
├── schedule.html
├── script.js
└── style.css
```

The `assets/` folder contains images used by the website. The HTML files define the individual pages, `style.css` controls their appearance, and `script.js` contains JavaScript functionality.

## Getting Started

### Prerequisites

- A modern web browser
- Git, if you want to clone the repository
- A code editor such as Visual Studio Code (optional)

No Python, Node.js, or backend server is required for basic local viewing.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Subhransu-git/waste-management.git
   ```

2. Open the project directory:

   ```bash
   cd waste-management
   ```

3. Open `index.html` in your browser.

Alternatively, open the folder in Visual Studio Code and use the Live Server extension to preview the website locally.

## Usage

1. Open the homepage to explore the waste management and sanitation information.
2. Use the navigation menu to visit the collection schedule and pickup request pages.
3. Read the recycling tips for guidance on separating recyclable and non-recyclable waste.
4. Explore the schedule page and its embedded map.
5. Use the pickup request form interface to enter collection details.
6. Use the contact form to send a message if the EmailJS integration is configured correctly.

## Important Implementation Notes

This repository is a front-end website. It does not currently document a connected backend or database.

- The contact form uses EmailJS. Successful delivery depends on the EmailJS service and template configuration.
- The pickup request page contains a form and a confirmation message element, but a working backend or persistent request-storage mechanism is not included in the inspected files.
- The schedule page contains area and waste-type selectors, an address search interface, and a Google Maps embed. A complete dynamic collection-schedule lookup should be verified before being described as fully functional.
- The Google Calendar link currently contains a predefined example event.

These features can be extended with backend APIs and persistent data storage in a future version.

## Future Improvements

- Implement functional collection schedule lookup
- Connect pickup requests to a backend or database
- Add request status tracking
- Improve form validation and user feedback
- Make navigation and layouts consistent across mobile devices
- Add real collection dates and area-specific schedules
- Improve accessibility and semantic HTML
- Add screenshots of the website to the README

## Deployment

The website is published through GitHub Pages:

https://subhransu-git.github.io/waste-management/index.html

To publish future updates, commit and push changes to the repository's configured publishing branch and verify the deployment in GitHub Pages settings.

## Author

**Subhransu**

GitHub: [Subhransu-git](https://github.com/Subhransu-git)

## License

No license file is currently listed in the repository. Add a license if you intend to grant others permission to reuse, modify, or distribute this project.

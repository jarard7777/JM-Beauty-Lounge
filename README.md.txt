# JM Beauty Lounge Platform

An elegant, fully responsive multi-page commercial web application built from scratch to showcase modern frontend architecture and serverless API integration.

## Live Demo
Experience the live application here: https://salonwebsite.kesug.com/hair.html

## Technical Highlights & Architecture

* **Serverless Notification Pipeline:** Integrated the third-party **EmailJS API** to implement an asynchronous communication layer. The engine handles dual-routing logic to dispatch background booking data directly to the corporate administrative email while simultaneously triggering custom, dynamic validation alerts back to the client.
* **State Control & Asynchronous JavaScript:** Programmed a lightweight client-side scheduling workflow using vanilla JavaScript to manage interactive modal popups, capture form data fields, and enforce real-time input validation rules.
* **Modern CSS3 Layout Standards:** Developed entirely custom styling configurations using **CSS Grid and Flexbox** layout models to achieve fluid cross-browser compatibility and seamless responsiveness across standard mobile, tablet, and desktop breakpoints.
* **Modular Multi-Page Design:** Structured clean navigation maps across dedicated service domains (Hair, Nails, Makeup) to optimize asset load distribution and enhance user retention.

## Tech Stack
* **Frontend:** HTML5, CSS3 (Advanced Positioning & Grid layouts), JavaScript (ES6+)
* **Integrations:** EmailJS API, FontAwesome Vector Icons
* **Fonts:** Google Fonts (Poppins)

## Repository Structure
* **hair.html** - Core landing and hair services domain view
* **nails.html** - Dedicated nail artistry service layout
* **makeup.html** - Makeup services and gallery page
* **style.css** - Custom CSS Grid and Flexbox structural stylesheets
* **script.js** - Asynchronous client-side state handling and EmailJS API logic
* **README.md** - Project documentation

## Local Setup and Installation
Follow these steps to view and run the project locally on your machine:

1. **Clone the repository:**
   git clone https://github.com/jarard7777/JM-Beauty-Lounge.git

2. **Configure EmailJS (Optional):**
   To make the booking forms active on your local instance, update the API keys inside `script.js` with your own EmailJS credentials.

3. **Launch the Application:**
   Simply open the `hair.html` file in any modern web browser, or use an editor extension like Live Server to launch a local environment.

## Development Methodology
This platform was built following clean frontend development standards, emphasizing modular asset design, clean separation of concerns (HTML/CSS/JS), and optimized performance layouts. Progressive updates were tracked systematically using version control.

## License
This project is open source and available under the MIT License.

## Contact
For any inquiries or technical discussions regarding this frontend implementation, feel free to reach out via your professional channels or open an issue directly in the repository.

# Body Treatments Berlin

Welcome to the repository for **Body Treatments Berlin**, a personal massage website where users can find information about various types of massages, prices, about the therapist, and contact details. This project is currently a work in progress.

## Project Overview

Body Treatments Berlin is designed to provide a seamless and user-friendly experience for clients looking to book massage treatments. The website features:

- Detailed descriptions of different types of massages
- Pricing information
- Information about the therapist
- Contact details

## Features in Development

One of the key features under development is the booking form. This form will slide in from the side of the screen when the user clicks the "Reserve" button. It will guide users through the process of selecting a massage, choosing a location, picking a date and time, entering personal details, and confirming the booking.

## Technologies Used

This project leverages modern web development technologies to create a responsive and interactive user experience:

- **Frontend**: React with TypeScript for building scalable and maintainable components.
- **Styling**: Tailwind CSS for utility-first styling, ensuring a clean and responsive design.
- **Backend**: Node.js and Express for handling server-side logic and APIs.

## Development Approach

I'm using ChatGPT as an AI helper to consciously leverage this powerful tool in the development process. This assists in brainstorming ideas, debugging issues, and speeding up the implementation of complex features.

## Current Status

- **Completed**:
  - Basic project setup
  - Information pages for massages, prices, about me, and contact
  - Slide-in booking form that sends a post request to the server

- **In Progress**:
  - Enhancements to the booking form and date picker
  - Creation of an admin page for viewing all bookings with login functionality
  - Deploying the server side

### Prerequisites

- Node.js and npm installed
- Git installed

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/body-treatments-berlin.git
    cd body-treatments-berlin
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

### Dependencies

This project uses the following dependencies:

```json
"dependencies": {
  "@testing-library/jest-dom": "^5.17.0",
  "@testing-library/react": "^13.4.0",
  "@testing-library/user-event": "^13.5.0",
  "@types/jest": "^27.5.2",
  "@types/react-datepicker": "^6.2.0",
  "axios": "^1.7.2",
  "dayjs": "^1.11.11",
  "dotenv": "^16.4.5",
  "emailjs-com": "^3.2.0",
  "react": "^18.3.1",
  "react-calendar": "^5.0.0",
  "react-datepicker": "^6.9.0",
  "react-dom": "^18.3.1",
  "react-icons": "^5.2.1",
  "react-router-dom": "^6.23.1",
  "react-scripts": "5.0.1",
  "web-vitals": "^2.1.4"
}

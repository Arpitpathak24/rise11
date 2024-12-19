# Jur Dashboard - README

## Overview
This project is a web-based dashboard for managing cases, disputes, and other legal proceedings. It features a user-friendly interface with interactive components to facilitate file uploads, data input, and navigation through various steps of the claim process.

## Project Structure

### HTML
The `index.html` file provides the structure for the dashboard:
- **Sidebar**: Contains navigation links and a branding section.
- **Main Content Area**: Includes the progress tracker and form sections for users to input and upload necessary information.

### CSS
The styling is written directly within the `<style>` tag in the HTML file. It uses CSS to achieve:
- Responsive design with flexbox for adaptable layouts.
- Custom colors, padding, and margins for aesthetic appeal.
- Transitions for interactive hover effects.

### Components
#### Sidebar
- **Logo Section**: Displays the "Jur" logo and branding.
- **Navigation Links**: Links for Dashboard, My Cases, Activities, Calendar, Files, and Open a Dispute.
- **Banner**: Highlights the platform’s purpose with a motivational message.

#### Main Content
- **Progress Tracker**: Visually represents the steps in the claim process with active, completed, and upcoming stages.
- **Form Section**: Users can input details like claim value, place, and language, and upload documents such as statements and agreements.
- **Horizontal Upload Section**: Displays the "Upload the Contract" and "Arbitration Agreement" upload boxes side by side for better organization.

## Features
1. **Responsive Design**: The layout adapts to different screen sizes.
2. **Interactive Progress Tracker**: Indicates the user's current step in the workflow.
3. **File Uploads**: Users can upload PDFs for specific sections like the contract and arbitration agreement.
4. **Customizable Input Fields**: Users can enter claim values and select languages and places for proceedings.

## Potential Enhancements
1. **Backend Integration**:
   - Add a server-side script to handle form submissions and file uploads.
   - Implement database connectivity to store user data.
2. **Dynamic Content Loading**:
   - Use JavaScript to dynamically populate dropdowns for place and language options.
3. **Validation**:
   - Add client-side and server-side validation for file types, sizes, and input fields.
4. **Styling Improvements**:
   - Migrate inline CSS to a separate CSS file for better maintainability.
5. **Accessibility**:
   - Improve accessibility with ARIA roles and labels.

## How to Run
1. Clone the repository.
2. Open the `index.html` file in any modern web browser.
3. Explore the dashboard and test the form features.

## Tools Used
- **HTML5**: For structuring the content.
- **CSS3**: For styling and layout.
- **Browser**: Any modern browser to view the output.

## Folder Structure
```
project-folder/
|-- index.html
|-- assets/
|   |-- images/
|   |   |-- image.png
|   |   |-- rise.png
|-- README.md
```

## Credits
This project is designed to provide an interactive experience for managing legal proceedings, aiming for simplicity and usability.


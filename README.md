# TechCo Solutions - Company Website

A modern, responsive company website built with React.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Smooth scrolling between sections
- **Company Information**: About Us section with mission, vision, and values
- **Services Showcase**: Display of company services and offerings
- **Contact Form**: Email integration for reaching out to the company organizer
- **Modern UI**: Beautiful gradient design with animations

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/shashwat-ucb/poojadidi.git
cd poojadidi
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Available Scripts

### `npm start`

Runs the app in development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.

### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm test`

Launches the test runner in interactive watch mode.

## Contact Form

The contact form allows visitors to reach out to the company organizer. When submitted:
- Opens the user's default email client with pre-filled information
- Validates email addresses before submission
- Provides user feedback on submission status

To customize the recipient email, modify the `mailtoLink` in `src/App.js`:
```javascript
const mailtoLink = `mailto:your-email@example.com?subject=${subject}&body=${body}`;
```

## Customization

### Change Company Name
Update the company name in:
- `src/App.js` (in the navbar logo)
- `public/index.html` (page title and meta description)

### Modify Services
Edit the services section in `src/App.js` to add, remove, or modify services.

### Update Styling
Customize colors and styles in `src/App.css`.

## License

This project is open source and available under the MIT License.

## Contact

For questions or support, please email: contact@company.com

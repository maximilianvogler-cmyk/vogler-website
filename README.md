# Maximilian Vogler - Official Website

Professional website for German tenor Maximilian Vogler.

## Features
- Responsive design
- Event calendar
- Press reviews
- Media gallery
- Contact form

## Updating Events

Edit the `events` array in `src/App.js` (around line 10) to add/remove performances:

\`\`\`javascript
const [events] = useState([
  {
    date: '2026-03-28',
    title: 'Your Event Title',
    location: 'Venue Name, City',
    time: '19:30',
    role: 'Tenor',
    details: 'Performance details...',
    ticketLink: 'https://...'
  }
]);
\`\`\`

## Local Development

\`\`\`bash
npm install
npm start
\`\`\`

## Deployment

Automatically deploys to Netlify on push to main branch.

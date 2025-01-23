MovieX is a mini streaming app where you can watch trailers for the latest movies and shows. Explore genres, search top hits, and enjoy a fast and easy way to preview what’s popular. Perfect for quick browsing, anytime!

Directory Structure
movieX/
├── public/
│   ├── src/
│   │   ├── index.jsx
│   │   ├── movie.jsx
│   │   └── apiService.jsx
│   ├── styles/
│   │   ├── index.css
│   │   └── movie.css
│   ├── index.jsx
│   ├── login.jsx
│   ├── movie.jsx
│   └── signup.jsx
├── .gitignore
├── README.md
└── package.json
Endpoints
  Primary URL https://shimmering-kitsune-443682.netlify.app/
Parameter	Type	Description
api_key	string	Required. Your API key
Search content by ID
  GET /tv/${ID}/videos?language=en-US
  GET /movie/${ID}/videos?language=en-US
Parameter	Type	Description
id	string	Required. Id of item to fetch

Parameter	Type	Description
q	string	Required. query to fetch item
Getting started locally
To get it on your local system, enter the following commands in your terminal:



# move into directory
cd movie

# Add the following environment variables to your .env file
`API_TOKEN` | `API_KEY`

Enjoy, happy coding!
#![Uploading Screenshot 2025-01-22 203941.png…]()


Quick demo ⭮https://shimmering-kitsune-443682.netlify.app/

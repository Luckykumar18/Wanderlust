Here is the live url - https://wanderlust-wsf5.onrender.com/listings
"# WonderLust A-Travel-listing-Website" 

# Wonderlust

A full-stack Node.js project inspired by Airbnb, featuring interactive map integration for property listings. Easily run locally with `node app.js`, manage secrets via `.env`, and deploy seamlessly to Render.

## Features

- **Interactive Map Integration:** View and search listings directly on a map.
- **User Authentication:** Register, log in, and manage your listings.
- **Add/Edit Properties:** Create and update property details with geolocation.
- **.env Support:** Securely manage API keys and environment variables.
- **Ready for Deployment:** Easily deploy to Render with minimal configuration.

## Getting Started

### Prerequisites

- [Node.js & npm](https://nodejs.org/)



### 1. Install Dependencies

```bash
npm install
```

### 2. Create a `.env` File

Create a `.env` file in the root directory. Example:

```env
ATLAS_DB_URL=your__mongoDb ___url

# Cloudinary Configuration
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_key
CLOUD_API_SECRET=your_api_secret_key

# Mapbox Access Token
MAP_TOKEN=pk.eyJ1IjoibHVja3lrciIsImEiOiJjbWEyNXlhYWUyaWFzMnZwc29lbGYycTd1In0.dWsw3VJq3ooy1CN_KMyH-g

# Session Secret
SECRET=your_session_secret

```


### 4. Run the Application Locally

```bash
node app.js
```

The app will be available at `http://localhost:3000` (or your specified port).

## Map Integration

- The map is displayed on the main listings page.
- Listings are shown as markers.
- Clicking a marker shows property details.
- Map provider (e.g. Mapbox) API key is loaded from `.env`.



## Acknowledgments

- Inspired by Airbnb
- Map integration via Google Maps/Mapbox APIs






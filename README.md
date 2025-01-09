# CampHunt 🏕️ 
Discover the perfect campsite and share your adventures with CampHunt!

**CampHunt** is a web application for camping enthusiasts to explore, create, and review campsites around the world. The app allows users to share their favorite camping spots with images, discover new ones, and leave reviews for others.

## Features 

- **Discover Campsites:** Explore campsites globally using an interactive map powered by **Mapbox**.
- **Create Listings:** Share your favorite campsites with photos uploaded via **Cloudinary**.
- **Leave Reviews:** Add reviews and ratings to help others find the best camping spots.
- **User Authentication:** Secure login and registration for personalized experiences.

## How to Run 

1. Clone the repository:
   ```bash
   git clone https://github.com/Karimbraham/CampHunt.git
   cd CampHunt
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file and add your configuration:
   ```env
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   MAPBOX_TOKEN=your_mapbox_token
   DATABASE_URL=your_database_url
   ```

4. Start the server:
   ```bash
   npm start
   ```

5. Open your browser and go to:
   ```
   http://localhost:3000
   ```

## Tech Stack 

- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Media Storage:** Cloudinary
- **Maps:** Mapbox

## Future Improvements 

- Add user profiles and saved campsite lists.
- Implement a booking system for campsites.
- Enhance search filters for location and ratings.
 

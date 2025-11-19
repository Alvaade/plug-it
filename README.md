
# Plug It

Plug It is a full-stack web application developed at Metropolia University of Applied Sciences. The app displays electric vehicle (EV) charging stations across Finland with real-time data and an interactive map.

The project is hosted on Render:
Client: https://web-project-group-6-client.onrender.com/
Server: https://plugit-backend.onrender.com/

---

## Features

- Live station data with Open Charge Map API
- Interactive map with Leaflet
- Secure authentication with JWT-based login and signup as well as Google OAuth integration
- Station reviews and favorite stations
  
---

## Technical Specifications

- **Frontend**: React with Reach Router DOM for navigation
- **Backend**: Node.js with Express.js for REST API implementation
- **Database**: MongoDB
- **Authentication**: JWT, Google OAuth
- **Map**: Leaflet with React-Leaflet
- **Hosting**: Render

---

## Getting Started

Requires:
- Node.js and npm
- MongoDB
- API keys for Open Charge Map and Mapbox
- Google OAuth credentials

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-repo/plug-it.git  
   cd plug-it  
   ```  

2. **Install Dependencies**:  
   Navigate to both the frontend and backend directories and run:  
   ```bash  
   npm install  
   ```  

3. **Set Up Environment Variables**:  
   - Create a `.env` file in both the frontend and backend directories.  
   - Add necessary credentials such as API keys, MongoDB URI, and JWT secret.  

4. **Run the Application**:  
   - Start the backend server:  
     ```bash  
     npm run dev  
     ```  
   - Start the frontend development server:  
     ```bash  
     npm start  
     ```  

---

## Contributors

- **Ade Aiho**
- **Heta Hartzell**
- **Mika Laakkonen**
- **Jonne Roponen**

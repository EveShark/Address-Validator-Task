# Address Validator with Map Integration

# Build a Web Application with a Beautiful Landing Page

## Task Overview
Create a web application with an attractive and user-friendly landing page. The main functionality should allow users to input a source and destination and display the real-time distance between them using open-source mapping tools. The app should include smooth user interactions and provide a seamless experience.

## Requirements
- **Landing Page**: Design a visually appealing landing page that introduces the app and its functionality. Utilize modern UI/UX design principles for a professional appearance.
- **Input Fields**: Create two main input fields for the source and destination locations, using auto-complete features for enhanced user experience.
- **Distance Calculation**: Display the real-time distance between the provided locations using an open-source mapping API such as **Leaflet** or **OpenStreetMap**.
- **Map Integration**: Integrate a dynamic map view showing the path between the source and destination.
- **Responsive Design**: Ensure the application is fully responsive and accessible on both desktop and mobile devices.
- **Error Handling**: Implement robust error handling to manage incorrect inputs or API issues gracefully.

## Additional Enhancements
- **Animations**: Use subtle animations to enhance the input field interactions and map updates for a more engaging experience.
- **Real-time Traffic Data (Optional)**: Integrate real-time traffic conditions using APIs like **OpenRouteService** to show estimated travel times.
- **User Location Detection (Optional)**: Add a feature to detect the user's current location for easier entry of the source point.
- **Custom Markers and Styling**: Customize map markers and route styles for better visual representation.

## Tech Stack Recommendations
- **React**: Core framework for building the application.
- **Leaflet.js**: For map rendering and distance calculation.
- **OpenStreetMap**: As the base map provider.
- **Styled-Components or Tailwind CSS**: For seamless and modern UI styling.
- **Framer Motion**: For interactive animations.
- **TypeScript**: Optional, for type safety and scalability.

## Implementation Steps
### 1. Set Up the Project Environment
- Initialize a new React project:
  ```bash
  npx create-react-app distance-calculator --template typescript
  cd distance-calculator
  ```

- Install necessary dependencies:
  ```bash
  npm install leaflet react-leaflet framer-motion styled-components @types/leaflet
  ```

### 2. Build the Landing Page
- Create a landing page layout with a welcoming design.
- Add input components for the source and destination locations with auto-complete functionality.

### 3. Implement Map and Distance Calculation
- Integrate the **Leaflet** library to display the map.
- Use APIs like **OpenRouteService** or other open-source mapping services for route distance and path display.
- Render the route and show the real-time calculated distance below the map.

### 4. Add Animations and UI Enhancements
- Use **Framer Motion** to animate input interactions and map transitions.
- Design smooth, visually appealing animations for map marker updates and route drawing.

### 5. Ensure Responsiveness
- Optimize the layout and map components for full responsiveness across devices.
- Test on various screen sizes to ensure usability and aesthetic consistency.

### 6. Final Touches and Optional Features
- Implement user location detection for convenience.
- Integrate real-time traffic data to enhance the travel time display.
- Add custom styles for map markers and paths for a unique visual touch.

## Features
- Validate and display Indian postal codes.
- Interactive map showing valid locations.
- Animated feedback for input validation and map markers.

## How to Run
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Add your ApyHub API key in `api.ts`.
4. Run the app with `npm start`.

## Future Extensions
- Integrate user authentication for saved address lists.
- Add more interactive map features.
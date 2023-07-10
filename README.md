# 3D_Product_Designer_Web_App
This is a 3D product design website where users can design clothes using a web-based interface. The website is built using React and Tailwind CSS on the front-end, and Express.js on the back-end.

## Features
*  **Clothes Design**: Users can design clothes by customizing various parameters such as colors, patterns, textures, and styles. The application provides an intuitive and interactive interface for designing clothes in 3D.

* **Real-time Rendering**: The website utilizes the power of Three.js to render the designed clothes in real-time. Users can see their changes and modifications instantly, providing a seamless design experience.

* **Responsive Design**: The website is designed to be responsive, ensuring that users can access and use the application on various devices, including desktops, tablets, and mobile phones.

## Technologies Used
* **React**: The front-end of the application is built using React, a popular JavaScript library for building user interfaces. React allows for efficient component-based development and provides a rich ecosystem of tools and libraries.

* **Tailwind CSS**: The website utilizes Tailwind CSS, a highly customizable CSS framework, for styling the user interface. Tailwind CSS provides utility classes that enable rapid and flexible UI development.

* **Three.js**: Three.js is a powerful JavaScript library used for rendering 3D graphics in the browser. It is employed in this website to visualize the designed clothes in real-time.

* **Express**: The back-end of the application is built using Express, a fast and minimalist web application framework for Node.js. Express handles routing, data storage, and other server-side functionalities.

## Setup Instructions
To get started with the project, follow the instructions below:

1. Clone the repository: Start by cloning this repository to your local machine using the following command:
```
git clone https://github.com/raj007-aii/3D_Product_Designer_Web_App.git
```
2. Navigate to the project directory: 
```
cd 3d-product-design-website/client
```
3. Install dependencies: Navigate to the project directory and install the dependencies for both the front-end and back-end
```
cd 3D_Product_Designer_Web_App/client

# Install front-end dependencies
npm install three @react-three/fiber @react-three/drei maath valtio react-color framer-motion   

cd 3D_Product_Designer_Web_App/server

# Install back-end dependencies
npm install cloudinary cors dotenv express mongoose nodemon openai
```
4. Start the development server: Start the development server for both the front-end and back-end:
* For the front-end, run the following command from the project root directory:
```
npm start
```

* For the back-end, open a new terminal, navigate to the backend directory, and run the following command:
```
npm start
```
5. Open your web browser and visit http://localhost:3000 to access the website.

Note: Make sure you have Node.js and MongoDB (or your preferred database) installed and properly configured before starting the server.

## Project Structure
* **/client/src**: Contains the source code for the front-end React application.
* **/client/src/components**: Contains reusable components used throughout the application.
* **/client/src/pages**: Contains the main page components that define different routes and their functionality.
* **/server/index.js**: The main entry point for the back-end Express server.
* **/routes**: Contains Express route handlers for different API endpoints.

## Contributing
Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request to the repository.

When contributing, please ensure that you follow the established coding style and conventions. Make sure to thoroughly test your changes before submitting a pull request.

## Acknowledgements
* This project was inspired by the growing popularity of 3D product design and the need for an interactive web-based solution.
* We would like to thank the open-source community for their valuable contributions and the developers of React, Tailwind CSS, Express.js, three.js, and other dependencies used in this project.

* **React**: https://reactjs.org/
* **Tailwind CSS**: https://tailwindcss.com/
* **Three.js**: https://threejs.org/
* **Express**: https://expressjs.com/
  

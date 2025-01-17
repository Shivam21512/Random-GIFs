# Random GIFs

Welcome to the Random GIFs project! This web application allows users to generate and display random GIFs based on their preferences. Built with React.js and Tailwind CSS, it leverages the Giphy API to fetch GIFs in real-time.

## Features

- **Random GIF Generation**: Fetches and displays random GIFs from the Giphy API.
- **Search Functionality**: Allows users to search for GIFs based on specific tags or keywords.
- **Responsive Design**: Ensures optimal viewing experience across various devices.

Navigate to the project directory:

bash
Copy
Edit
cd Random-GIFs
Install the dependencies:

bash
Copy
Edit
npm install
Obtain a Giphy API Key:

Visit the Giphy Developers website: https://developers.giphy.com/
Log in or sign up to create an account.
Create a new app to obtain your API key.
Configure the API Key:

Create a .env file in the root directory of the project.

Add your Giphy API key to the .env file:

env
Copy
Edit
REACT_APP_GIPHY_API_KEY=your_api_key_here
Usage
After completing the installation steps:

Start the development server:

bash
Copy
Edit
npm start
Access the application:

Open your web browser and navigate to http://localhost:3000.
Generate Random GIFs:

Click the "Generate" button to fetch and display a random GIF.
Search for Specific GIFs:

Enter a keyword in the search bar and click the "Search" button to display GIFs related to your search term.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch for your feature or bug fix:

bash
Copy
Edit
git checkout -b feature/your-feature-name
Make your changes and commit them with descriptive messages.

Push your changes to your branch on GitHub:

bash
Copy
Edit
git push origin feature/your-feature-name
Create a pull request against the main branch of this repository.

License
This project is licensed under the MIT License. See the LICENSE file for details.


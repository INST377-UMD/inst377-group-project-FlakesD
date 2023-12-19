Star Wars Explorer APi
Description
The Star Wars Explorer is a dedicated web application designed for Star Wars enthusiasts seeking detailed information about their favorite characters. Dive into the Star Wars universe, 
explore character details, and satisfy your curiosity about the galaxy far, far away.

Target Browsers
The Star Wars Explorer is optimized for a seamless experience on desktop browsers, ensuring Star Wars fans can easily access character information.

User Manual
For detailed instructions on how to unleash the power of the Force in exploring Star Wars characters, please refer to the User Manual.

Developer Manual
Audience
This Developer Manual is crafted for Star Wars fans who have technical knowledge about web applications. 
While not delving into system design intricacies, it provides a comprehensive guide for setting up the application, running tests, and understanding the API structure.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/StarWarsCharacterExplorer.git
Navigate to the project directory:

bash
Copy code
cd StarWarsCharacterExplorer
Install the Force (dependencies):

bash
Copy code
npm install
Running the Application
Initiate lightspeed (start the development server):

bash
Copy code
npm start
Open your preferred starship (web browser) and navigate to http://localhost:4000/index.html.

Running Tests
To ensure the integrity of the Force, run tests using the following command:

bash
Copy code
npm test
API
GET /api/characters?name={name}
Retrieve information about a Star Wars character by name.

GET /api/characters/{id}
Get details of a specific character by ID.

GET /api/external-data
Fetch external data from the galaxy for transformation.

Known Bugs and Roadmap
Known Bugs
Characters with special characters in their names may not display correctly.
Height may not be accurate for characters with non-standard units.


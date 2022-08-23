# Express.js Note Taker
  
  ## Description
  
  This app was created to allow users to write and save notes with an Express.js back end that will save and retrieve note data from a JSON file.

  The application will be deployed to Heroku.
  
  ## Table of Contents 
  
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)
  
  ## [Installation](#table-of-contents)
  
  To install the application, download the git repository to your directory of choice and run the application by following the instructions below.
  
  ## [Usage](#table-of-contents)
  
  The application should have a db.json file on the back end that will be used to store and retrieve notes using the fs module.

    The following HTML routes should be created:

    - GET /notes should return the notes.html file.
    - GET * should return the index.html file.

    The following API routes should be created:

    - GET /api/notes should read the db.json file and return all saved notes as JSON.
    - POST /api/notes should receive a new note to save on the request body, add it to the db.json file, and then return the new note to the client. You'll need to find a way to give each note a unique id when it's saved (look into npm packages that could do this for you).
  
  
  ## [License](#table-of-contents)

  License Used: N/A
 
  ## [Contributing](#table-of-contents)
  
  If you'd like to contribute, please follow the [Contributor Covenant](https://www.contributor-covenant.org/).

  Please contribute to the project by adding issues on the links above the repo.

  ## [Tests](#table-of-contents)
  
  TBD
  
  ## [Questions](#table-of-contents)
  
  For additional questions, please reach out to:

  [GitHub: devilarms83](https://github.com/devilarms83)

  [Email: bautista.albert@gmail.com](mailto:bautista.albert@gmail.com)


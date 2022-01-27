## Available Scripts

In the project directory, To build the project run below both commands in different Terminal:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npx json-server --watch data/db.json --port 8000`

Runs the server to watch data/db.json file on port 8000 to request GET, POST, DELETE operations

GET: http://localhost:8000/blogs - Getting all data
GET: http://localhost:8000/blogs/:id - Getting a single data
POST: http://localhost:8000/blogs - Posting a single data
DELETE: http://localhost:8000/blogs/:id - Deleting a single data

Accesibilidad Web
=================

Presentación sobre aspectos básicos de Accesibilidad Web.

## Full setup

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)

1. Clone the Accesiblidad repository
   ```sh
   $ git clone https://github.com/Hyde1942/Accesiblidad.git
   ```

1. Navigate to the Accesiblidad folder
   ```sh
   $ cd Accesiblidad
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port=8001`.

## Folder Structure

- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)

MIT licensed

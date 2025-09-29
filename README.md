# Zdog 3D Animation Starter

A 3D character animation starter template using the Zdog library, featuring Madeline character by Dave DeSandro.

## File Structure

This template contains the files needed to deploy a 3D animated website on Bunetic:

- **`index.html`** - Main HTML file with Zdog 3D animation and interactive canvas
- **`server.js`** - Express server that serves the HTML file and static assets
- **`package.json`** - Defines Express dependency and project configuration
- **`Procfile`** - Tells Bunetic how to start the application (`web: node server.js`)


## Why These Files Are Needed

- **Bunetic requires a server process** - The Zdog library and 3D rendering need proper HTTP serving
- **Express handles static assets** - Serves the HTML and enables the CDN-loaded Zdog library
- **Node.js runtime** - Required for the Express server and proper deployment
- **Procfile defines startup** - Bunetic reads this to launch your 3D animation server


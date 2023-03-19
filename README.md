# openai-image
This is a simple image generator built with Node.js and Express that uses OpenAI's Dall-E models to generate images. 

## Use
After cloning the repo greate a .env file with ""

Generate an API KEY at OpenAI and add it to the .env file.

## Dependencies
npm install

## Run server
npm start

Visit http://localhost:3030 in your browser.

The backend endpoint is at POST http://localhost:3030/openai/generateimage, expecting "size", and "prompt" in the post body. 

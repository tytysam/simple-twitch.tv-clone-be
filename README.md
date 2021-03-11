# Twitch.tv Clone | Backend

React-based application that uses Open Broadcaster Software to supply a video feed, a basic Real Time Message Protocol Server to process the stream, a simple server to track which streams are broadcasting, and a user interface for viewing those streams.

## Setup:

There are two different servers that need deployed in order to get things running. Setup for each is identical and ~straightforward.

1. Clone-down this repository.
2. Inside each server folder, run 'npm install' to install the required dependencies (each server only has 1 dependency).
3. After installing the necessary dependencies, start each server individually from your terminal by running 'npm run start' inside of the respective server's folder.
4. Start-up your Open Broadcaster Software and frontend. When all three are running concurrently, your stream should broadcast directly to the embedded view in the browser.

View the accompanying front-end files / repository <a href="https://github.com/tytysam/simple-twitch.tv-clone-fe" target="_blank" >here</a>.

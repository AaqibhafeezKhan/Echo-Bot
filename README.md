## Echo-Bot

A clean and modern single-page HTML chat client designed for debugging front-end interactions with a mock API.
Features
 * Responsive UI: A sleek, dark theme that adapts to various screen sizes.
 * Chat Interface: Displays messages from both the user and a "bot."
 * Typing Indicator: A visual cue to show when the bot is "responding."
 * API Interaction: Sends user messages to a mock API endpoint (https://jsonplaceholder.typicode.com/posts) and displays the JSON response as the bot's reply.
 * Debug Console: An integrated, collapsible console that logs all API requests and responses for easy debugging.
How It Works
The client uses native JavaScript's fetch API to make a POST request to the mock API endpoint. The mock API echoes the request body back in its response. The sendToMockApi function captures this response and appends it to the chat log, effectively creating an "Echo Bot."
The debug console at the bottom of the page provides real-time insights into the network requests, which is useful for understanding the flow of data and for troubleshooting.
Usage
This project is a single-file application. There is no special setup required.
 * Save the code as a file with an .html extension (e.g., index.html).
 * Open the file directly in any modern web browser.
Once opened, you can type a message into the input field and press "Send." The message will be sent to the mock API, and the bot's reply will appear in the chat log. The debug console will show the details of the request and response.
Technologies Used
 * HTML5: For the document structure.
 * CSS3: For all styling, including the modern, dark aesthetic.
 * JavaScript (ES6+): For handling user input, API requests, and dynamic UI updates.
 * Font Awesome: For the icons.

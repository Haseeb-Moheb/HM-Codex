# Open_AI_Codex

HM-Codex is an AI-based Application that helps us to code more efficiently. 

With an elegant user interface that resembles the ChatGPT app, communication with advanced GPT3 model API, and most importantly, the ability to ask the AI for help regarding JavaScript, React, or any other programming language.

Giving it code and translating it to another programming language, and much more.

This CodeGPT is the best AI-based web application that you can currently find on the market. 
It imports two SVG images, one for the user and one for the bot. It then selects the form and chat container elements from the DOM. It defines a loader function which adds dots to an element every 300 milliseconds, and a typeText function which types out text character by character with a 20-millisecond delay. It also defines a generateUniqueId function which creates an ID based on the current timestamp and random number. Finally, it defines a chatStrip function which creates HTML for each chat message.

The handleSubmit function is called when the form is submitted or when enter is pressed in the form field. It creates HTML for the user's message using the chatStrip function, resets the form, creates HTML for the bot's message using chatStrip, scrolls to the bottom of the chat container, and calls loader on the bot's message element. Then it makes a POST request to an API with data from the form field as JSON in its body. If successful, it clears interval from loader and calls typeText on bot's message element with response data as argument; otherwise, it displays an error message and alerts with error text from response object. Finally, it adds event listeners to form submit and key up events calling handleSubmit when triggered.


![Alt text](<HM-Codex SS.png>)
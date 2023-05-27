## ChatBot App

This is a chatbot application built using Java and the Spring framework. The app allows users to have interactive conversations with a language model powered by the ChatGPT API from OpenAI.

## Prerequisites

- Java Development Kit (JDK) installed of version 19.
- Maven build tool
- OpenAI API key

## Installation

1. Clone the repository to your local machine:
2. Open the project in your preferred Java IDE.
3. Configure the OpenAI API key:
-  Open the application.properties file.
- Replace 'YOUR_API_KEY' with your actual OpenAI API key.
- You can also replace the port number with the one of your requirement.

## How to get it running

- Clone this GIT project.
- Make sure it is a Maven project and Maven is executed to load dependencies.
- Create an Account at https://openai.com & log in
- Create API key at https://beta.openai.com/account/api-keys
- Store the key in application.properties file in cloned project.
- Start it as Spring Boot application.
- For chatting with ChatBot: http://localhost:8084/.
- Enter your message in the input box and press Enter to send it to the chatbot.
- The chatbot will process the message using the ChatGPT API and provide a response, which will be displayed in the chat area.
- Continue the conversation by entering more messages.

## Customization

You can customize the app and extend its functionality according to your requirements:

- Implement additional features and commands.
- Enhance the user interface with additional components.
- Add error handling and input validation.
- Improve the natural language processing capabilities.

Feel free to modify the codebase and experiment with different approaches to suit your needs.

## Limitations

- The app requires an active internet connection to communicate with the ChatGPT API.
- The accuracy and quality of the chatbot's responses depend on the performance of the language model and the training data used.

## Troubleshooting

If you encounter any issues or have questions, please open an issue on the GitHub repository. I'll be happy to assist you.

## More information

- OpenAI API documentation: https://beta.openai.com/docs/api-reference/completions/create

## Acknowledgments

- This app was developed using the ChatGPT API provided by OpenAI.
- Thanks to the creators and contributors of the Java, Spring, and Maven communities for their valuable resources and libraries.

## Disclaimer

Please note that the use of the ChatGPT API is subject to the terms and conditions set by OpenAI. Make sure to review and comply with their guidelines to avoid any misuse or violations.

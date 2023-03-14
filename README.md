# chatbot_demo

This is a simple AI chatbot React Native project that uses the OpenAI API to generate responses to user inputs. Users can type messages into the chatbot and receive responses generated by the AI.

# Installation
To install the project, clone the repository and navigate to the project directory. Then, run the following command to install the project dependencies:
```
npm install
```
# Usage
To use the project, start the development server by running the following command:
```
npm start
```
This will start the Metro bundler, which you can use to build and run the project in the iOS or Android simulator.

The Main component contains the main functionality of the app. It uses the useState hook to manage the input and output text, and the TextInput and TouchableOpacity components to allow the user to input text and trigger a response from the AI. The openai object is created using the Configuration and OpenAIApi classes from the openai package, and is used to generate responses to user inputs.
# Configuration
To use the OpenAI API, you must have an API key. You can get an API key by signing up for an account on the OpenAI website. Once you have an API key, you can set it as an environment variable by adding the following line to your .env file:
```
OPENAI_API_KEY=<your api key>
```
Be sure to replace <your api key> with your actual API key.
## License
This project is licensed under the MIT License. See the LICENSE file for more information.

# agri-bot
This is a LLM model, where it is tuned to help the farmers for clarifying their doubts about organic farming, with personalised suggestions.

Live : https://nalinrajendran-agri-bot-ui2-cci0mq.streamlit.app/



![Blank diagram](https://user-images.githubusercontent.com/51052614/235840501-b35ab015-9940-4dc4-9742-c0e6c4b3d595.jpeg)




ECO-AGRI BOT

NALIN MR – CB.EN.U4AIE20041
RAHUL KRISHNA A – CB.EN.U4ECE20047




Introduction
This project is designed to provide personalized suggestions for organic farming to farmers based on their field of interest. The model is trained on open-source data from the Tamil Nadu Agricultural University and can search online resources to provide the best results and suggestions. The app is built using several Python libraries such as Streamlit, Langchain, and Cohere.

Installation
To use this project, you will need to have Python 3.x installed on your machine. Once you have Python installed, you can use the following command to install the required libraries:

pip install streamlit streamlit_chat langchain cohere 


Usage

The app is also deployed on the web and can be accessed using the following URL:

https://nalinrajendran-agri-bot-ui2-cci0mq.streamlit.app/


Once the app is loaded, the farmer can input their field of interest. The model will then search for information related to organic farming in that field and provide personalized suggestions based on the factors.The app uses several modules from the Langchain library to split the text into characters, vectorize the text, and search through online resources. The Cohere library is used to generate the embeddings and prompts for the model. The Streamlit library is used to build the user interface for the app.

Data Source
The data used for this project is sourced from the Tamil Nadu Agricultural University, which provides open-source data related to agriculture in Tamil Nadu. The data includes information on crop cultivation, pest control, and other relevant topics.



Model Description

The model used in this project is called RetrievalQA, which is designed to provide personalized suggestions on organic farming based on a farmer's field of interest. This model is built using several powerful Python libraries such as Langchain and Cohere.
The text splitter used in the model is called CharacterTextSplitter, which splits the text into small chunks of size 300 with an overlap of 10. This allows the model to search through the text more efficiently and provide more accurate recommendations.
The language model used in RetrievalQA is Cohere, which is a large language model that is specifically designed for natural language processing tasks. It is trained on a large corpus of text and can understand the context and meaning behind the text.
The Cohere model used in this project is the "command-xlarge-nightly" model, which has a high level of accuracy and can generate high-quality recommendations. The temperature parameter is set to 0.95, which allows the model to generate more diverse and creative responses.
To use the Cohere model, an API key is required, which is stored securely using the Streamlit secrets functionality. This ensures that the API key is not visible to the user and is kept secure.
Overall, the RetrievalQA model is a powerful tool that can provide personalized recommendations on organic farming to farmers. It uses state-of-the-art natural language processing techniques and can provide accurate and useful suggestions.

 


Usage and Advantages of Prompt/Prompts

Prompt/Prompts are an essential part of this project as they allow us to generate accurate and relevant responses to the farmer's questions. The usage of PromptTemplate and Cohere provides several advantages, including:
1.	Personalized Responses: The use of prompts allows us to generate responses that are personalized to the farmer's field of interest and location. This ensures that the recommendations are relevant and useful for the farmer, making it easier for them to implement eco-friendly farming methods and maximize their profits.
2.	Natural and Conversational: The use of prompts allows us to provide a more natural and conversational experience for the user. This makes it easier for farmers to engage with the chatbot and get the information they need.
3.	Easy to Implement: The use of PromptTemplate and Cohere makes it easy to implement prompts in the chatbot. PromptTemplate allows us to generate prompts quickly and easily, while Cohere generates responses based on the prompts, making it easier to provide personalized recommendations to the farmer.
4.	Accuracy: The use of prompts allows us to generate more accurate and relevant responses to the farmer's questions. By using PromptTemplate and Cohere, we can ensure that the responses are tailored to the farmer's field of interest and location, providing them with the best possible recommendations.
In summary, the usage of prompts provides several advantages, including personalized responses, a natural and conversational experience, easy implementation, and increased accuracy. These advantages make it easier for farmers to engage with the chatbot and get the information they need to implement eco-friendly farming methods and maximize their profits.


Future Extensions
This project has the potential for future extensions that can enhance the user experience and make the app more accessible to a wider audience. Some possible extensions are:
1.	Speech input: Adding speech input can make it easier for farmers who are not comfortable typing on a keyboard. This extension can be achieved using libraries like SpeechRecognition and PyAudio.
2.	Multi-lingual support: The app can be extended to support multiple languages, making it accessible to farmers who speak different languages. This can be achieved using language translation APIs like Google Translate or by training the model on multilingual data.
3.	Image recognition: Adding image recognition can make it easier for farmers to identify pests and diseases in their crops. This extension can be achieved using libraries like OpenCV and TensorFlow.
4.	Soil analysis: Adding soil analysis can help farmers understand the nutrient composition of their soil and provide recommendations on fertilizers and other treatments. This extension can be achieved using soil testing kits or by partnering with soil testing labs.
5.	Weather forecasting: Adding weather forecasting can help farmers plan their crop cultivation and irrigation activities. This extension can be achieved using weather APIs like OpenWeatherMap or by training the model on weather data.


Conclusion
These future extensions can enhance the functionality of the app and provide more value to farmers. By adding speech input and multi-lingual support, the app can become more accessible to a wider audience. Adding image recognition, soil analysis, and weather forecasting can provide farmers with more comprehensive recommendations and help them make informed decisions. With continuous development and improvements, this app has the potential to become a valuable resource for farmers around the world.


REPO LINK:

https://github.com/nalinrajendran/eco-agri-bot




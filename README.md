## **Overview**
<p>&nbsp;</p>
This Gen AI project aims to utilize machine learning for healthcare by developing a web application that can detect various diseases such as asthma, cancer, diabetes, and stroke. The application provides real-time diagnosis based on predictive modeling. If a disease is detected, the user receives preventive measures and can engage in further conversation with an LLM chatbot specialized in that disease.


## **Features**

- **Real-time disease detection using machine learning**: Instantly analyzes user-provided data to identify potential diseases.
- **Personalized preventive measures for detected diseases**: Offers tailored guidance based on the diagnosed condition.
- **Interactive LLM chatbot for further consultation**: A specialized chatbot provides more information and answers user queries related to the detected diseases.
- **User authentication with sign-up and sign-in functionality**: Secure access for personalized user interactions.
- **Easy-to-use interface with intuitive navigation**: Ensures a smooth user experience with clear and straightforward navigation.

## **Step-by-Step Process**

1. **User Registration**: User signs up or logs in to the platform.
2. **Access Diagnosis Page**: On the home page, the user navigates to the diagnosis page.
3. **Form Filling**: The user fills out a form providing necessary information.
4. **Disease Prediction**: Based on the input, the application predicts whether the user has any of the specified diseases.
5. **Preventive Measures**: If a disease is detected, personalized preventive measures are provided to the user.
6. **Chatbot Interaction**: The user can engage in further conversation with a disease-specific LLM chatbot on the chat page.

---
## **Unique Idea Brief**

We have worked on both aspects of the problem statement: Disease Diagnosis and Treatment Recommendation.

- **Disease Diagnosis**: Involves identifying the disease based on information provided by the user through form-filling. A machine learning model specific to each disease is used for accurate diagnosis.
- **Recommendation Process**: Generates a detailed report that includes causes, symptoms, medical prescriptions, and suggested lifestyle changes.
- Additionally, there is an **LLM-based chat-doctor**, fine-tuned on a specific dataset (link mentioned below), which provides guidance on general medical-related questions.

### Kaggle Datasets:
- [Diabetes Dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)
- [Asthma Dataset](https://www.kaggle.com/datasets/deepayanthakur/asthma-disease-prediction)
- [Stroke Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- [Cancer Dataset](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer)

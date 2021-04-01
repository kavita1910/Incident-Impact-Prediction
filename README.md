# Incident-Impact-Prediction
# Incident-Impact-Prediction
### Project Summary 
#### Requirement 
An organisation operating in IT-enabled business segment receives IT incidents/tickets, which are handled to best practice by ITIL framework with incident management, problem management, change management and configuration management processes. This management is looking for ways to improve the incident management process.  Machine learning looks prospective to improve ITSM processes through prediction and automation.
They came up with a key area, where Machine Learning can help ITSM processes :
1. Predicting High Priority Tickets: To predict priority 1 & 2 tickets, so that they can take preventive measures or fix the problem before it surfaces.
#### Analysis
1. The data is ordinal, nominal as well as categorical. 
2. To analyze the data, various data processing techniques like Label Encoding and Standardization is used.
3. To select the best features from the dataset Feature Selection is done using Extra Tree Classifier, Mutual Information Classifier and Decision Tree Classifier.
![Capture1](https://user-images.githubusercontent.com/66661758/113299158-33a7cd80-931a-11eb-8145-757db8ab0df5.PNG)
4. As this is a Classification problem for training the data and predicting the target, algorithms used are:
![Capture](https://user-images.githubusercontent.com/66661758/113298504-8c2a9b00-9319-11eb-85fa-5b455a9bb255.PNG)
5. Exporting the model with highest accuracy.
6. Deployment of this project is done using Flask

# chatbot-ml-SIH-2019
A Customer Support Chatbot using Machine Learning for Screen Magic

Problem Definition / Idea:

Develop a chatbot for customer support using Python. The chatbot will interact with
users in natural language to provide assistance, answer common questions, and resolve
issues related to a specific domain or product.
Key Features:
● Natural Language Understanding: Implement natural language processing (NLP)
techniques to understand user queries and intents accurately.

● Dialog Management: Design dialog flows to handle conversations between the
user and the chatbot, ensuring smooth interactions and context retention.
● Knowledge Base Integration: Integrate a knowledge base or database containing
FAQs, troubleshooting guides, and relevant information to provide accurate
responses to user queries.
● Multichannel Support: Enable the chatbot to communicate with users across
multiple channels such as website chat, messaging apps (e.g., Facebook
Messenger, Slack), and email.
● Personalization: Implement personalized responses based on user data and
preferences, if available.
● Error Handling: Handle errors gracefully and provide helpful suggestions or
alternative solutions when the chatbot cannot understand or address a user
query.
● Analytics and Reporting: Incorporate analytics to track user interactions, analyze
trends, and generate reports to improve the chatbot's performance over time.
● Integration with Customer Support Systems: Integrate the chatbot with existing
customer support systems (e.g., ticketing systems, CRM platforms) to escalate
issues and capture user feedback seamlessly.
● Continuous Improvement: Implement mechanisms for continuous learning and
improvement, such as user feedback collection, sentiment analysis, and model
retraining.




Technology Stack:

1. Dialogflow(NLP training and Webhook):

	Dialogflow which is powered by Google was used to create intents and entities with respect to the domain that was selected i.e.
  Mutual Funds. 

Based on the intents the Chatbot was trained, Small Talk is a feature offered by Dialogflow was also incorporated into the Chatbot. 

2.  Python ( Sentimental Analysis and Sentence similarity )

	To work on the default fallback intent we used python modules such as vaderSentiment to do Sentimental analysis so as to verify
  whether the query is a Feedback or a Complaint. Part of speech tagging was also done using NLTK.corpus module.

3. Flask(API and REST API)

      Representational State transfer (REST)  API was used as a web API and was implemented using flask microframework.

4. SQLAlchemy(Data Base)

      The identified query which is fallback content is updated in the database to provide its solution when asked the next time

5. Ngrok(local web server)

Secure web tunnel was created to handle the requests along with public URL. It listens on the same port that your local web server is running on.

This URL was used to connect to Dialogflow API using webhook feature.


Integrations:

Whatsapp using Twilio

Skype

Telegram

Google Assistant
# Chatbot-Development-for-Customer-Support
# Customer-Support-Chat-bot-using-Python

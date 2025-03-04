# AI-CHATBOT-WITH-NLP

 *COMPANY*: CODETECH IT SOLUTIONS PVT.LTD
 
 *NAME*: PERUMALLA LAKSHMI PRASANNA
 
 *INTERN ID*: CT08PRF
 
 *DOMAIN*: Python programming
 
 *DURATION*: 4 Weeks
 
 *MENTOR*: Neela Santosh Kumar

    ### **Review and Commentary on the IISc Bangalore Chatbot Code**

This chatbot is a rule-based chatbot developed using the Natural Language Toolkit (NLTK) in Python. It is designed to provide basic information about the Indian Institute of Science (IISc) Bangalore. The chatbot interacts with users by recognizing specific input patterns and responding with predefined answers. It follows a structured approach, ensuring a smooth conversation flow.

### **Functionality of the Chatbot**
The chatbot is built using three main components: importing necessary libraries, defining chatbot responses, and creating an interaction loop.

1. **Importing Libraries:**  
   The code makes use of NLTK’s chatbot module, which provides an easy way to implement rule-based chatbots. The `Chat` module is used for pairing user inputs with predefined responses, and `reflections` helps in mapping pronouns, though it is not utilized in this case.

2. **Defining Chatbot Responses:**  
   The chatbot relies on a collection of predefined patterns and responses. These are structured as regular expressions, allowing the chatbot to identify specific keywords or phrases in the user’s input. Some of the questions it can answer include:
   - What is IISc Bangalore?
   - Who founded IISc?
   - What courses does IISc offer?
   - How can I get admission to IISc?
   - Where is IISc located?
   - How to contact IISc?

   The chatbot also handles basic greetings such as “hi” and “hello,” as well as exit commands like “bye” and “exit.” When a user types any of these, the chatbot responds accordingly.

3. **Creating the Chatbot and Running the Conversation Loop:**  
   Once the predefined responses are set, the chatbot is initialized. It continuously listens for user input, processes it, and returns a response based on the closest matching pattern. If the user types “bye” or “exit,” the chatbot ends the conversation gracefully.

### **Strengths of the Chatbot**
✅ **Simple and Easy to Use:** The chatbot is based on rule-based logic, making it straightforward to implement and maintain.  
✅ **Efficient Query Matching:** By using regular expressions, the chatbot quickly identifies predefined queries and responds accurately.  
✅ **Handles Common User Queries:** It provides relevant information about IISc Bangalore, making it useful for students or researchers seeking details.  
✅ **Graceful Exit Mechanism:** The chatbot recognizes when a user wants to end the conversation and responds appropriately.  

### **Limitations and Areas for Improvement**
❌ **Limited Understanding of User Input:**  
   - Since the chatbot relies on exact phrase matching, it struggles with variations of the same question.  
   - If a user asks a question in a different wording than what is predefined, the chatbot may not recognize it.  
   - A potential solution is to incorporate Natural Language Processing (NLP) techniques like word embeddings to better understand user intent.  

❌ **Lack of Dynamic Conversation:**  
   - The chatbot does not track previous interactions, meaning it cannot engage in contextual conversations.  
   - It answers questions independently without retaining memory of past interactions.  
   - Implementing a memory-based system can help improve engagement.  

❌ **No Handling of Misspellings or Variations:**  
   - The chatbot only matches predefined phrases, so it will not understand inputs with typos or slight variations.  
   - Using NLP-based spell correction methods (e.g., `TextBlob` or `SymSpell`) could improve accuracy.  

❌ **Static Responses:**  
   - Each query has a fixed response, making conversations predictable.  
   - Adding multiple response variations and randomization would make the chatbot feel more human-like.
       
Support & Learning: Throughout the project, I leveraged ChatGPT for assistance in debugging errors, and improving visualization techniques. It provided solutions to common issues and helped refine the workflow.

### **Conclusion**
This chatbot is a **basic rule-based system** that efficiently provides information about **IISc Bangalore**. It successfully handles **simple queries** and includes error handling for conversation termination. However, it lacks **learning capabilities, flexibility, and response variation**. By incorporating **natural language processing (NLP) techniques, machine learning, or AI-driven models**, this chatbot can be **significantly improved** to provide a more **interactive and intelligent user experience**.  

*Output*

![Image](https://github.com/user-attachments/assets/9d41fd6e-bb2a-438e-b0d4-e5df99b5006c)



# **Basic Conversation**
IBM Watson® Conversation is a question-and-answer system that provides a dialog interaction between the conversation system and users. This style of interaction is commonly called a chatbot.

![](https://github.com/NailahTayyar/WatsonConversation/blob/master/views/1.png)


# **Building the Conversation**

**Requirements:**

IBM Cloud account https://ibm.biz/BdZYZx

**1-  Create an instance of Watson Conversation on IBM Cloud**
Make sure that you are logged in to your IBM Cloud account. Click **Catalog** and then click **Services > Watson > Conversation> choose a name> hit Create**

**2-Click Launch tool to open the Watson Conversation workspace**

**3-Create a Workspace.**

**4-Add intents.**

An intent is a group of examples of things that a user might say to communicate a specific goal or idea. To identify intents, start with something that a user might want and then list the ways that the user might describe it.

![](https://github.com/NailahTayyar/WatsonConversation/blob/master/views/2.png)

For each intent, add examples to train the conversation for intent recognition.

![](https://github.com/NailahTayyar/WatsonConversation/blob/master/views/3.png)

**5-Test your intent.**
As soon as you create an intent, you can test it by clicking Ask Watson icon in the top, right-hand side of the conversation editor.
![](https://github.com/nailahDev/Watson-chatbot/blob/master/Basic-Conversation-master/views/Chatbot-tutorial-pictures/3.1.PNG)

**6-Create Your Entity**
entity is a portion of the user's input that you can use to provide a different response to a particular intent.
Click Entities. On the Entities page, click Create new.

Each entity definition includes a set of specific entity values that can be used to trigger different responses. Each value can have multiple synonyms that define different ways that the same value can be specified in user input.

![](https://github.com/NailahTayyar/WatsonConversation/blob/master/views/4.png)

![](https://github.com/NailahTayyar/WatsonConversation/blob/master/views/5.png)


Create entities to represent to the application what the user wants to access.     
Fuzzy logic is a feature that allows Watson Conversation to accept misspelled words. You can enable this feature at the entity level.

**7-Building the Dialog**
A dialog is made up of nodes that define steps in the conversation.

![](https://github.com/NailahTayyar/WatsonConversation/blob/master/views/6.png)




## Web Application Template for Watson Conversation API Demonstration

**Requirements:**
1. Install Nodejs http://blog.teamtreehouse.com/install-node-js-npm-windows

**Main steps:**
1. **"Clone or Download"**  this Repository
2. Take note of Watson Conversation Service's **Credentials** and **workspace_id**
3. Edit the file **app.js** and fill the fields: *username*, *<password>* and *<workspace_id>* with the data collected in the last step.
```css
var conversation = watson.conversation({
  username:"<username>",//replace with the username from service credential
  password:"<password>",//replace with the password from service credential
  version: 'v1',
  version_date: '2016-07-11'
});
```
4. Get the workspace ID
[workspace!]()

```css
     var workspace = "<workspace_id>"; //replace with the workspace_id from service credential

```


5.Open a terminal and Change the directory where you saved your code
write the command

```css
cd C:\Users\Desktop\...;

```




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
node app.js 

```

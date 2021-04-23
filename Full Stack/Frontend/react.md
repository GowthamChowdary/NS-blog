# Step 1:
Click on the dropdown menu and select the boiler plate code, then click on clone.
Newton school will ask for access to your github account, click on authorize. You only have to give access for once and you wont have to do it for all assignments. 
Once you click authorize, Newton school will automatically clone the boilerplate code into your github, and show the link to the project in blue colour.
# Step 2:
Go to the cloned repository in your github, and make the changes. 
I'll show an example for only the first assignment
# Question: Render Component using React
```
Render the react component inside a div with id="root"
Render the following text in p tags- "I am learning React. My life is getting better. 
```
They asked us to only render a p tag , so i went into the cloned repository, then into src, then into components and added a p tag in the app.js like this:

```
import React, {Component, useState} from "react";
import '../styles/App.css';

const App = () => {
  return (
    <p>I am learning React. My life is getting better. </p>
  )
}
export default App;
```
and then commited the code. 
# Step 3:
Once you've commited the code, now you have to copy the link of the repository for that particular assignment and paste it in the "Hosted project link" box and then run all testcases.

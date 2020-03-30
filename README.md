## Dice Roller  
---
### About  
It is a mobile application made with React Native to simulate throwing of two dice.  
I have used `expo-cli` to develop this project.
Images are saved in assets folder and named according to the numbers - "1.png", "2.png" and so on.  
Two random numbers are generated in (1,6) using `Math.floor() ` and `Math.random()` functions of Javascript.   
code:   
```javascript
getRandomValue = () =>
{
    return ( Math.floor(Math.random() * 6) + 1 )
}
```   
##### Requirements:  
* [Node.js](https://nodejs.org/en/)
* [Expo CLI](https://docs.expo.io/versions/latest/workflow/expo-cli/)  
* Any Text editor, I have used [VS Code](https://code.visualstudio.com/)  
---
### Working  
* __Step 1__ - When the button is clicked, generate 2 random numbers between 1 to 6 (both inclusive).   
* __Step 2__ - Select the image of the dice from the assets matching it's name to the two numbers.
* __Step 3__ - Replace the existing images with the newly selected images.  
---

### Installation  
1. Clone the repository and navigate into the folder.
   ```bash
   $ git clone https://github.com/rishabhsxn/User_API.git   
   ```         
2. Install the dependencies using npm.     
    ```bash
   $ npm install   
    ```  
3. To run the application on expo, execute the command   
    ```bash
   $ npm start   
    ```   
---

### Demo  
![DiceRoller Demo](https://media.giphy.com/media/hvMdgKu8xMYtJqlBr4/giphy.gif)
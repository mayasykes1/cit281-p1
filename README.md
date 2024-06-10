# CIT281 Project 1

### Learning Objectives:
<li>Gain experience accessing your operating system's command line interface (CLI)</li>
<li>Gain experience working with CLI commands</li>
<li>Gain experience working with Visual Studio Code (VSCode)</li>
<li>Gain experience writing and executing non-web server Node.js JavaScript code</li>

### Project Overview:
<li>Use the command line interface (CLI) of your operating system to create a number of folders</li>
<li>List the folders in a tree-like structure</li>
<li>Use the ping command, and practice using the break keyboard sequence</li>
<li>Create and execute a JavaScript files using Node.js and Visual Studio Code (VSCode) terminal and Run and Debug</li>

### Code:
#### p1-date.js 
<code>function dayOfTheWeek() {
    const weekDays = ["Sunday","Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
    const day = new Date();
    const currentDay = day.getDay();
    console.log(weekDays[currentDay]);
}
console.log('Today is: ');
console.log(dayOfTheWeek());</code>

#### p1-random.js
<code>function getRandomInteger(min, max) {
    return Math.floor(Math.random() * (max - min) + min);
}
function getRandomString() {
    const alphabet = 'a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,z,y,z';
    const alphabet_array = alphabet.split(",");
    const minLength = 5;
    const maxLength = 25; 
    const randomAmount = getRandomInteger(minLength,maxLength);
    let random;
    let word = "";
    for(let i = 0; i < randomAmount; i++) {
        random = getRandomInteger(0,26);
        word += (alphabet_array[random]);
    }
    console.log(word)
}
getRandomString();</code>

### Photos:
<img width="697" alt="p1-folders" src="https://github.com/mayasykes1/cit281-p1/assets/52678410/84aed07c-576d-4576-965c-ee9072db2210">
<img width="506" alt="p1-ping" src="https://github.com/mayasykes1/cit281-p1/assets/52678410/02323e21-4d3a-42e5-a045-cd523741dd85">
<img width="537" alt="p1-break" src="https://github.com/mayasykes1/cit281-p1/assets/52678410/496bd146-07f6-47d6-a621-70f9310f7985">
<img width="711" alt="p1-tree" src="https://github.com/mayasykes1/cit281-p1/assets/52678410/aed7b152-1754-47b1-b7e6-2211de999fd8">




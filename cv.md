# Khamitsevich Elena
## Contacts
* Phone: +375 33 626-17-81
* E-mail: <khamitsevich.elen@gamil.com>
* Discord: elenakhamitsevichelena
* Github: khamitsevich-elena

## About me

I am a responsible person, able to work in conditions of multitasking. I am currently working as a Lead Chemical Engineer.
When the work ceased to bring pleasure, I became interested in web development. I watch courses on online services, read books.
This is not the first time here, but not having enough time I had to quit what I started.
My goal is to improve my level of web development for further change of activity.
## Skills
* HTML
* CSS
* Bootstrap
* BEM
* LESS/SASS
* Figma
* JavaScript(Fundamentals, ES6+, DOM, JSON)
* React/Redux(basic knowledge)
* PHP(basic knowledge)

## Code Examples
Create the function consecutive(arr) that takes an array of integers and return the minimum number of integers needed to make the contents of arr consecutive from the lowest number to the highest number.

For example:
If arr contains [4, 8, 6] then the output should be 2 because two numbers need to be added to the array (5 and 7) to make it a consecutive array of numbers from 4 to 8. Numbers in arr will be unique.

```
function consecutive(arr) {
  if(arr.length == 0){
    return 0;
  }
    let min = arr.reduce((x, y) => Math.min(x, y));
    let max = arr.reduce((x, y) => Math.max(x, y)); 
      let n = 0;
      for(let i=min;i<=max;i++){
        if(!arr.includes(i)){
          ++n;
        }

      }
      return n;
}
```
## Experience
* <https://khamitsevich-elena.github.io/>
* <https://khamitsevich-elena.github.io/todolist/todolist>
* <https://match-match-game-1daad.web.app/>

## Education
* Belarusian State University
    + Chemical faculty
        - Nuclear chemistry
* Courses:
    + TeachMeSkills
    + Udemy
    + Learning PHP, MySQL & JavaScript, 6th Edition _by Robin Nixon_(in progress)

## English
* A2-B1

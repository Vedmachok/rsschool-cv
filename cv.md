# Aleksandr Akhtirsky 
### Junior Frontend Developer

---

### Contact information:

**Phone:** +38 063 4331111<br>
**E-mail:** alexandr.ahtirsky@i.ua<br>
**Telegram:** @Vedmak_A<br>
[LinkedIn](https://www.linkedin.com/in/александр-ахтырский-890b77219/)<br>
[Codewars](https://www.codewars.com/users/Vedmachok)

---

### Briefly About Myself:

I have more than ten years experience as a data analyst. Preparation and construction of reports, analysis of sales, balances, forecasting.
I have a good command of Microsoft Office Word, Excel (summary tables, functions, formulas, data bulk processing), PowerPoint.<br>
In 2015 finished courses: "Contact" Educational Center, MSSQL Programmer Courses (2015, 3 months)<br>
I am engaged in self-development and I am interested in the Front-End Developer direction. I independently studied the basic basics of programming: HTML5, CSS, JavaScript.<br>
Work examples: [GitHub](https://github.com/Vedmachok);



---

### Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- Basics SQL
- Gulp, Grunt
- SASS, LESS
- VS Code, IntelliJ IDEA, Atom
- Adobe Photoshop

---

### Code example:

**Create Phone Number**
*Example
```createPhoneNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 0]) // => returns "(123) 456-7890"```
The returned format must be correct in order to complete this challenge.
Don't forget the space after the closing parentheses!*

```javascript
function createPhoneNumber(numbers){
  let fullNumber =[]
  for(let i = 0; i < numbers.length; i++){
    if( i === 0 ){
       fullNumber.push('(')
     }
    
    if( i === 3 ){
       fullNumber.push(') ')
     }
    if( i === 6 ){
       fullNumber.push('-')
     }
    
    fullNumber.push(numbers[i]);
  }
  return fullNumber.join('');
}
```
---

### Courses:

- JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/) (in progress)


---

### Languages:

- English \- Intermediate/Upper-intermediate 
- Russian \- Native
- Ukrainian \- Intermediate

# Irina Blagoveschik

## Contact information

* __Location__: Minsk, Belarus
* __Phone__: +375 29 343-90-07
* __Email__: irina.blagoveschik@gmail.com
* [LinkedIn](https://www.linkedin.com/in/irina-blagoveschik-23a088207/)

## About Myself
After being a tutor of English for 6 years I faced the lack of opportunities for professional growth. I decided to get knowledge in IT. As I didn’t have any related skills I finished the course of manual testing. By chance, I entered the LeverX Intro Course where I had my first experience in learning programming language (JavaScript) and successfully completed it. I became passionate about Frontend Development. Currently I continue getting skills that are “must have” to become a professional developer.

## Skills
* HTML5, CSS3
* JavaScript (Basics)
* Git
* SQL
* Jira, Confluence

## Code example
*A piece of code that validates the chosen answers in application __Test__*
``` javascript
  var re = /^[1-4]{1}(,[1-4]{1})*$/;
  
  var isCorrectAnswerValid = re.test(correctAnswer);
  
	//check if entered answer numbers are unique
  if(isCorrectAnswerValid){
	var arrCorrectAnswers =	correctAnswer.split(",").map(function(index){return index - 1;});	
  var uniqueArrCorrectAnswers = arrCorrectAnswers.filter((element,index,arr)=>{return (arr.indexOf(element) == index);}); 
	isCorrectAnswerValid = uniqueArrCorrectAnswers.length == arrCorrectAnswers.length;
  } 

  if(!isCorrectAnswerValid){
    showNotification("Поле может содержать только уникальные цифры 1,2,3,4, разделенные запятой. Попробуйте добавить вопрос заново.");
    return;
  }
```

## Experience
LeverX Intro Course: _Application_ **Test**. User can enter questions, answer options and the right answers. The test can be passed and then automatically checked.

## Education
* __Courses:__
    * https://learnjavascript.online/
    * https://learnprogramming.online/
    * https://itvdn.com/ru/video/html5-css3-starter/
    * LeverX Intro Course
* __State Institute of Management and Social Technologies of Belarusian State University: «LINGUA+»__ Language Interpretation and Translation

## English language
Advanced level, speak English fluently. Have 6 year experience of teaching English.

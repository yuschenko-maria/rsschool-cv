# Maria Yuschenko
## Contacts
* **[LinkedIn](https://www.linkedin.com/in/%D0%BC%D0%B0%D1%80%D0%B8%D1%8F-%D1%8E%D1%89%D0%B5%D0%BD%D0%BA%D0%BE-9505261a9)**
* **[GitHub](https://github.com/yuschenko-maria)**
* **e-mail**: yuschenko.maria@icloud.com
## About me
*I am a fast learner, I do not quit what I started, I like to develop and learn new things. I am able to work effectively both in a team and alone*
## Skills
* HTML
* CSS
* JavaScript(basics)
* Git
## Code Example
```
function unluckyDays(year){
  let unlucky = 0;
  for (x = 0; x < 12; x++) {
    unlucky += new Date(year, x, 13).getDay() === 5 ? 1 : 0;
  }
  return unlucky;
}
```
---
```
function getCount(str) {
  var vowelsCount = 0;
  str.split('').map(str =>{
    if(/[aeiouAEIOU]/.test(str)){
      vowelsCount++;
  }
  })
  return vowelsCount;
}
```
---
```
function checkCoupon(enteredCode, correctCode, currentDate, expirationDate){
  let date1 = new Date(currentDate)
  let date2 = new Date(expirationDate)
  if (enteredCode === correctCode && date1 <= date2){
    return true;
  }
  return false;
}
```
## Experience
*I have no work experience, but often practice my knowledge by myself*
## Education
* HTML, CSS on codebasics
* JavaScript on learnjavascript

#### Cources
* RSSchool Stage 0
## English
C1 (practice English with my English-speaking friend from Germany and while living in Poland)

[rs-school](https://rs.school/ "URL rs-school")
****
# Dana Sundetbayeva
****
## Junior Front-end Developer
****
Contacts:
* _Discord_: __Dana#2950__
* _Telegram_: __@dana_10969__
* _E-mail_: __danasundetbayeva@gmail.com__
****
About me:

1,5 year ago I decided to change my career from engineer in
automatic and control to web developer. In Front-end I like to create
useful and convenient apps from client side. In the future I am going 
to learn server side as well!
****
Skills and Proficiency:
* HTML
* CSS
* JavaScript
* React
* Figma
* Git
* Rest.API
****
Code example:

_You are given an array(list) strarr of strings and an integer k.
Your task is to return the first longest string consisting of k
consecutive strings taken in the array._

```
function longestConsec(strarr, k) {
  if (!strarr || k > strarr.length || k <= 0) return ''
  
  let res = [];
  let currentArr = []
  
  for (word in strarr) {
    currentArr = strarr.slice(word, +word + k).join('')    

    if (currentArr.length > res.length) {
      res = currentArr
      
    }

  }
  return res
  
}
```

****
My Projects:

* [Project 1](https://sundetbayeva-dana.github.io/sw/ "Link to SW repository") - HTML, CSS, JS, API.Rest - __Small project where you can find Stars Wars characters__
* [Project 2](https://sundetbayeva-dana.github.io/mesto/ "Link to mesto repository") - HTML, CSS, JS, API.Rest - __Project where you can save your cards and press like button to others__
* [Project 3](https://sundetbayeva-dana.github.io/react-mesto-auth/ "Link to mesto-react repository") - HTML, CSS, JS, React, API.Rest - __Project where you can save your cards and press like button to others with authorization using React__
****
Courses:

Web-developer by [Yandex.Praktikum](https://practicum.yandex.ru/ "Link to Yandex.Praktikum")
****
Languages:

* English - Intermediate
* Russian - Native

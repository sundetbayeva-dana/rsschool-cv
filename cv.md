# Dana Sundetbayeva

## Junior Front-end Developer

### Contacts:
    *Discord*: **Dana#2950**
    *Telegram*: **@dana_10969**
    *E-mail*: **danasundetbayeva@gmail.com**

### About me:
    2 years ago I decided to change my career from engineer in automatic and control to web developer. In Front-end
    I like to create useful and convenient web apps from client side. In the future I am going to learn server side as
    well!

### Skills and Proficiency:
    * HTML
    * CSS
    * JavaScript
    * React
    * Vue
    * Figma
    * Git
    * Rest.API

### Code example:
    *You are given an array(list) strarr of strings and an integer k. Your task is to return the first longest string
    consisting of k consecutive strings taken in the array.*

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


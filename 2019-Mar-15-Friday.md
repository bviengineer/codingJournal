>>>>>>>>># Q&A DAY :question::pencil::hourglass_flowing_sand:

Today was set aside as a Q&A day, a day to articulate my thoughts and knowledge on technical and development concepts, practice potential whiteboard exercises.

The questions answered do not live in this repo and include: 
* Explain the difference between `=`, `==` and `===`
* When is it accepable to use `==` versus `===` or vice versa

The coding exercise completed
* Write a function that checks a string for a palindrome (forwards and backwards). The challenge was completed in `JavaScript` and `Ruby`.

  [Run the code below in my JavaScript Repl](https://repl.it/@bviengineer/QandA-Day-for-JavaScript)
  ```javascript
    // JavaScript
  
    //chaining methods in a function
    function reverseString(word){
      return word.split("").reverse().join("");
    }
    reverseString("table"); // OUTPUT: elbat
  ```
  [Run the code below in my Ruby Repl](https://repl.it/@bviengineer/QandA-Day-Repl-for-Ruby)
  ```ruby
    # Ruby

    def palindrome(word)
      return word.reverse
    end

    puts palindrome("developer") # OUTPUT: repoleved
    puts palindrome("madam")     # OUTPUT: madam
  ```
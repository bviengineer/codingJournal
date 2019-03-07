# THEORY | LECTURE DAY!:book::pen::school::computer:

![Classroom](img/maintenance.jpg) 
###### Photo obtained from Pixaby. No attribution is required. However, as a thank you to and visibility for, Pixaby and the author, [here's a link to the image](https://pixabay.com/vectors/classroom-blackboard-class-learning-42275/) by [Clker-Free-Vector-Images](https://pixabay.com/users/Clker-Free-Vector-Images-3736/) on [Pixabay's website](https://pixabay.com/).
<hr>

## [App Academy Open FREE Online Full-Stack Curriculum]() - REVIEW
As mentioned during [my last review day](https://github.com/bviengineer/codingJournal/blob/master/2019-Feb-28.md), it has been two weeks since I last touched the App Academy Curriculum and a result, today was a continued refresher on what I previously learned.
* Variables: 
  * `var_example = 42`
  * `name = 'Student'`
  * ` = ` is the assignment operator while `==` and `===` are equality operators
<br>
* Methods:
  * Methods allow you to run or execute repeative code wihtout having to duplicate the code.
  * Example of a method in Ruby
  ```ruby
    def ruby_method
      # code here...
      puts "I am a Ruby method"
    end

    # Call or execute the method
    ruby_method

    # Output
    "I am a Ruby method"
  ```
  * `def` is short for define
  <br>

 * Method **with parameter**
  ```ruby
    def method_with_parameter(location)
      puts "Hello World from: " + location
    end

    # Calling method & passing it the execpted var as 
    # an argument
    method_with_parameter("Space")

    # Output
    "Hello World from: Space"
  ```
* Conditionals: 
```ruby
  #e.g
  num = 50
  if num > 0
    puts "It is greater than zero"
  elsif num < 0
    puts "It's not greater than zero"
  else
    "It's zero!"
  end

  # Possible combinations
  if
  end

  if
  else
  end

  if
  elsif
  else
  end
```
<hr>

## [JavaScript via Go Make Things](https://gomakethings.com)
Continued with DOM manipulation and reviewed:
* Selecting Elements
  * `getElementsByClassName()`
  * `getElementsByTagName()`
  * `matches()`
    * checks to see if a particular method would be selected by a particular selector or selectors. 
    * returns a boolean if a match is found 
    ```javascript
      const tag = document.querySelector("#bold-word");

      if(tag.matches("#bold-word")){
        // if condition evaluates to true
        console.log("It's a match!");
      } else {
        // if condition evaluates to false
        console.log("It's not a match!");
      }
    ````
  * Selectors that target specfic element types such as `getElementById()` and `getElementsByClassName()` are faster than selectors like `querySelector()` and `querySelectorAll()`
* Loops
  * `for loop` to loop through arrays and node lists
    * `continue` can be used to skip or move on, inside of a loop
<hr>

## [AWS CCP]()
Took the [ACG](https://acloud.guru) AWS Certified Cloud Practioner exam simulator, made up of 65 questions. Scored in the 70's. Will retake test after reading through the AWS white papers.
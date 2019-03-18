# THEORY | LECTURE DAY! :school::book::pen::computer:
![Classroom](img/classroom.png) 
###### Photo obtained from Pixaby. No attribution is required. However, as a thank you to and visibility for, Pixaby and the author, [here's a link to the image](https://pixabay.com/vectors/classroom-blackboard-class-learning-42275/) by [Clker-Free-Vector-Images](https://pixabay.com/users/Clker-Free-Vector-Images-3736/) on [Pixabay's website](https://pixabay.com/).
<hr>

## [App Academy FREE Online Full-Stack Curriculum](https://online.appacademy.io)
Continued review of **Array Methods & Enumerables** and reviewed:
* `.split()` =>   * can only be used or _called_ on strings and **returns an array** 
  ```ruby
    str = "Follow the yellow brick road"

    puts str.split(" ") # tells ruby to split the string wherever 
    # there are spaces
    
    # output
      # Follow
      # the
      # yellow
      # brick
      # road

    print str.split(" ") 
    # tells ruby to split the string wherever 
    # there's a space which isolates each word

    # output
      # ["Follow", "the", "yellow", "brick", "road"]

  ```
* `.join()` => can only be _called_ on on arrays and **returns a string**
  ```ruby
    arr = ["Follow", "the", "yellow", "brick", "road"]

    print arr.join(" ")

    # output
      # Follow the yellow brick road    
  ```

* Other useages of `.spilt()` and `.join()`
    ```ruby
    # using .split() to split a string on each character
        string = "table"

        print string.split("") #no space between the "" quote marks
        # output: ["t", "a", "b", "l", "e"]


    # CHAINING .split() and .join() together
    my_house = "table cloths"

    print string.split("l").join("X")
    
    # output 
      # tabXe cXoths
       # the string is split into an array wherever there's a lower case
        # "L".  The l's are removed and then the array is joined together
        # as a string, replacing appearances of l's with X's. 
    ```

See my **[Ruby Repl.it here](https://repl.it/@bviengineer/StupidOurCommunication)** to run the code examples
<hr>

## [Go Make Thiings](https://gomakethings.com)
Resumed DOM manipulation methods and reviewed:
* `arr.forEach()` 
  * => calls a function once for each element in an **array** in acending order. Unlike `for loops`, `forEach()` does not interate through `string` data types.
  * Unlike `for loops`, the need for an incrementer variable, increasing/decreasing the incrementer variable, and checking the status of the incremeter variable against the test condition, are eliminated. 
  <br>

* `NodeList.forEach()` 
  * => iterates over nodeLists
  * requires more digging, the examples are confusing.
<br>

* `Object.keys(objectName)`
  * => `ES6` way of looping through objects
  * returns the `keys` or `object keys` of an object
  * `.forEach()` can be chained to the end to access and loop through the list of values assigned to each key.
    ```javascript
      // Examples

      let bible = {
        bible: 'Genesis',
        chapter: '1',
        verse: '1'
      };

      //prints the object keys only
      console.log(Object.keys(bible));
      // OUTPUT: ['book', 'chapter', 'verse']


      //prints the object keys and their corresponding values
      Object.keys(bible).forEach((value) => {
        console.log(value) //outputs the object's keys
        console.log(bible[value]) //outputs the values assigned 
        //to the object's keys
      });

      /* 
        OUTPUT:
         Object keys then values:
          bible   => key
          Genesis => value
          chapter => key
          1       => value
          verse   => key
          1       => value
      */
    ```
    See my **[JavaScript Repl.it here](https://repl.it/@bviengineer/TruthfulUnfitPerimeter)** to run the code examples
    <hr>
    
    ## [Git]()
    In an effort to improve my collaboration skills, resumed review git of on [Udacity](https://udacity.com). Looked over the following concepts:
    * `git add` 
      * stages files by moving untracked files to the staging area or staging index
    * `git rm --cached <file>`
      * moves "staged" files back to the working directory or it 'unstages' files
    * `git commit`
      * moves a staged file to the respository; opens default text editor for commit message to be added
    * `git commit -m`
      * moves or commits a staged file to thhe repository bypassing the text editor and allowing the commit message to be accepted at once
    * `git log`
      * view details of [a] commit(s) including the message body
    * `git log -p`
    * `git log --oneline`
      * shows information for a given commit on a single line 
  <br>
  
    * `git tag`
      * creates a lightweight tag
      * allows you to add labels to commits
      * `git tags` don't move when you make commits
    `git tag -a`
      * creates an annotated flag which is recommended and provides extra info such as:
        * the person who created tag
        * date the tag was made
        * a message for the tag
    * `git tag -d`
      * allows you to delete tags by referencing the name of the tag
      * `d` means delete
    * `git branch`
      * branches allows you to create parallel and separate branches for the development of specific feature
    * `git checkout`
      * switch between branches and tags
    * `git merge`
      * combine changes on branches

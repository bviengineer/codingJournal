<!-- Photo obtained from Pixabay.com and uses a Pixabay license. It is Free for Commerical use. No attribution is required. -->
![Colorful & Flexible Pencils](https://cdn.pixabay.com/photo/2015/01/17/18/28/pencil-602440_640.jpg)
## FreeCodeCamp [FCC]
 Completed the CSS flexbox module and covered:
 * `flex-basis` property
 * `flex` shorthand property
 * `order` property to rearrange items
 * `alig-self` property

This completes the CSS Flexbox portion of the Responsive Web Design Ceritification. Next up, CSS Grid.
_ _ _ _
![A Trunk of music records](https://cdn.pixabay.com/photo/2013/07/05/12/24/records-143468_640.jpg)
## App Academy [free] Full-Stack Curriculm
Continued with __Array Manipulation Methods & Enumerables__: Range Slicing and Split & Join lectures, along with an Array cheat Sheet.
* __Range Slicing__ works on arrays and strings:
   ```ruby
  arr = ["a", "b", "c", "d", "e"]
  print arr[1..3] 
  #will print b - d 
  #2 dots mean that the beginning and ending limits are INCLUDED in the range

  arr = ["a", "b", "c", "d", "e"]
  print arr[1...3] 
  #will print b - c
  #3 dots mean that the ending limit is EXCLUDED from the range

  string = "generation"
  print string(3..-1) 
  #will print "eration"
  #a negative (-) number references the end of the string
  #-1 indicates the last character in the string 
  #all characters, beginning at position 3 and up to the very last character in the string(-1), will be printed
  #generation => -1 = n, -2 = o, etc.
  ```
* __.split & .join__:
__.split__ works only on strings but evaluates to an array while leaving the original string variable in tact. <br>
__.join__ works only on arrays but evaluates to a string while leaving the original array in tact.
  ```ruby
  #EXAMPLES using .split
  str = "coding is fun and creative"
  
  print str.split(" ") 
  #using the blank spaces between each word => (" ") as the separator, each word becomes an element in the resulting array

  print str.split("is")
  #evaluates to ["coding", "fun", "and", "ceative"]
  #everything to the left and right of the separator => ("is") is included in the resulting array

  print str.split("i")
  #evaluates to ["codng", "s", "fun", "and", "ceatve"]
  #all appearances of the separator => ("i") are excluded from the resulting array

  print str.split("")
  #evaluates to ["c", "o", "d", "i", "n", "g", " ", "i", "s", " ", "f", "u", "n", " ", "a", "n", "d", " ", "c", "r", "e", "a", "t", "i", "v", "e"]
  #in this output there is no separator => (""), and thus each character becomes an element in the array


  #EXAMPLE using .join
  arr = ["coding", "is", "fun", "and", "ceative"]

  print arr.join(" ")
  #evaluates to "coding is fun and creative"
  #a blank space => (" ") is the separator

  print arr.join("_")
  #evaluates to "coding_is_fun_and_creative"
  #the underscore => is the separator and will appear between each word

  
  #EXAMPLE combining .split & .join => swapping characters
  str = "coding is fun and creative"
  
  print str.split("i").join("X")
  #evaluates to "codXng Xs fun and creatXve"
  #all apperances of "i" => ("i") are first removed and then replaced with X => ("X")

  ```
* __Array cheat sheet__ provided methods for
  * Array manipulaiton
    * array.push 
    * array.pop 
    * array.shit 
    * array.unshift
  * Checking for the existence of something
    * array.include?
    * array.index
  * Conversion between an array and a string
    * .array.join
    * .string.split
  * Array Enumerable Methods
    * array.each => iterate or loop over elements in an array
    * array.each_with_index do ( |array, i| ) => loop over array elements using an index
  * String Enumerable Methods
    * array.each_char => iterate or loop over characters in a string
    * array.each_with_index do |char, i|  => loop over string characters using an index
  * Other Methods
    * Repeat a block **n** times
    ```ruby 
      2.times do
        puts "coding"
      end # prints
      # coding
      # coding
    ```
    * A range of numbers using (start __..__ end) or (start __...__ end)
    ```ruby
    # including end => 2 dots ..
      (3..7).each {|n| puts n} # prints
      # 3
      # 4
      # 5
      # 6
      # 7

      # excluding end => 3 dots ...
      (3...7).each {|n| puts n} # prints
      # 3
      # 4
      # 5
      # 6
    ```
_ _ _ _
## Frontend Mentor
[Frontend Mentor](https://www.frontendmentor.io/) is an online source that provides developers with front-end based challenges to buildout. Each project include designs, project overview, style guide and starter code. There are a number of projects and between last night and today, I worked on the the _Huddle landing page with coded decorative elements_. Worked on:
* Marking up the HTML using HTML5 semantic tags.
* Positioning header elements in their respective places based on the mockup.
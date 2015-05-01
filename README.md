##Arrays

###SWBAT
+ understand what an array is and when to use it
+ declare arrays and add items
+ fetch array elements by index
+ insert new values into an array
+ access array elements by their index
+ store or change elements in an array
+ call methods on an array - like length, push, pop, splice
+ understand when to use associative arrays

###Lesson Plan
+ Let’s start by learning about arrays. We’ll do this by making our own arrays.
+ Think about an array as an ordered list that can be visualized as a two-column table where the left column is the index (or the order) and the right column is the thing you’re listing (Draw on board, using one of the students’ examples):
<img src= "https://s3.amazonaws.com/after-school-assets/advanced_jquery1.png">
+ Notice that the index starts at 0. This is a quirk about data structures in computer science that you just have to memorize. The first item in an array is always 0, and it increments by one.
+ So how do we translate this table into code?
  + [“Danny”, “Lyel”, “Victoria”, “Vanessa”]
  + Remember that the names are data so they must be in quotes as strings.
  + We use square brackets to denote an array.
  + We don’t explicitly write the index anywhere. (show the index above each item on the board)
+ Great, we’ve made an array. Let’s go ahead and assign it to a variable so that whenever we call the variable names we have the array returned to us.
+ <b>Model and then have students create a new file in their development directories to hold their array practice code. Have students create their own array of their choice and assign it to a variable. Have students turn to partners and check with each other.</b>
+ Great. We’ve created the array. Now what if I just want to get out one item from the array instead of the whole thing. For example, What if I want to get the third item listed in my array?
+ We access items in an array using the brackets and the index of the thing you want.
+ <b>names[3] will give me what? (the fourth). how do I get the third item?
+ So what if we want to change one of the items in the array? Any thoughts on how we can reassign/change an item?</b>
+ names[2] = “Joe” will change the third item in the array to Joe. (Model this)
+ We can also add and remove items from an array. Arrays actually have methods built in to them. Remember that methods are just a set of instructions.
  + names.push(“Alfred”) will add an item with the contents of the argument to the end of the array it is called on. 
  + names.pop() will remove the last item in an array.
+ Here are some other cool methods: .length(), .sort(), .splice(), split().
+ <b>[Mini Lab](https://learn.co/admin/lessons/5206): Manipulating arrays (start with array and then have 10 instructions, what does array look like at the end?)
+ Answer: ["Peru", "Laos", "Chad", "Cuba", "Togo", "Iraq", "Iran", "Mali", "Oman", "Fiji"] </b>

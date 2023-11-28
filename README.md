# Process Writeup

## Name: Wilson Huang
## Course: APCSA
## Period: 7
## Concept: Unit 4

### Introduction 
In APCSA (Advanced Placement Computer Science A), we are learning about Java. Learning Java is somewhat similar to Javascript; so I am familiar with some of the code. In unit 4 we have been learning about Iterations which is like looping. Learning Iterations have been challenging because it is really confusing to understand. In this writeup I will talk about some learning moments and challenges which is mostly about confustion and not getting the material about unit 4.

### Challenge 1
One challegne I had when learning about for and while loops was telling the difference between both and when to use one over the other. During the quiz we had, there was a question asking when to use for and while loops. The question said `"When would it be more beneficial to use a while loop instead of a for loop?"` and I chose` "Whenever you need to do repeated calculations with a variable"`. This is incorrect because they both can repeat calculations. I realized after the test that while loops are used when you don't know when the loop ends and for loops do it for a certain amount of times. 
#### While loop
```js
while(x != 0){
  System.out.println("Hello world"); // Does this infinity amount of times as long x does not equal to 0
}
```
#### For loop
```js
for(int i = 1; i >= 10; i++){
  System.out.println("Hello world"); // Does this for 10 times and stops when i is greater than 10
}
```

### Challenge 2
One challegne I had when learning about unit 4 is nested loops. It is where there is a loop inside a loop. I didn't understand how this worked. I watched this [youtube video](https://www.youtube.com/watch?v=AO-iAyBvNXo&t=198s) about nested loops and it was helpful. I learned that each time the each time the outer loop loops the inner loop does a full cycle. For example:
```Java
    int weeks = 3;
    int days = 7;

    // outer loop prints weeks
    for (int i = 1; i <= weeks; ++i) {
      System.out.println("Week: " + i);

      // inner loop prints days
      for (int j = 1; j <= days; ++j) {
        System.out.println(" Day: " + j);
      }
    }
```
For example in this nested loop I found in the internet, the outer loop, i will print one week and then the inner loop will print all the days from each week.

### Challenge 3
Another challenge I had when learning unit 4 is making algorithms for strings. It was also confusing to understand. For example I found it hard understanding traversing strings. I understood what it does but I didn't understand how it works. Traversing string is a loop that goes through each character in a string. I later watched this [video](https://www.youtube.com/watch?v=s7w-q2RoIFg) to understand how it works. 
```js
for (int i = 0; i < str.length(); i++) 
{
  System.out.print(str.substring(i, i + 1));
}
```

After watching the video, I understood the concept. The for loop condition will go through every letter of the string and the ` System.out.print(str.substring(i, i + 1));' will print out every letter sine substring is the first letter you want and the other letter your don't want (+1).

### Challenge 4

### Takeaways
* Watch youtube videos if you don't understand a topic since there are a lot or resources in youtube

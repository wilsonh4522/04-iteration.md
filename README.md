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
After learning all materials about unit 4 we had to take an exam. I didn't do so well at the exam so I will take you through some of the questions I got wrong and my explanation and reasoing. 
#### Question 1 
```js
int f = 0;
while (f < 7)
{
  System.out.print(f % 3 + " ");
  f++;
}
```
For this question I answered `0 1 2 0 1 2 `. This is wrong because there should be 7 outputs instead of 6 since f = 0 so the answer is `0 1 2 0 1 2 0 `

#### Question 2
Assuming that str is a correctly initialized String, which of the following best describes what the algorithm below does?
```js
int i = str.indexOf("a");
while (i != -1) 
{
  System.out.print(str.substring(0,i));
  str = str.substring(i + 1);
  i = str.indexOf("a");
}

System.out.print(str);
```
In this question I said `Prints the character before each a in str`. I realized that this is wrong because `str = str.substring(i + 1);` has a plus 1 so it prints the word including a so the answer is `Prints each character in the string, str, except for the lowercase a’s`.


### Takeaways
* Watch youtube videos if you don't understand a topic since there are a lot or resources in youtube
* You should aways review the questions you got wrong in the unit exam because it can help you learn from your mistakes
  

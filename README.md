# What is Machine Learning ?
What is Machine Learning ?

Consider the traditional manner of building apps, as represented in the following diagram:

![image](https://user-images.githubusercontent.com/51197053/141085516-fac5c57f-1e4d-4ec2-aef5-18bdf331920f.png)

<text>
You express rules in a programming language. They act on data and your program provides answers**.** In the case of the activity detection, the rules (the code you wrote to define activity types) acted upon the data (the person's movement speed) to produce an answer: the return value from the function for determining the activity status of the user (whether they were walking, running, biking, or doing something else).
</text>  
<br><br>
<p>The process for detecting that activity status via ML is very similar, only the axes are different.</p>

![image](https://user-images.githubusercontent.com/51197053/141086128-e4c6d9f1-247a-4410-a941-bef9f434ca7e.png)

<text>Instead of trying to define the rules and express them in a programming language, you provide the answers (typically called labels) along with the data, and the machine infers the rules that determine the relationship between the answers and data. For example, your activity detection scenario might look like this in an ML context:</text>


![image](https://user-images.githubusercontent.com/51197053/141087560-f3854579-5fbf-4d49-9380-ea2907a36e83.png)

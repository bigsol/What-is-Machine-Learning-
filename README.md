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

<text><b>You gather lots of data and label</b> it to effectively say, "This is what walking looks like," or "This is what running looks like." Then, the computer can infer the rules that determine, from the data, what the distinct patterns that denote a particular activity are.</text>

<text>Beyond being an alternative method to programming that scenario, that approach also gives you the ability to open new scenarios, such as the golfing one that may not have been possible under the rules-based traditional programming approach.</text>

<text>In traditional programming, your code compiles into a binary that is typically called a program. In ML, the item that you create from the data and labels is called a model.</text>

<text>So, if you go back to this diagram:</text>

![image](https://user-images.githubusercontent.com/51197053/141088490-e07b8f89-f4fd-4d70-ae69-d2631c01b965.png)

<text>Consider the result of that to be a model, which is used like this at runtime:</text>

![image](https://user-images.githubusercontent.com/51197053/141088902-242c268e-4ecb-4268-a93c-9304b8de7208.png)

<text>You pass the model some data and the model uses the rules that it inferred from the training to make a prediction, such as, "That data looks like walking," or "That data looks like biking."</text>

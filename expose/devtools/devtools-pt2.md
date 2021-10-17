**#1) What was the bug?**

The bug was that the num1 and num2 inputs from the user were added, but as a string. This is why for an input like 1 and 2 respectively, we were getting 12 and not 3 since strings were getting concatenated instead of addition getting performed. 


**#2) How would you fix it? Include a screenshot of your fix. Name it fix.png (or whatever image extension you would like to use)**

I fixed the bug by converting the type of num1 and num2 variables into a number. Doing so, the result ended up being of type number as well after the addition between num1 and num2 was done. Screenshot included in the folder!

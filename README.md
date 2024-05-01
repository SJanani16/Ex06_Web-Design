# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("No Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Find Grade Result of a Student
</h1>
</body>
</html>
```


## OUTPUT
![Screenshot (33)](https://github.com/SJanani16/Ex06_Web-Design/assets/168054215/bafbe97e-7769-4ce3-9d7f-b3edf8783530)
![Screenshot (34)](https://github.com/SJanani16/Ex06_Web-Design/assets/168054215/2233bdbb-1657-4d4d-88b0-f9ceb228c9b8)
![Screenshot (35)](https://github.com/SJanani16/Ex06_Web-Design/assets/168054215/a8a53131-1ce8-4a41-b7e5-9a874d69662f)
![Screenshot (36)](https://github.com/SJanani16/Ex06_Web-Design/assets/168054215/de957de1-0393-4f17-bf0c-7779502fa8a0)
![Screenshot (37)](https://github.com/SJanani16/Ex06_Web-Design/assets/168054215/ad5951d5-f455-4421-8b08-af38f464eb7f)
![Screenshot (38)](https://github.com/SJanani16/Ex06_Web-Design/assets/168054215/dc518bc1-1fa2-44ef-8a78-7e022d826317)







## RESULT
  Student result using JavaScript is created successfully.

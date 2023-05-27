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
```<html>
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function student()
{
    var mark1, mark2, mark3, mark4, mark5, total, percentage;
    mark1 = parseInt(prompt("Enter Subject-1 Marks"));
    mark2 = parseInt(prompt("Enter Subject 2 Marks"));
    mark3 = parseInt(prompt("Enter Subject 3 Marks"));
    mark4 = parseInt(prompt("Enter Subject 4 Marks"));
    mark5 = parseInt(prompt("Enter Subject 5 Marks"));
    total = mark1 + mark2 + mark3 + mark4 + mark5;
    percentage = total / 5;

    if (percentage >= 91 && percentage <= 100)
    {
        alert("O Grade");
    }
    else if (percentage >= 81 && percentage <= 90)
    {
        alert("A+ Grade");
    }
    else if (percentage >= 71 && percentage <= 80)
    {
        alert("A Grade");
    }
    else if (percentage >= 61 && percentage <= 70)
    {
        alert("B+ Grade");
    }
    else if (percentage >= 51 && percentage <= 60)
    {
        alert("B Grade"); 
    }
    else
    {
        alert("RA Grade");
    }
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
```

## OUTPUT
![webassignment62](https://github.com/22006782/Ex06_Web-Design/assets/128878369/bfd8f5f2-b006-4aa5-9c58-8ce01985db15)
![webassignment63](https://github.com/22006782/Ex06_Web-Design/assets/128878369/5682992e-6804-444a-9e62-7969e6b996da)
![webassignment64](https://github.com/22006782/Ex06_Web-Design/assets/128878369/b85bf0c1-beab-45e9-8c75-3d1590524070)
![webassignment65](https://github.com/22006782/Ex06_Web-Design/assets/128878369/66accf8e-01fc-4479-be35-8ba12737779c)
![webassignment66](https://github.com/22006782/Ex06_Web-Design/assets/128878369/2441a877-d34d-4fa2-bd3c-cb86e1c51d9b)
![webassignment67](https://github.com/22006782/Ex06_Web-Design/assets/128878369/89bec93c-f4a9-482d-afaf-c95a6e713967)




## RESULT
  Student result using JavaScript is created successfully.

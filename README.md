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

## OUTPUT

![Screenshot 2023-05-26 223320](https://github.com/JosephselwinJ/Ex06_Web-Design/assets/127816444/201c83dd-e391-4818-8121-5e23d1f2dc33)
![Screenshot 2023-05-26 223339](https://github.com/JosephselwinJ/Ex06_Web-Design/assets/127816444/effe7eec-2e17-46b6-853d-0738f31499c9)
![Screenshot 2023-05-26 223353](https://github.com/JosephselwinJ/Ex06_Web-Design/assets/127816444/c82cf194-328b-4a93-90b7-203293946b90)
![Screenshot 2023-05-26 223413](https://github.com/JosephselwinJ/Ex06_Web-Design/assets/127816444/2314b4dc-5ef8-4e83-a181-9926543c6689)
![Screenshot 2023-05-26 223430](https://github.com/JosephselwinJ/Ex06_Web-Design/assets/127816444/bc459290-d0ef-4595-b7d8-9a3496e5f81b)
![Screenshot 2023-05-26 223451](https://github.com/JosephselwinJ/Ex06_Web-Design/assets/127816444/325ca628-9005-4bf7-ba2c-fbf5da0bf376)
![Screenshot 2023-05-26 223502](https://github.com/JosephselwinJ/Ex06_Web-Design/assets/127816444/54c4ddd9-3f5a-44c9-b704-5716d584e28f)

## RESULT
  Student result using JavaScript is created successfully.

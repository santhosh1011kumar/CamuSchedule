# Ex08 CAMU Schedule using Bootstrap
## Date: 16-03-2026

## AIM:
To design a responsive and visually appealing CAMU Schedule using Bootstrap.

## DESIGN STEPS:
### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Add the Bootstrap CDN link inside the <head> section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
<title>CAMU Schedule</title>

<!-- Bootstrap CDN -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

<style>

body{
background:#f3f4f6;
font-family: Arial;
}

/* Sidebar */

.sidebar{
background:#ffffff;
height:100vh;
border-right:1px solid #ddd;
padding-top:20px;
}

.home-icon{
width:50px;
height:50px;
background:#3da5f4;
color:white;
display:flex;
align-items:center;
justify-content:center;
border-radius:10px;
margin:auto;
margin-bottom:30px;
}

.menu li{
list-style:none;
padding:12px 20px;
color:#666;
cursor:pointer;
}

.menu li:hover{
background:#f0f7ff;
}

.active{
background:#e6f2ff;
border-radius:6px;
}

/* Header */

.header{
background:white;
padding:15px 25px;
border-bottom:1px solid #ddd;
}

.header h4{
margin:0;
}

/* Content */

.content{
padding:25px;
}

/* Logo */

.logo{
width:160px;
}

/* Semester */

.semester{
font-size:16px;
font-weight:bold;
margin-top:10px;
}

/* Date */

.date-nav{
text-align:center;
font-size:22px;
margin:20px 0;
}

.week-btn{
float:right;
margin-top:-30px;
}

/* Schedule Cards */

.card{
background:white;
padding:18px;
border-radius:10px;
margin-bottom:15px;
box-shadow:0 1px 3px rgba(0,0,0,0.08);
}

.card h4{
margin-top:0;
font-size:16px;
font-weight:bold;
}

.card p{
margin:3px 0;
color:#666;
}

</style>

</head>

<body>

<div class="container-fluid">

<div class="row">

<!-- Sidebar -->

<div class="col-sm-2 sidebar">

<div class="home-icon">
<span class="glyphicon glyphicon-home"></span>
</div>

<ul class="menu">

<li>Reports</li>
<li>Progress report</li>
<li>Assessments</li>
<li>Holidays</li>
<li class="active">Timetable</li>
<li>Teaching content</li>
<li>Leave</li>
<li>Services</li>

</ul>

</div>

<!-- Main Area -->

<div class="col-sm-10">

<div class="header">
<h4>Saveetha Engineering College (Autonomous)</h4>
</div>

<div class="content">

<div class="row">

<div class="col-sm-3 text-center">

<img src="Screenshot 2026-03-08 191716.png" class="logo">
</div>

<div class="col-sm-9">

<div class="semester">EVEN I 2025-2026</div>

<button class="btn btn-default week-btn">Weekly schedule</button>

<div class="date-nav">

<span class="glyphicon glyphicon-chevron-left"></span>

16 Mar 2026

<span class="glyphicon glyphicon-chevron-right"></span>

</div>

<!-- Schedule -->

<div class="card">

<h4>Fundamentals of Web Application Development (19AI414) (5452)</h4>

<p>10:00 AM - 11:00 AM (60 min) VIJAYAN P</p>

<p>5452</p>

<p><b>Attendance recorded</b></p>

</div>

<div class="card">

<h4>Fundamentals of Web Application Development (19AI414) (5452)</h4>

<p>11:00 AM - 12:00 PM (60 min) VIJAYAN P</p>

<p>5452</p>

</div>

<div class="card">

<h4>Python Programming (19AI301) (3653)</h4>

<p>1:00 PM - 2:00 PM (60 min) RAJE A</p>

<p>2331</p>

</div>

<div class="card">

<h4>Python Programming (19AI301) (3653)</h4>

<p>2:00 PM - 3:00 PM (60 min) RAJE A</p>
<p>2331</p>

<p><b>Attendance recorded</b></p>


</div>

</div>

</div>

</div>

</div>

</div>

</div>

</body>
</html>

```

## OUTPUT:

![alt text](image.png)

## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.

## HTML CODE:
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website - Academics</title>
</head>
<body>
    <header>
        <div class="container">
            <img src="C:\Users\nihil\Pictures\images.png" alt="College Logo">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="academics.html">Academics</a></li>
                    <li><a href="admission.html">Admission</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container">
        <section>
            <h2>Academics</h2>
            <p>The SNS Engineering College has an excellent academic coordination methodology which has evolved over a period of more than 17 years and 
                has been producing excellent results in terms of students pass percentage and university ranks.
                 
            </p>
            <ul>
                <li>Science
                    <ul>
                        <li><a href="courses/computer-science.html">Computer Science</a></li>
                        <li><a href="courses/mathematics.html">Mathematics</a></li>
                    </ul>
                </li>
                <li>Arts
                    <ul>
                        <li><a href="courses/english.html">English</a></li>
                        <li><a href="courses/sociology.html">Sociology</a></li>
                    </ul>
                </li>
                <li>Commerce
                    <ul>
                        <li><a href="courses/economics.html">Economics</a></li>
                        <li><a href="courses/business-management.html">Business Management</a></li>
                    </ul>
                </li>
            </ul>
        </section>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2024 SNS Engineering College. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
```
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website - Admission</title>
</head>
<body>
    <header>
        <div class="container">
            <img src="C:\Users\nihil\Pictures\images.png" alt="College Logo">
            <h1>SNS Engineering College</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="academics.html">Academics</a></li>
                    <li><a href="admission.html">Admission</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container">
        <section>
            <h2>Admission</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                
                <label for="course">Select Course:</label>
                <select id="course" name="course" required>
                    <option value="">--Select Course--</option>
                    <option value="Computer Science">Computer Science</option>
                    <option value="Mathematics">Mathematics</option>
                    <option value="English">English</option>
                    <option value="Sociology">Sociology</option>
                    <option value="Economics">Economics</option>
                    <option value="Business Management">Business Management</option>
                </select><br><br>
                
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>
                
                <input type="submit" value="Submit">
            </form>
        </section>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2024 SNS Engineering College. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
```
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website - Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <img src="C:\Users\nihil\Pictures\images.png" alt="College Logo">
            <h1>SNS Engineering College</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="academics.html">Academics</a></li>
                    <li><a href="admission.html">Admission</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container">
        <section>
            <h2>Gallery</h2>
            <div class="gallery">
                <img src="C:\Users\nihil\Pictures\WhatsApp_Image_2021-07-09_at_1.51.29_PM_1_1x.jpeg" alt="Gallery Image 1">
                <img src="C:\Users\nihil\Pictures\SNS_COLLEGE_OF_ENGINEERING_1x.jpg" alt="Gallery Image 2">
                <img src="C:\Users\nihil\Pictures\tre_2x_1x.png" alt="Gallery Image 3">
                <img src="C:\Users\nihil\Pictures\snsce_1x.jpeg" alt="Gallery Image 4">
            </div>
        </section>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2024 SNS Engineering College. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
```
```c
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Science Course</title>
</head>
<body>
    <header>
        <div class="container">
            <img src="C:\Users\nihil\Pictures\images.png" alt="College Logo">
            <nav>
                <ul>
                    <li><a href="../index.html">Home</a></li>
                    <li><a href="../academics.html">Academics</a></li>
                    <li><a href="../admission.html">Admission</a></li>
                    <li><a href="../gallery.html">Gallery</a></li>
                </ul>
            </nav>
            <h1>Computer Science</h1>
            <p>Embark on a journey of innovation and excellence with the Department of Computer Science and Engineering, a cornerstone of academic prowess of SNS Engineering College since its inception in 2001. What began with an intake of 60 students has evolved into a dynamic hub of learning, now accommodating 240 bright minds by the year 2023-24. Our commitment to growth is evident in our consistent expansion, from 120 students in 2005-2006 to 180 in 2017-18.
                At our department, we nurture talents through our esteemed B.E. and M.E. programs in Computer Science and Engineering. Guided by a team of 36 dedicated faculty members, comprising seasoned professionals with diverse expertise, we ensure a nurturing environment for academic excellence. Among them, 13 hold doctorates, while others are actively pursuing their Ph.D.s, embodying our commitment to staying at the forefront of research and knowledge.</p>
        <h2>FACULTY</h2>
        <ul>
            <label>Faulty Handling Various CS Department Subjects:</label>
            <li>Visak</li>
            <li>Ramya</li>
            <li>Ravindran</li>
            <li>Rekha</li>
        </ul>
        <html>
<head>
<title> TIME TABLE </title>   
</head>
<body>
<br>
<table align="center" width="1000" border="5" bgcolor="Lavender" cellspacing="12" cellpadding="12">
<caption><b>SLOT TIME TABLE</b></caption>

<tr bgcolor="CornflowerRed">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday </th>
</tr>
<tr align="center">
   <th bgcolor="CornflowerRed"> 8-10 </th>
   <td bgcolor="red"><b> Fundamentals Of Web Development Application</b></td>
   <td> Free Slot </td>
   <td bgcolor="lightgreen"><b>Problem sloving And Python Programming</b></td>
   <td> Free Slot </td>
   <td> Free Slot </td>
   <td> Free Slot </td>
</tr>
<tr align="center">
    <th bgcolor="CornflowerRed"> 10-12 </th>
    <td> Free Slot</td>
    <td bgcolor="yellow"><b>Parallel Computing Architecture</b></td>
    <td bgcolor="yellow"><b>Parallel Computing Architecture</b></td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td bgcolor="grey"><b>Programming in C</b></td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 12-1 </th>
    <th colspan="1">LUNCH</th>
    <th bgcolor="white" colspan="1">MENTOR MEET</th>
    <td colspan="6" align="center"><b>LUNCH</b></td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 1-3 </th>
    <td > Free SLOT </td>
    <td bgcolor="purple"><b>Intellectual Property Rights</b> </td>
    <td bgcolor="grey"><b> Programming in C</b> </td>
    <td bgcolor="red"><b> Fundamentals Of Web Development Application</b>
    <td bgcolor="red"><b> Fundamentals Of Web Development Application</b>
    <td bgcolor="pink"><b>Advanced Quantitative and Logical Reasoning</b> </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 3-5 </th>
    <td> Free Slot </td>
    <td bgcolor="lightgreen"><b>Problem Solving and Python Programming</b></td>
    <td bgcolor="purple"><b>Intellectual Property Rights</b></td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
</tr>
</tr>
</table>
<br>
<br>
<table align="center" border="8" cellspacing="12" cellpadding="12">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td bgcolor="lightgreen"> 1. </td>
<td bgcolor="lightgreen"> 19CS301 </td>
<td bgcolor="lightgreen">  Python Programming </td>
</tr>
<tr align="center">
<td bgcolor="red"> 2. </td>
<td bgcolor="red"> 19AI414 </td>
<td bgcolor="red">  Web Application Development </td>
</tr>
<tr align="center">
<td bgcolor="grey"> 3. </td>
<td bgcolor="grey"> 19CS302 </td>
<td bgcolor="grey"> Programming in C </td>
</tr>
<tr align="center">
<td bgcolor="yellow"> 4. </td>
<td bgcolor="yellow"> 19AI407 </td>
<td bgcolor="yellow"> Parallel Computing </td>
</tr>
<tr align="center">
<td bgcolor="purple"> 5. </td>
<td bgcolor="purple"> 19ME531 </td>
<td bgcolor="purple"> Intellectual Property Rights </td>
</tr>
<tr align="center">
<td bgcolor="pink"> 6. </td>
<td bgcolor="pink"> 19EY704 </td>
<td bgcolor="pink"> Advanced Quantitative  </td>
</tr>
</html>

            </div>
    </header>
```
## OUTPUT:
![image](https://github.com/nihilkrishnan/html-ABC-college/assets/118120621/fafd3647-2600-4620-8e79-b01def17f832)
![image](https://github.com/nihilkrishnan/html-ABC-college/assets/118120621/603fdf86-8a33-4c67-98a6-f13f80d933af)
![image](https://github.com/nihilkrishnan/html-ABC-college/assets/118120621/0f023978-a39f-45ba-aaf9-79e4959e8d78)
![image](https://github.com/nihilkrishnan/html-ABC-college/assets/118120621/eac1760e-73c0-4d72-b048-9ceef6ddde85)





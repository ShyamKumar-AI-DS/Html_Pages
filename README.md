# 1.html-ABC-college

1. Design a website for a College. There should be at least 15 web-pages present in the web-site.

## Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Page</title>
</head>
    <body style="background-color: rgb(179, 240, 240); background-blend-mode: color;">
        <hr>
        <img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" alt="Logo" style="width: 50%; height: 2%; padding-left: 25%;">
        <hr>
        <h1 style="text-align: center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; position: static;color: rgb(0, 146, 195)">
            Saveetha Engineering College
        </h1>
        <hr>
        <table style="align-content: center;">
            <tr>
                <th style="padding-left: 50%; font-size: larger; font-size: 250%;"> <a href="HomePage.html" target="_blank"> 
                    <ol>
                        <li style="list-style-type: georgian;">Home</li>
                    </ol>
                 </a></th>

                <th style="padding-left: 200%; font-size: larger; font-size: 250%;"> <a href="AdmissionPage.html" target="_blank"> 
                    <ol>
                        <li style="list-style-type: georgian;">Admission</li>
                    </ol>
                 </a></th>
            </tr>
            <br>
            <br>
            <br>
            <br>
            <tr style="margin: 1px;">
                <th style="padding-left: 50%; font-size: larger; font-size: 250%;"><a href="AcadamicsPage.html" target="_blank"> 
                    <ol>
                        <li style="list-style-type: georgian;">Acadamics</li>
                    </ol>
                </a></th>
                <th style="padding-left: 200%; font-size: larger; font-size: 250%;"><a href="GalleryPage.html" target="_blank"> 
                    <ol>
                        <li style="list-style-type: georgian;">Gallery</li>
                    </ol>
                </a></th>
            </tr>
        </table>
        <footer style="text-align: center; padding-top: 1%; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; 
        font-size: 200%; color: rgb(0, 146, 195);"> 
        <hr>
            <b> Contact : +91 123456789 <br>E-mail : Saveethaxyz@gmail.com </b>
        <hr>
        </footer>
    </body>
</html>
```
## Academics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics - ABC College</title>
</head>
<body style="background-color: rgb(179, 240, 240); background-blend-mode: color;">
    <hr>
    <img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" alt="Logo" style="width: 50%; height: 2%; padding-left: 25%;">
    <hr>
    <h1 style="text-align: center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; position: static;color: rgb(0, 146, 195)">
        Saveetha Engineering College
    </h1>
    <hr>
    <div class="container">
        <h2 style="color: #383f40; font-size: 250%;">Admission Form</h2>
        <ul>
            <li style="font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
            ; font-size: larger;">Science
                <ul>
                    <li><a href="courses/ComputerScience.html">Computer Science</a></li>
                    <li><a href="courses/mathematics.html">Mathematics</a></li>
                </ul>
            </li>
            <li style="font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
            ; font-size: larger;">Arts
                <ul>
                    <li><a href="courses/english.html">English</a></li>
                    <li><a href="courses/sociology.html">Sociology</a></li>
                </ul>
            </li>
            <li style="font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
            ; font-size: larger;">Commerce
                <ul>
                    <li><a href="courses/economics.html">Economics</a></li>
                    <li><a href="courses/business-management.html">Business Management</a></li>
                </ul>
            </li>
        </ul>
    </div>
    <footer style="text-align: center; padding-top: 1%; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; 
    font-size: 200%; color: rgb(0, 146, 195);"> 
    <hr>
        <b> &copy; Saveetha engineering college. All rights reserved.</b>
    <hr>
</footer>
</body>
</html>
```
## Admission.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission Page</title>
</head>
<body style="background-color: rgb(179, 240, 240); background-blend-mode: color;">
    <hr>
        <img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" alt="Logo" style="width: 50%; height: 2%; padding-left: 25%;">
        <hr>
        <h1 style="text-align: center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; position: static;color: #383f40">
            Saveetha Engineering College
        </h1>
        <hr>
    <div class="container">
        <h2 style="color: #383f40; font-size: 250%;">Admission Form</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <br>
            <br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br>
            <br>
            <label for="course">Course:</label>
            <select id="course" name="course">
                <option value="computer-science">Computer Science</option>
                <option value="mathematics">Mathematics</option>
                <option value="english">English</option>
                <option value="sociology">Sociology</option>
                <option value="economics">Economics</option>
                <option value="business-management">Business Management</option>
            </select>
            <br>
            <br>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4"></textarea>
            <br>
            <br>
            <input type="submit" value="Submit">
        </form>
    </div>
    <footer style="text-align: center; padding-top: 1%; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; 
        font-size: 200%; color: rgb(0, 146, 195);"> 
        <hr>
            <b> &copy; Saveetha engineering college. All rights reserved.</b>
        <hr>
    </footer>
</body>
</html>
```
## Gallery.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
</head>
    <body style="background-color: rgb(150, 240, 240);">
        <hr>
        <img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" alt="Logo" style="width: 50%; height: 2%; padding-left: 25%;">
        <hr>
        <h1 style="text-align: center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; position: static;color: #383f40;">
            Saveetha Engineering College
        </h1>
        <hr>
    <h2 style="text-align: center; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: 250%;color: #383f40;">Gallery</h2><hr>
    <img src="https://images.squarespace-cdn.com/content/v1/5f8a85fc2ad7a514c3fdaf60/1603593971445-SX52H8823WGBI2RT3P11/building_2.jpg?format=750w" 
        alt="Picture" style="width: 600px; height: 400px; padding-right: 5%; padding-left: 5%;">
        <img src="https://images.squarespace-cdn.com/content/v1/5f8a85fc2ad7a514c3fdaf60/1603591594705-ALQ9EZ3CKT50WUA2REBX/1581681661phpp04qVD.jpeg?format=500w" 
            alt="Picture" style="width: 600px; height: 400px ;padding-left: 5%;">
    </body>
</html>
```
## Computer-science.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CS Course Page</title>
</head>
    <body style="background-color: rgb(179, 240, 240); background-blend-mode: color;"></body>
        <hr>
        <img src="https://www.saveetha.ac.in/images/WEB_LOGO-01.png" alt="Logo" style="width: 50%; height: 2%; padding-left: 25%;">
        <hr>
        <h1 style="text-align: center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; position: static;color: rgb(0, 146, 195)">
            Saveetha Engineering College
        </h1>
        <hr>
        <h2 style="color: #383f40; text-align: center; font-size: 150%; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif">Computer Science</h2>
        <img src="https://www.saveetha.ac.in/images/sec/2020/depts/cse/future-artificial-intelligence-robot-cyborg.gif" alt="Picture" 
        width="500px" height="300px" style="padding-left: 500px;">
        <p style="font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: large;">To pursue our vision by striving for excellence in creating, applying, and imparting knowledge in Computer Science and Engineering.
            To pursue comprehensive educational system, research in collaboration with industry and government and to disseminate knowledge through scholarly publications.
            To provide service through professional societies to the community, the state, and the nation.</p>
    </body>
</html>
```

## Output
![HomePage](https://github.com/ShyamKumar-AI-DS/html-ABC-college/assets/93427182/513d4673-628b-4549-80a5-bdd8c9a44aaf)
<br>
![Gallery Page](https://github.com/ShyamKumar-AI-DS/html-ABC-college/assets/93427182/eb30233e-bc97-44e1-ac89-ba8f662c765d)
<br>
![CS Course Page](https://github.com/ShyamKumar-AI-DS/html-ABC-college/assets/93427182/5e09495a-81a2-4131-98ef-c425b8bbc7fc)
<br>
![Admission Page](https://github.com/ShyamKumar-AI-DS/html-ABC-college/assets/93427182/cb03df58-4094-43f5-91fb-c8ebc53fd205)
<br>
![Acadamics Page](https://github.com/ShyamKumar-AI-DS/html-ABC-college/assets/93427182/2c4fb583-da4b-434c-b565-fbf05b541851)
<br>
![Index Page](https://github.com/ShyamKumar-AI-DS/html-ABC-college/assets/93427182/dc1a8f7b-d255-47eb-9076-f79c514c2622)
<br>

# 2.Prepare a html file to display the contents as seen in the following image.
![image](https://github.com/ShyamKumar-AI-DS/html-ABC-college/assets/93427182/c428f10f-2476-4a4b-9a60-162b10b026ae)
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My Day</title>
    </head>
    <body style="align-items:center;">
    <table cellpadding= "10" cellspacing="10" style="border-style: double;">
        <tr>
            <th colspan="2" class="center" style="border-style: double;"><mark>My Day</mark></th>
        </tr>
        <tr>
            <td style="border-style: double;">
                <ol>
                    <li>wake up early
                    <ul>
                        <li style="list-style-type: square; margin-bottom: 20px">5AM</li>
                        <li>walk</li>
                        <li>jog</li>
                    </ul>
                    </li>
                </ol>
            </td>
            <td rowspan="3" style="border-style: double;">
    <table>
        <tr>
            <th colspan="2" class="center highlight" style="border-style: double;"><mark>Things to watch</mark></th>
                </tr>
        <tr >
            <td style="border-style: double;"><img src="joggingg.png" alt="image 1" width="100" height="100" >
            <td style="border-style: double;"><img src="break.jpeg" alt="image 2" width="100" height="100">
        </tr>
        <tr>
            <td style="border-style: double;"><img src="tea.jpeg" alt="image 3" width="100" height="100">
            <td style="border-style: double;"><img src="group.jpeg" alt="image 4" width="100" height="100">
        </td>

        </tr>
        <tr>
        </tr>
    </table>
            <tr>
                <td style="border-style: double;">
                    <ol start="2">
                        <li>breakfast
                            <ul>
                                <li style="list-style-type: square; margin-bottom: 20px">8AM</li>
                                <li>eggs</li>
                                <li>coffee</li>
                            </ul>
                        </li>
                    </ol>
                </td>
            </tr>
            <tr>
                <td style="border-style: double;">
                    <ol start="3">
                        <li>go to Saveetha
                        <ul>
                            <li style="list-style-type: square; margin-bottom: 20px">8AM</li>
                            <li>attend classes</li>
                            <li>to be continued</li>
                        </ul>
                        </li>
                    </ol>
                </td>
            </tr>
    </table>
    </body>
</html>
```
## OUTPUT
![Q1 Img](https://github.com/ShyamKumar-AI-DS/html-ABC-college/assets/93427182/dcf320fb-048c-4e6c-9a42-287f0a6a0685)







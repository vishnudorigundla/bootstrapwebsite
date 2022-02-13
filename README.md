# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### Home Page:-
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</head>
<body>
    <div class="container-fluid">
        <div class="page-header text-center bg-primary ">
            <h2>Bureau of Police Research and Development</h2>
        </div>
        <div>
            <img class="img-thumbnail" src="head.png" width="2000px">
        </div>
        <div class="navbar navbar-dark bg-dark">
            <div class="nav-item col-md-4 text-center text-decoration-underline ">
                <a class="nav-link" href="./home.html" aria-current="page">home</a>
            </div> 
            <div class="nav-item col-md-4 text-center ">
                <a class="nav-link" href="./gallery.html">Gallery</a>
            </div>
            <div class="nav-item col-md-4 text-center">
                <a class="nav-link" href="./aboutus.html" >Aboutus</a>
            </div> 
        </div>
        <div class="row text-center">
            <div class="col-md-2 ">
                <table class="table table-bordered">
                    <thead>
                        <tr><th>Events</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Investigative Workflow on cybersecurity</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Data of Police organisation</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Bureau Darpan</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Police Aur Seva</th></tr>
                    </thead>
                    
                </table>
            </div>
            <div class="col-md-8">
                <img class="img img-thumbnail" src="hm.png" height="500px" width="500px">
            </div>
            <div class="col-md-2">
                <img class="img img-thumbnail" src="ge.png">
                <h3>Director General</h3>
            </div>
        </div>
    </div>
</body>
</html>
~~~

### Gallery page :-
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</head>
<body>
    <div class="container-fluid">
        <div class="page-header text-center bg-primary ">
            <h2>Bureau of Police Research and Development</h2>
        </div>
        <div>
            <img class="img-thumbnail" src="head.png" width="1200px">
        </div>
        <div class="navbar navbar-dark bg-dark">
            <div class="nav-item col-md-4 text-center">
                <a class="nav-link" href="./home.html" aria-current="page">home</a>
            </div> 
            <div class="nav-item col-md-4 text-center text-decoration-underline">
                <a class="nav-link" href="./gallery.html">Gallery</a>
            </div>
            <div class="nav-item col-md-4 text-center ">
                <a class="nav-link" href="./aboutus.html" >Aboutus</a>
            </div> 
        </div>
        <div class="row">
            <div class="col-md-3">
                <table class="table table-bordered">
                    <thead>
                        <tr><th>PhotoGallery</th></tr>
                    </thead>
                    <thead>
                        <tr><th>National Conference</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Foundation Day</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Attachements of IPS officier</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Third National Conference</th></tr>
                    </thead>
                </table>
            </div>
            <div class="col-md-9 text-center">
                <h3>National Conference-Images</h3>
                <img class="img-responsive" style="height: 200px; width:800px;"src="ga.png">
            </div>
        </div>
    </div>
</body>
</html>
~~~

### About Us :-
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</head>
<body>
    <div class="container-fluid">
        <div class="page-header text-center bg-primary ">
            <h2>Bureau of Police Research and Development</h2>
        </div>
        <div>
            <img class="img-thumbnail" src="head.png" width="2000px">
        </div>
        <div class="navbar navbar-dark bg-dark">
            <div class="nav-item col-md-4 text-center">
                <a class="nav-link" href="./home.html" aria-current="page">home</a>
            </div> 
            <div class="nav-item col-md-4 text-center">
                <a class="nav-link" href="./gallery.html">Gallery</a>
            </div>
            <div class="nav-item col-md-4 text-center text-decoration-underline">
                <a class="nav-link" href="./aboutus.html" >Aboutus</a>
            </div> 
        </div>
        <div class="row">
            <div class="col-md-3">
                <table class="table table-bordered">
                    <thead>
                        <tr><th>Abouts us</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Evolution of BPRD</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Awards/Medals</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Work Allocation</th></tr>
                    </thead>
                    <thead>
                        <tr><th>organisation</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Draft Legislation</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Contact Us</th></tr>
                    </thead>
                    <thead>
                        <tr><th>Citizens Corner</th></tr>
                    </thead>
                </table>

            </div>
            <div class="col-md-9 text-center" style="padding-right: 10px;">
                <h3>About us:</h3>
                <h4>Evolution of BPRD:</h4>
                <br>
                1. The Government of India vied Resolution No.8/136/68-P.I (Pers.I) dated 28.08.1970 formally established the Bureau of Police Research and Development (BPR&D), under the Ministry of Home Affairs giving a new orientation to then existing Police Research and Advisory Council (1966) for the following reasons and with the primary objective of modernization of police force:

1.    To take direct and active interest in the issues

2.    To promote a speedy and systematic study of the police problems,

3.    To apply science and technology in the methods and techniques used by police.

In addition and as a secondary, the Resolution mandated an advisory role also for the Bureau.

2. The Bureau was established with the following two divisions initially with a well laid out charter of duties

1.    Research, Statistics and Publication

2.    Development

3. Training is a vital and growing requirement to improve the competency of police forces in the country. 
The Gore-Committee (1971) set up by the Government of India studied the training aspects of police and gave 
several recommendations. The government of India in accepting its recommendations created a Training Division
(1973) in addition to the two divisions already existing to function under the Bureau.

4. The forensic science services uncompromising & Geese under the Development Division grew over a period and a 
separate Directorate of Forensic Sciences under the BPR&D came into existence in 1983.

5. Further in 1995 Government of India decided to entrust issues relating to Correctional Administration Work to 
the BPR&D so that problems relating to prisons and implementation of deemed prison reforms can be taken up by the
 Bureau in a cohesive manner. This set up is operating out of the existing manpower resources.

6. During the year 2008, the Government of India further decided to create National Police Mission under the
 administrative control of BPR&D to transform the police forces in the country into effective instrument for 
 maintenance of internal security and facing the challenges in future, by equipping them with the necessary
 material, intellectual and organizational resources.

            </div>
        </div>
    </div>
</body>
</html>
~~~


## OUTPUT:-
Home :
![OUTPUT](/image/image1.png)
Gallery:
![OUTPUT](/image/image2.png)
About us :
![OUTPUT](/image/image3.png)
## Result:
The codes are successfully excuted to create a webpage by using bootstrap.

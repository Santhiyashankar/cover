# Ex.06 Book Front Cover Page Design
## Date:29.11.23

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```

<style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:lightsteelblue;
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(/static/background1.jpeg);
        background-size: cover;
    }
        
    
    .insight{
        color: palegreen;
    
    }
    
    
    .hrstyle{
        width:100px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: lightcoral;
        top:160px;
        
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 30px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:175px;
        
    }
    .pub{
        font-size: medium;
        position: relative;
        top:135px;
        left:330px;
    }
    .ed{
        color: lightpink;
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:80px;
    
    }
    .subtitle{
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:40px;
    }
    .mypic{
        position: relative;
        top: 120px;
        left: 260px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
        <br>
        <br>

    <div class="bookpage">
        <div class="insight">
            INSIGHT EXPERIENCE
        </div>
        <div class="hrstyle">
            <hr style="color: olive;">
        </div>
        
        <div class="booktitle">
            <h1>MANAGING INFORMATION TECHNOLOGY</h1></div>
        <div class="subtitle">
            <ul>
            <l1><b>Technical Management</b></l1>
            <l2><b>IT operation Management</b></l2>
            </ul>
        
        </div>
        <br>
        <br>
        <div class="mypic">
            <img src="/static/image1.jpg" width="130" height="145" alt="">
        </div>
    
        <div class="id">
        
        
        
            <hr style="color: goldenrod;">
        
        </div>
        <div class="author">
        
           <p><b>SANTHIYA.S</b></p>
        
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            
            <b>Third Edition</b>
        </div>
    </div>
</br>
</br>
</br>
</br>

    </body>
</html>
```

## OUTPUT:
![Alt text](<Screenshot (139).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

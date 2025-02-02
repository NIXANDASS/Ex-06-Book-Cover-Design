# Ex-06-Book-Cover-Design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the Github respository and create a Django admin interface.

### Step 2:
Write HTML and CSS Code for designing book cover page and execute them.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>
        .bookpage{
            width: 420px;
            height: 600px;
            color:rgb(245, 76, 9);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/luff.jpg);
            background-size: cover;
        }
            
        .insight{
            color: rgb(236, 240, 3);
        }
        
        .hrstyle{
            width:100px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color: rgb(3, 3, 3);
            top:190px;
            
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
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(255, 115, 0);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>COVER PAGE DESIGN</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(0, 0, 0);">
            </div>
            <div class="booktitle" style="color: rgb(255, 64, 0);">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle" style="color: rgb(247, 255, 6);"><b>
                HTML and CSS Combined with Django Architecture</b>
            </div>
            <div class="mypic" >
                <img src="/static/images/DSC_3162.jpg" width="60" height="100" alt="" style="vertical-align:bottom;margin:50px 55px">
            </div>
            <div class="id">
                <hr style="color: rgb(255, 0, 0);">
            </div>
            <div class="author">
               <p><b>A NIXAN DASS</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## Output:
![o1](https://user-images.githubusercontent.com/118781418/215206892-0eb20291-256c-4be1-aeea-e1de988b8cda.png)
![VALID2](https://user-images.githubusercontent.com/118781418/215207405-ac2d0a63-0999-4e3a-9627-53a93604d7a5.png)


## Result:
The program for designing book cover page using HTML and CSS is executed.

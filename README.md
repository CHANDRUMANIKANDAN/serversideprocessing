# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

## Step 1:

Clone into the repository named 'serversideprocessing' and create a project named 'myproj'.
## Step 2:

Startapp 'myfirstapp'.Create a folder named 'templates' under which all html files are stored.
## Step 3:

Make the necessary changes in the settings.py and add codes in urls.py and views.py which enables the operation to take place.
## Step 4:

Under templates and myfirstapp, create a html file named math.html and write the required html code for the website.
## Step 5:

Push to the github.
## Step 6:

Publish the website in the given URL

Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            www.volume.html
        </title>
    </head>
<style>
    *{
        box-sizing: border-box;
         }

    body{
    background-color;
    color: black;
    }

   .container{
    width: 1080px;
    height: 350px;
    margin-top: 100px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 25px;
    border: 10px solid black;
    
    
    }
    h1{
        color: rgb(0, 0, 0);
        text-align: center;
    }
    .calculate{
        padding-top: 10px;
        padding-bottom: 10px;
        padding-left: 10px;
        padding-right:10px;
        text-align: center;
        font-size: 20px;
        padding-top: 7px;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
</style>
    <body>
        <div class="container">
        <h1>TO CALCULATE AREA OF RECTANGLE</h1>
        <form method="POST">
            {% csrf_token %}
            <div class="calculate"> 
                Height:<input type="text" name="height" value={{h}}></input><br/>
            </div>
            <div class="calculate">
                length:<input type="text" name="length" value={{l}}></input><br/>
            </div>
            
            <div class="calculate">
                <input type="submit" value="Calculate area"></input><br/>
            </div>
            <div class="calculate">
                area:<input type="text" name="area" value={{volume}}></input>
            </div>
        </form>
    </div>
    </body>
</html>
```

## OUTPUT:

### Home Page:
![Screenshot (5)](https://github.com/CHANDRUMANIKANDAN/serversideprocessing/assets/118644502/b970edab-3d26-4e50-927d-31758f1ac035)



## Result:
thus the experiment was executed successfully.


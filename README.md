# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts


### Step 3:
Use CSS for creating attractive colors.


### Step 4:
Write JavaScript program for implementing five different operations.


### Step 5:
Validate the HTML,CSS javascript code.


### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
NAME:G.R.NANDHAKUMAR
REG NO:212222100029
```
```html
<!DOCTYPE html>
<html>
    <head>
        <title>NANDHA'S CALCULATOR</title>
        <style type="text/css">
        table{
            border: 1px solid black;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 1px solid black;
            padding: 20px 30px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color:rgb(137, 18, 206);
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:darkmagenta;">NANDHA'S CALCULATOR</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"/></td>
                <td><input type="button" value="2" onclick="result.value+='2'"/></td>
                <td><input type="button" value="3" onclick="result.value+='3'"/></td>
                <td><input type="button" value="+" onclick="result.value+='+'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"/></td>
                <td><input type="button" value="5" onclick="result.value+='5'"/></td>
                <td><input type="button" value="6" onclick="result.value+='6'"/></td>
                <td><input type="button" value="-" onclick="result.value+='-'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"/></td>
                <td><input type="button" value="8" onclick="result.value+='8'"/></td>
                <td><input type="button" value="9" onclick="result.value+='9'"/></td>
                <td><input type="button" value="*" onclick="result.value+='*'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="clearall" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```

## OUTPUT:
## SERVER OUTPUT
![servercalci png](https://github.com/Nandhakumar1313/standard-calculator/assets/120230694/b096394d-eb44-4502-9224-87451416d2fa)

## CLIENT OUTPUT
![calci png](https://github.com/Nandhakumar1313/standard-calculator/assets/120230694/081598ae-59a3-4e2b-a4a7-9a062838d1a5)

## Result:
The program for implementing simple calculator using HTML, CSS and JavaScript is executed successfully.


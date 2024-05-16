# Ex.08 Design of a Standard Calculator
## Date:
## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
    <head>
        <title> Standard Calculator</title>
        <title> HARIHARAN A (212223110013) </title>
        <style>
        
        table{
            border: 10px solid rgb(6, 73, 100);
            margin-left: auto;
            margin-right: auto;
        
        }
        input[type="text"]{
            border: 5px solid cyan;
            padding: 20px 30px;
            font-size: 30px;
            font-weight: italic;
            border-radius: 3px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color: rgba(185, 12, 12, 0.825);
            border-radius: 3px;
            font-size: x-large;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:rgb(10, 10, 10);">Standard Calculator</h1>
            <h2 style="text-align: center;color:rgb(205, 9, 68);">HARIHARAN A (212223110013) </h2>

        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"></td>
                <td><input type="button" value="2" onclick="result.value+='2'"></td>
                <td><input type="button" value="3" onclick="result.value+='3'"></td>
                <td><input type="button" value="+" onclick="result.value+='+'"></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"></td>
                <td><input type="button" value="5" onclick="result.value+='5'"></td>
                <td><input type="button" value="6" onclick="result.value+='6'"></td>
                <td><input type="button" value="-" onclick="result.value+='-'"></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"></td>
                <td><input type="button" value="8" onclick="result.value+='8'"></td>
                <td><input type="button" value="9" onclick="result.value+='9'"></td>
                <td><input type="button" value="*" onclick="result.value+=''"></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"></td>
                <td><input type="button" value="0" onclick="result.value+='0'"></td>
                <td><input type="button" value="." onclick="result.value+='.'"></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="C" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
   </body>
</html>

```

## OUTPUT:
![d885d4db-553e-4e8e-8b2f-9f4358fe813c](https://github.com/swethasurendar/Calc/assets/133625914/de18a7a6-fc2e-407c-9412-3cdef32bc2c3)
![9d57a0a3-8b58-466f-ace0-0721cb6cef49](https://github.com/swethasurendar/Calc/assets/133625914/6fc077f4-af07-4033-af5f-1cd195e341e9)



## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.

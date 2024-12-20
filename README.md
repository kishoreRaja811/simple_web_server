# EX01 Developing a Simple Webserver

# Date:14/11/2024
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>laptop configuration</title>
</head>
<style>
    body{
        background-color: azure;
    }
    header{
        background-color: azure;
        color: rgb(53, 9, 156);
        padding: 20px 0;
        font-family: Georgia, 'Times New Roman', Times, serif;
    }
    table{
        background-color: rgb(226, 220, 245);
        border-collapse: collapse;
        box-shadow: 0;
        margin: 20px;
        text-align: center;
    }

</style>
<body>
    <center>

        <header>
            <h1 style="font-size: 350%;">LAPTOP CONFIGURATION</h1>
        </header>

    <table border="4px" width="600" height="400">
        <div class="heading">
        <tr style="font-size: x-large;">
            <th>S.NO</th>
            <th>COMPONENTS</th>
            <th>DETAILS</th>
        </tr>
        </div>
        <tr>
            <th>1</th>
            <th style="font-style: oblique;">PROCESSOR(CPU)</th>
            <td style="font-style: oblique;">13th Gen i5-1335U</td>
        </tr>
        <tr>
            <th>2</th>
            <th style="font-style: oblique;">MEMORY(RAM)</th>
            <td style="font-style: oblique;">16.0 GB</td>
        </tr>
        <tr>
            <th>3</th>
            <th style="font-style: oblique;">STORAGE</th>
            <td style="font-style: oblique;">512GB SSD</td>
        </tr>
        <tr>
            <th>4</th>
            <th style="font-style: oblique;">DISPLAY</th>
            <td style="font-style: oblique;">15.6-inch Full HD (1920x1080)</td>
        </tr>
        <tr>
            <th>5</th>
            <th style="font-style: oblique;">GRAPHICS(GPU)</th>
            <td style="font-style: oblique;">Integrated Intel UHD</td>
        </tr>
        <tr>
            <th>6</th>
            <th style="font-style: oblique;">BATTERY</th>
            <td style="font-style: oblique;">45 Wh, Up to 8 hours</td>
        </tr>
        <tr>
            <th>7</th>
            <th style="font-style: oblique;">OPERATING SYSTEM</th>
            <td style="font-style: oblique;">Windows 10 Home</td>
        </tr>
    </table>
    </center>
</body>
</html>. 
```
# OUTPUT:
![alt text](<Screenshot 2024-12-07 082735.png>)

![alt text](<Screenshot 2024-12-07 082813.png>)
# RESULT:
The program for implementing simple webserver is executed successfully.

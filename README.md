<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="tabl.css">
    <script type="text/javascript" src="tabl.js">

    
    </script>
    <title> Zebra striping a table | </title>
</head>
<body>
    <table id ="t1" border=" 4"> 
        <thead class = "zbr">
            
                <th>  Name </th>
                <th> Bounces </th>
            
        </thead>

        <tr>
            <td>Tendai</td>
            <td>7</td>
         </tr>

         <tr class = "zbr "> 
            <td>Kudzai</td>
            <td>13</td>
         </tr>

         <tr>
            <td>Taurai</td>
            <td>3</td>
         </tr>

         <tr class =" zbr"> 
            <td>Nyika</td>
            <td>1000</td>
         </tr>

    </table>
<br>    
    <table id="T2" border="9">
        <thead class="zbr">
          <th>Name</th>
          <th>Favourite Dish</th>
        </thead>

        <tr>
            <td>Tendai</td>
            <td>Sadza Madora</td>
        </tr>

        <tr class="zbr">
            <td>Kudzai</td>
            <td>Sadza Chicken</td>
        </tr>

        <tr>
            <td>Taurai</td>
            <td>Gango</td>
        </tr>
    </table>
</br>

<button onclick="myFuction()">CHANGE</button>
</body>
</html>

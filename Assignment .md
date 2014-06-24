##Assignment 3##

I have placed the below code to test the database connectivity from my cs2 server

```php
<?php
$con=mysqli_connect("localhost","akalaru","akhima97971","akalaru");
// Check connection
if (mysqli_connect_errno()) {
  echo "Failed to connect to MySQL: " . mysqli_connect_error();
}

$result = mysqli_query($con,"SELECT * FROM Plantes");

echo "<table border='1'>
<tr>
<th>Name</th>
<th>NumMoons</th>
<th>Type</th>
<th>LengthOfYear</th>
</tr>";

while($row = mysqli_fetch_array($result)) {
  echo "<tr>";
  echo "<td>" . $row['Name'] . "</td>";
  echo "<td>" . $row['NumMoons'] . "</td>";
  echo "<td>" . $row['Type'] . "</td>";
  echo "<td>" . $row['LengthofYear'] . "</td>";
  echo "</tr>";
}

echo "</table>";

mysqli_close($con);
?>


```

I have the below mentioned link to test the database connectivity

```
http://cs2.mwsu.edu/~akalaru/DBTesting/DBTest.php

```

I have got the below mentioned output from the database


Name	NumMoons	Type	LengthOfYear
Mercury	0	Rocky	0.24

Venus	0	Rocky	0.62

Earth	1	Rocky	1

Mars	2	Rocky	1.88

Jupiter	16	Gas	11.86

Saturn	18	Gas	29.46

Pluto	1	Rocky	247.7


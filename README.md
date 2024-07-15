<?php 
$arr1 = array("Geeks", "g4g"); 
$arr2 = array("GeeksforGeeks", "Computer science portal"); 
  
// Get the merged array in the first array itself. 
$arr1 = array_merge($arr1, $arr2);  
  
echo "arr1 Contents:"; 
  
// Use for each loop to print all the array elements. 
foreach ($arr1 as $value) { 
    echo $value . "\n"; 
} 
?> 

# PHP-Essentials-Bootcamp
Assignment - PHP Essentials Bootcamp

<?php
function findLargest($num1, $num2, $num3) {
    $largest = $num1;

    if ($num2 > $largest) {
        $largest = $num2;
    }

    if ($num3 > $largest) {
        $largest = $num3;
    }

    return $largest;
}

// Test the function
$number1 = 10;
$number2 = 25;
$number3 = 15;

$largestNumber = findLargest($number1, $number2, $number3);
echo "The largest number is: " . $largestNumber;
?>

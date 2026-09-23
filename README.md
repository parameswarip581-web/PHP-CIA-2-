# PHP-CIA-2-
Program 2
<?php

$name = "Ravi";
$birthYear = 2000;
$currentYear = 2026;
$retirementAge = 60;

$age = $currentYear - $birthYear;
$remainingYears = $retirementAge - $age;

echo "Employee Name: " . $name;
echo "<br>Birth Year: " . $birthYear;
echo "<br>Current Age: " . $age;

if ($remainingYears > 0) {
    echo "<br>Remaining Years for Retirement: " . $remainingYears;
} else {
    echo "<br>Employee has reached retirement age.";
}

?>
Output 
Employee Name: Ravi
Birth Year: 2000
Current Age: 26
Remaining Years for Retirement: 34

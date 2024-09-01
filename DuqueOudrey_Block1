<?php
class Person {
    public $firstName;
    public $lastName;
    private $age;

    public function __construct($firstName, $lastName, $age) {
        $this->firstName = $firstName;
        $this->lastName = $lastName;
        $this->age = $age;
    }

    public function getFullName() {
        return $this->firstName . ' ' . $this->lastName;
    }

    public function getAge() {
        return $this->age;
    }
}

class Car {
    public $make;
    public $model;
    protected $year;

    public function __construct($make, $model, $year) {
        $this->make = $make;
        $this->model = $model;
        $this->year = $year;
    }

    public function getCarInfo() {
        return $this->make . ' ' . $this->model . ' (' . $this->year . ')';
    }
}

$person = new Person("Oudrey", "Duque", 19);
$car = new Car("Porche", "911", 1983);

echo "Full Name: " . $person->getFullName() . "\n";
echo "Age: " . $person->getAge() . "\n";
echo "Car Info: " . $car->getCarInfo() . "\n";

?>

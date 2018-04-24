# Lecture 5 : PHP & MySQL
## How to create a MySQL connection?
```php
<?php
$servername = "localhost";
$username = "username";
$password = "password";

$conn = new mysqli($servername, $username, $password);

if($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
echo "Connected successfully";

```

## How to send query to database?
```php
<?php
$query = "SELECT * FROM mydb";
$success = $mysqli_query($conn, $query);
if($success) {
    echo "Query successfully passed into database";
}
```


## How to use prepared statements?
```php
<?php
// prepare and bind
$stmt = $conn->prepare("INSERT INTO people (name, age) VALUES (?, ?)");
$stmt->bind_param("si", $name, $age); // s means string, i means integer

// set parameters and execute
$name = "John";
$age = 39;
$stmt->execute();
```
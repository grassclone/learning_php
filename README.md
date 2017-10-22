# learning_php

<?php ?>
(you can omit closing tag when its only PHP. However if there's something else (like html) you have to include it.

### variables

$greeting = 'hello';
echo $greeting;
----
$name = "Nicholas Daniel";
echo "Hello, " . $name;
echo "Hello, {$name}";

### php and html

<?php
  $name = $_GET['name'];
  echo $name;
  
?>

localhost:8888/learning_php?name=Nick // key -> value

<?php echo ... ?> -> <?= ... ?>

### including a file in another file

require 'index.view.php';

### loop an array

$names = ['Nick', 'Cy', 'Glue'];
foreach($names as $name) {
  echo $name;
}

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

# learning_php


### variables

```php
$greeting = 'hello';
echo $greeting;
```
```php
$name = "Nicholas Daniel";
echo "Hello, " . $name;
echo "Hello, {$name}";
```

### php and html

```php
<?php
  $name = $_GET['name'];
  echo $name;
?>
```

__localhost:8888/learning_php?name=Nick // key -> value

```php
<?php echo ... ?> -> <?= ... ?>
```

### including a file in another file

```php
require 'index.view.php';
```

### loop an array

```php
$names = ['Nick', 'Cy', 'Glue'];
foreach($names as $name) {
  echo $name;
}
```


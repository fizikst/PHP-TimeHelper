Php TimeHelper class
==============

Php class helper for formatting datetime

Download file and install
-----------
```php
<?php
  include_once('TimeHelper.php');
?>
```

Or use composer
-----------
```json
{
	"repositories": [
		...
        {
            "type": "git",
            "url": "https://github.com/korytoff/PHP-TimeHelper.git"
        }
    ],
    "require": {
    	...
        "korytoff/timehelperf": "*"
    },
}
```

```bash
$ php composer.phar update
```

Use
-----------
```php
<?php
  echo TimeHelper::create('2014-11-07 22:12:00')->today(); // Сегодня, Завтра, Вчера или 14 сентября 2015 г.
?>
```

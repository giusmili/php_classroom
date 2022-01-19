---
title: Cours php
tags: support, php, good practice
robots: noindex, nofollow
author: Giuseppe Militello
---

![logo php](./asset/php_8_released.png)
# Comment mettre en place une navigation dynamique par PHP
Pour commencer vous devez cloner ce ripository en local

```php
<?php
    class Page{
        public $_title = "PHP : Create navigation by get";
        static $_css = "./css/main.css"; /* static propertie */
        public $_lang = "fr";
    }

    $_newTitle = new Page;
    $_newLang = new Page;

?>
```
&copy;  [Giuseppe Militello](https://www.linkedin.com/in/giuseppe-militello-22406ab0/) - All rights reserved for educational purposes only
#Anti-MSIE (jQuery Popup)

Anti Microsoft Internet Explorer is jQuery Popup To Stop The Use IE Browers

## How to Install

1) Copy src/anti-msie folder on your website

2) Add script and jquery before `</body>`:
```php
<?php 
$antimsie_path = "";
echo '<script type="text/javascript" src="'.$antimsie_path.'anti-msie/js/jquery.js"></script>';
include_once("anti-msie/anti-msie.php"); 
?>
```

## How to Install: Wordpress

1) Copy src/anti-msie folder into wptheme

2) Add script and jquery before `</body>`:
```php
<?php 
$antimsie_path = get_bloginfo('template_url')."/";
echo '<script type="text/javascript" src="'.$antimsie_path.'anti-msie/js/jquery.js"></script>';
include_once("anti-msie/anti-msie.php"); 
?>
```

## Support

You can find us on this web source:

WebSite: http://www.ptkdev.it/

Source: https://github.com/PTKDev/

IRC: chat.freenode.net at #ptkdev

#Anti-MSIE (jQuery Popup)

Anti Microsoft Internet Explorer is jQuery Popup To Stop The Use IE Browers

## How to Install

1) Copy anti-ie image, css and js from src folder to your website and fix path on step2 and step3.

2) Add css and jquery into `<head></head>`:
```html
	<link href="./css/jquery.mobile-1.2.0.min.css" rel="stylesheet" />
	<script src="./js/jquery.js"></script>
	<script src="./js/jquery.mobile-1.2.0.min.js"></script>
	<script type="text/javascript" language="JavaScript">
		$("#anti-msie").css("width", "300px");
		$("#anti-msie").css("height", "480px");
		$(":jqmData(role='page'):last").on("pageshow", function(event) {
		  $("#anti-msie", $(this)).popup("open");
		});
	</script>
```
    
3) Add css and jquery into after `<body>`:
```html
	<!--[if IE]>
		<div id="anti-msie" data-role="popup" data-history="false" >
			<p><img src="./img/anti-msie_it.png" alt="anti-msie" /><br /><p>
		</div>
	<![endif]-->
```

## Support

You can find us on this web source:

WebSite: http://www.ptkdev.it/

Source: https://github.com/PTKDev/

IRC: chat.freenode.net at #ptkdev

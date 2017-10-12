# WP Html Helper
The WP HTML Helper contains functions that assist in working with HTML

# Example use
include wp-html-helper.php file in your theme or plugin.

```php
<div class="image">
	img_tag(
		array(
			'url' 	 => 'img.png',   //  image url
			'alt' 	 => 'Img alt',   //   image alter tag ( by default image name set as alt )
			'class'  => 'img-class', //   class name
		)
	);
</div>

### Output :

<div class="image">
	<img src="img.png" alt="Img alt" class="img-class" />
</div>

```

# Available Functions:

### The following functions are available:

## Create HTML img tag
```php
img_tag(
	array(
		'url' 	 => '',
		'alt' 	 => '',
		'class'  => '',
		'id' 	 => '',
		'width'  => '',
		'height' => '',
		'srcset' => ''
	)
);

```
## Create HTML anchor tag
```php
anchor_tag(
	array(
		'url' 	 => '',
		'text' 	 => '',
		'target' => '',
		'class'  => '',
		'id' 	 => '',
	)
);

```
## Create HTML heading tag
```php
heading_tag(
	array(
		'tag' 	 => '',
		'text' 	 => '',
		'class'  => '',
		'id' 	 => '',
	)
);

```
## Create HTML paragraph tag
```php
paragraph_tag(
	array(
		'text' 	 => '',
		'class'  => '',
		'id' 	 => '',
	)
);

```

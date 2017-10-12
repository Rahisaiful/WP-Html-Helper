# WP Html Helper
The WP HTML Helper contains functions that assist in working with HTML

# Available Functions:

### The following functions are available:

## Create HTML img tags
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
## Create HTML Anchor tags
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
## Create HTML heading tags
```php
heading_tag(
	array(
		'tag' 	 => 'h1',
		'text' 	 => 'Write Something',
		'class'  => '',
		'id' 	 => '',
	)
);

```
## Create HTML paragraph tags
```php
paragraph_tag(
	array(
		'text' 	 => 'Write Something',
		'class'  => '',
		'id' 	 => '',
	)
);

```

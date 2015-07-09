yii2-floatThead
=====================
This is a Yii 2 wrapper for [jquery.floatThead](http://mkoryak.github.io/floatThead/) a floating/locked/sticky/fixed table header plugin that requires no special CSS and supports window and overflow scrolling.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist bluezed/yii2-floatThead "*"
```

or add

```
"bluezed/yii2-floatThead": "*"
```

to the require section of your `composer.json` file.


How to use
----------

On your view file.

```php

<table id="myTable">
	<tr>
		<th>Col1</th>
		<th>Col2</th>
	</tr>
	<tr>
		<td>Data1</td>
		<td>Data2</td>
	</tr>
</table>
<?php
\bluezed\floatThead\FloatThead::widget(['tableId'=>'myTable']);
?>

```

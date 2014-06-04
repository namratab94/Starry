# Starry

![Image](http://i.imgur.com/nZpT2Yb.png)

Starry is a JavaScript star rating library.

### Installation

> You need [jQuery](https://github.com/jquery/jquery) version 1.11.0 or higher!

HTML markup:
```html
<div id="starry" name="starry"></div>
```
JavaScript markup:
```javascript
$(document).ready(function () {
	var starry = new Starry('#starry');
	starry.init({
		file: '../rate.php' // Path / URL to the rate file!
	});
});
```
Read params in php:
```php
<?php
// Get rating
echo $_POST['rate'];

// Get user id
echo $_POST['user'];
?>
```

-------------

### Options

| Option | Type | Default | Description | 
|:----- |:----- |:----- |:----- |
| stars | int | 5 | Number of rating stars. You can choose 3, 5, 6, 8 or 10. | 
| userId | int | 0 | Id of the user who has voted. | 
| file | string | false | File to which the rating will be sent. | 
| multiple | boolean | false | Determines whether the user can submit several ratings. | 
| startValue | int | 0 | Preloaded rating. | 
| readOnly | boolean | false | Determines whether the user can submit ratings. | 
| tooltips | array | false | Tooltips for the stars. | 

-------------

### Browser support

| Browser | Version | 
|:-----:|:----- |
| ![](http://www.w3schools.com/images/compatible_ie.gif) | 9 or higher | 
| ![](http://www.w3schools.com/images/compatible_chrome.gif) | Works! Tested in version 29 | 
| ![](http://www.w3schools.com/images/compatible_firefox.gif) | Works! Tested in version 35 | 
| ![](http://www.w3schools.com/images/compatible_safari.gif) | Not tested - [Tell us!](https://github.com/Teddy95/Starry/issues) | 
| ![](http://www.w3schools.com/images/compatible_opera.gif) | Not tested - [Tell us!](https://github.com/Teddy95/Starry/issues) | 

-------------

### Cookies

Starry use [cookies](http://en.wikipedia.org/wiki/HTTP_cookie), to save ratings! :cookie:

-------------

### Download

- [Releases on Github](https://github.com/Teddy95/Starry/releases)
- **[Download latest version from Github](https://github.com/Teddy95/Starry/archive/v1.0.1.zip)**
- [Download master from Github](https://github.com/Teddy95/Starry/archive/master.zip)

-------------

### Contributors

- [Teddy95](https://github.com/Teddy95)

-------------

### License

The MIT License (MIT) - [View LICENSE.md](https://github.com/Teddy95/Starry/blob/master/LICENSE.md)

The default icons are from [https://github.com/paomedia/small-n-flat](https://github.com/paomedia/small-n-flat)!
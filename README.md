# Lumen Cors Package

[![Join the chat at https://gitter.im/vluzrmos/lumen-cors](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vluzrmos/lumen-cors?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Lumen Version](https://img.shields.io/badge/Lumen-5.0%20%7C%205.1-orange.svg)](https://packagist.org/packages/vluzrmos/lumen-cors) [![Latest Stable Version](https://poser.pugx.org/vluzrmos/lumen-cors/v/stable)](https://packagist.org/packages/vluzrmos/lumen-cors) [![Total Downloads](https://poser.pugx.org/vluzrmos/lumen-cors/downloads)](https://packagist.org/packages/vluzrmos/lumen-cors) [![Latest Unstable Version](https://poser.pugx.org/vluzrmos/lumen-cors/v/unstable)](https://packagist.org/packages/vluzrmos/lumen-cors) [![License](https://poser.pugx.org/vluzrmos/lumen-cors/license)](https://packagist.org/packages/vluzrmos/lumen-cors) [![Build Status](https://travis-ci.org/vluzrmos/lumen-cors.svg)](https://travis-ci.org/vluzrmos/lumen-cors)

A Simple [Cross Origin Resource Sharing](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS) for Lumen Framework.

# Install

```bash 
composer require vluzrmos/lumen-cors
``` 

# Configure

On <code>boostrap/app.php</code> register the middleware:

```php
$app->middleware([
	//...,
	'Vluzrmos\LumenCors\Middlewares\CorsMiddleware'
]);
```   
> You are free to use ::class notation.


And that is it!

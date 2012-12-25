Twitter Bootstrap integration to Symfony2 projects
==================================
Version 2.2.2


Symfony2 bundled & in composer packaged

https://github.com/sunra/tw-bootstrap-bundle



Installation
------------

1. Add to composer.json into "require" section
```
"sunra/jquery-set-symfony2-bundle": "dev-master"
```
and run 
```
composer.phar update
```

1. Add to app/AppKernel.php
```
new Sunra\jQuerySetBundle\SunrajQuerySetBundle()
```

2. run :
```
app/console assets:install
```


Usage
-----
```js
<script src="{{ asset('bundles/sunrajqueryset/js/jquery/jquery-1.8.3.min.js') }}"></script>
```
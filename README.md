Twitter Bootstrap integration to Symfony2 projects
==================================
Version 2.2.2


Symfony2 bundled & in composer packaged

https://github.com/sunra/tw-bootstrap-bundle



Installation
------------

1. Add to composer.json into "require" section
```
"sunra/tw-bootstrap-bundle": "dev-master"
```
and run 
```
composer.phar update
```

1. Add to app/AppKernel.php
```
new Sunra\TwBootstrapBundle\SunraTwBootstrapBundle()
```

2. run :
```
app/console assets:install
```


Usage
-----
```
...
<link href="{{ asset('bundles/sunratwbootstrap/css/bootstrap.min.css') }}" rel="stylesheet">
...
<script src="{{ asset('bundles/sunratwbootstrap/js/bootstrap.min.js') }}"></script>
...

```
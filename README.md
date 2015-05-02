ar behaviors
============
ar-behaviors

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist ramshresh/yii2-ar-behaviors "*"
```

or add

```
"ramshresh/yii2-ar-behaviors": "*"
```

to the require section of your `composer.json` file.

Optional
--------
The next step is just for initial development, skip it if you directly publish the extension on packagist.org
Add the newly created repo to your composer.json.

"repositories":[
    {
        "type": "git",
        "url": "https://path.to/your/repo"
    }
]

Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \ramshresh\ar\behaviors\AutoloadExample::widget(); ?>```
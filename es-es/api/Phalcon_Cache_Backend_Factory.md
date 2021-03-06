---
layout: article
language: 'es-es'
version: '4.0'
title: 'Phalcon\Cache\Backend\Factory'
---
# Class **Phalcon\Cache\Backend\Factory**

*extends* abstract class [Phalcon\Factory](Phalcon_Factory)

*implements* [Phalcon\FactoryInterface](Phalcon_FactoryInterface)

[Código fuente en GitHub](https://github.com/phalcon/cphalcon/tree/v{{ page.version }}.0/phalcon/cache/backend/factory.zep)

Carga la clase del Adaptador de almacenamiento en caché de backend usando la opción 'adapter', si el frontend es abastecido como matriz se llamara Frontend Cache Factory

```php
<?php

use Phalcon\Cache\Backend\Factory;
use Phalcon\Cache\Frontend\Data;

$options = [
    "prefix"   => "app-data",
    "frontend" => new Data(),
    "adapter"  => "apc",
];
$backendCache = Factory::load($options);

```

## Métodos

public static **load** ([Phalcon\Config](Phalcon_Config) | *array* $config)

protected static **loadClass** (*mixed* $namespace, *mixed* $config)

...
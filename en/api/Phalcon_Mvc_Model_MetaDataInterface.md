---
layout: article
language: 'en'
version: '4.0'
title: 'Phalcon\Mvc\Model\MetaDataInterface'
---
# Interface **Phalcon\Mvc\Model\MetaDataInterface**

[Source on GitHub](https://github.com/phalcon/cphalcon/tree/v{{ page.version }}.0/phalcon/mvc/model/metadatainterface.zep)

## Methods
abstract public  **setStrategy** ([Phalcon\Mvc\Model\MetaData\StrategyInterface](Phalcon_Mvc_Model_MetaData_StrategyInterface) $strategy)

...


abstract public  **getStrategy** ()

...


abstract public  **readMetaData** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **readMetaDataIndex** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, *mixed* $index)

...


abstract public  **writeMetaDataIndex** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, *mixed* $index, *mixed* $data)

...


abstract public  **readColumnMap** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **readColumnMapIndex** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, *mixed* $index)

...


abstract public  **getAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getPrimaryKeyAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getNonPrimaryKeyAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getNotNullAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getDataTypes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getDataTypesNumeric** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getIdentityField** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getBindTypes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getAutomaticCreateAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getAutomaticUpdateAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **setAutomaticCreateAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, *array* $attributes)

...


abstract public  **setAutomaticUpdateAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, *array* $attributes)

...


abstract public  **setEmptyStringAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, *array* $attributes)

...


abstract public  **getEmptyStringAttributes** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getDefaultValues** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getColumnMap** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **getReverseColumnMap** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model)

...


abstract public  **hasAttribute** ([Phalcon\Mvc\ModelInterface](Phalcon_Mvc_ModelInterface) $model, *mixed* $attribute)

...


abstract public  **isEmpty** ()

...


abstract public  **reset** ()

...


abstract public  **read** (*mixed* $key)

...


abstract public  **write** (*mixed* $key, *mixed* $data)

...



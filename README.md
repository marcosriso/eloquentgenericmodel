# eloquentgenericmodel
Eloquent Generic Model Example

Please configure to your needs. You only need to call it, and then, set the table, like in this example:
```php
$modelObj = new GenericModel();
        $modelObj->setTable($table);
        $query = $modelObj::orderby('id', 'desc');```

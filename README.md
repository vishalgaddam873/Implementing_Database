# MyDatabase
MyDatabase is lightweight, fast, and simple database based on the json module.
# Fun with MyDatabase

```
>>> import mydb

>>> db = mydb.load('test.db', True)

>>> db.set('key', 'value')

>>> db.get('key')
'value'

>>> db.dump()
True
```

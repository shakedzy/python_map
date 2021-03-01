# Python Map

An extension to the standard `dict` for Python 3.x. It allows you to call values as attributes:
```python
>> from pythonmap import Map
>> m = Map({'first_name': 'Eduardo'}, last_name='Pool', age=24, sports=['Soccer'])
>> m['age']
24
>> m.age
24
```

Inner dictionaries are automatically translated to maps too, so the dot operator can be chained:
```python
>> from pythonmap import Map
>> m = Map({'x': {'A': 1, 'B':2 }})
>> m.x
{'A': 1, 'B':2 }
>> m.x.A
1
```

Installing:
```
pip install git+https://github.com/shakedzy/pythonmap
```

Original code taken from [This StackOverflow Answer](https://stackoverflow.com/a/32107024/5863503).
    
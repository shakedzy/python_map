# Python Map

An extension to the standard `dict` for Python 3.x. It allows you to call values as attributes:
```python
>> m = Map({'first_name': 'Eduardo'}, last_name='Pool', age=24, sports=['Soccer'])
>> m['age']
24
>> m.age
24
```

Installing:
```
pip install git+https://github.com/shakedzy/python_map
```

Original code taken from [This StackOverflow Answer](https://stackoverflow.com/a/32107024/5863503).
    
# dictionary 딕셔너리

[python library mapping type](https://docs.python.org/ko/dev/library/stdtypes.html#mapping-types-dict)

```python
# 딕셔너리 생성 방법
a = dict(one=1, two=2, three=3)
b = {'one': 1, 'two': 2, 'three': 3}
c = dict(zip(['one', 'two', 'three'], [1, 2, 3]))
d = dict([('two', 2), ('one', 1), ('three', 3)])
e = dict({'three': 3, 'one': 1, 'two': 2})
f = dict({'one': 1, 'three': 3}, two=2)
a == b == c == d == e == f
True
```

| 연산                       | 결과                                                                                                                                                                                                                                                                                                   |
| :------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| list(d)                    | 딕셔너리 d 에 사용된 모든 키의 리스트를 반환                                                                                                                                                                                                                                                           |
| len(d)                     | 딕셔너리 d 에 있는 항목의 수를 반환                                                                                                                                                                                                                                                                    |
| d[key]                     | 키 key 인 d 의 항목을 반환. key 가 매핑에 없는 경우 KeyError                                                                                                                                                                                                                                           |
| d[key] = value             | d[key] 를 value 로 설정                                                                                                                                                                                                                                                                                |
| del d[key]                 | d 에서 d[key] 를 제거합니다. key 가 매핑에 없는 경우 KeyError 반환                                                                                                                                                                                                                                     |
| key in d                   | d 에 키 key 가 있으면 True 를, 그렇지 않으면 False 를 반환                                                                                                                                                                                                                                             |
| key not in d               | not key in d 와 같음                                                                                                                                                                                                                                                                                   |
| iter(d)                    | 딕셔너리의 키에 대한 이터레이터를 반환. iter(d.keys()) 의 단축                                                                                                                                                                                                                                         |
| clear()                    | 딕셔너리에서 모든 항목을 제거                                                                                                                                                                                                                                                                          |
| copy()                     | 딕셔너리의 얕은 복사본을 반환                                                                                                                                                                                                                                                                          |
| get(key[, default])        | key 가 딕셔너리에 있는 경우 key 에 대응하는 값을 돌려주고, 그렇지 않으면 default 를 돌려줍니다. default 가 주어지지 않으면 기본값 None 이 사용됩니다. 그래서 이 메서드는 절대로 KeyError 를 일으키지 않음                                                                                              |
| items()                    | 딕셔너리 항목들((key, value) 쌍들)의 새 뷰를 반환                                                                                                                                                                                                                                                      |
| keys()                     | 딕셔너리 키들의 새 뷰를 돌려줍니다. 뷰 객체의 설명서 을 참조하세요.                                                                                                                                                                                                                                    |
| pop(key[, default])        | key 가 딕셔너리에 있으면 제거하고 그 값을 돌려줍니다. 그렇지 않으면 default 를 돌려줍니다. default 가 주어지지 않고 key 가 딕셔너리에 없으면 KeyError 를 일으킵니다.                                                                                                                                   |
| popitem()                  | 딕셔너리에서 (key, value) 쌍을 제거하고 돌려줍니다.                                                                                                                                                                                                                                                    |
| reversed(d)                | 딕셔너리의 키에 대한 역순 이터레이터를 돌려줍니다. 이것은 reversed(d.keys()) 의 단축입니다.                                                                                                                                                                                                            |
| setdefault(key[, default]) | key 가 딕셔너리에 있으면 해당 값을 돌려줍니다. 그렇지 않으면, default 값을 갖는 key 를 삽입한 후 default 를 돌려줍니다. default 의 기본값은 None 입니다.                                                                                                                                               |
| update([other])            | other 가 제공하는 키/값 쌍으로 사전을 갱신합니다. 기존 키는 덮어씁니다. None 을 돌려줍니다. update() 는 다른 딕셔너리 객체 나 키/값 쌍(길이 2인 튜플이나 다른 이터러블)을 주는 이터레이터를 모두 받아들입니다. 키워드 인자가 지정되면, 딕셔너리는 그 키/값 쌍으로 갱신됩니다: d.update(red=1, blue=2). |
| values()                   | 딕셔너리 값들의 새 뷰를 돌려줍니다. 한 dict.values() 뷰와 다른 dict.values() 뷰 간의 동등 비교는 항상 False를 반환합니다. 이것은 dict.values()를 자신과 비교할 때도 적용됩니다                                                                                                                         |

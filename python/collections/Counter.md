# Counter

[python library](https://docs.python.org/ko/dev/library/collections.html#collections.Counter)

Counter는 해시 가능한 객체를 세기 위한 dict 서브 클래스\
요소가 딕셔너리 키로 저장되고 개수가 딕셔너리값으로 저장되는 컬렉션\
개수는 0이나 음수를 포함하는 임의의 정숫값

요소는 이터러블로부터 계산되거나 다른 매핑(또는 계수기)에서 초기화됨

```python
> c = Counter()
> c = Counter('gallahad')
> c = Counter({'red': 4, 'blue': 2})
> c = Counter(cats=4, dogs=8)
```

계수기 객체는 누락된 항목에 대해 KeyError를 발생시키는 대신 0을 반환한다는 점을 제외하고 딕셔너리 인터페이스를 가짐

```python
> c = Counter(['eggs', 'ham'])
> c['bacon']
> 0
```

개수를 0으로 설정해도 계수기에서 요소가 제거되지 않습니다. 완전히 제거하려면 del을 사용하십시오

```python
> c['sausage'] = 0
> del c['sausage']
```

| 연산                            | 결과                                                                                                                                                                                                                    |
| :------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| elements()                      | 개수만큼 반복되는 요소에 대한 이터레이터를 반환. 요소는 처음 발견되는 순서대로 반환. 요소의 개수가 1보다 작으면 elements()는 이를 무시.                                                                                 |
| most_common([n])                | n 개의 가장 흔한 요소와 그 개수를 가장 흔한 것부터 가장 적은 것 순으로 나열한 리스트를 반환합니다. n이 생략되거나 None이면, most_common()은 계수기의 모든 요소를 반환합니다. 개수가 같은 요소는 처음 발견된 순서를 유지 |
| subtract([iterable-or-mapping]) | 이터러블이나 다른 매핑 (또는 계수기)으로부터 온 요소들을 뺍니다. dict.update()와 비슷하지만 교체하는 대신 개수를 뺍니다. 입력과 출력 모두 0이나 음수일 수 있습니다.                                                     |
| total()                         | Counter의 합계를 계산                                                                                                                                                                                                   |

```python
# elements()
> c = Counter(a=4, b=2, c=0, d=-2)
> sorted(c.elements())
> ['a', 'a', 'a', 'a', 'b', 'b']|
```

```python
# most_common([n])
> Counter('abracadabra').most_common(3)
> ('a', 5), ('b', 2), ('r', 2)]
```

```python
# subtract([iterable-or-mapping])
> c = Counter(a=4, b=2, c=0, d=-2)
> d = Counter(a=1, b=2, c=3, d=4)
> c.subtract(d)
> c
> Counter({'a': 3, 'b': 0, 'c': -3, 'd': -6})
```

```python
# total()
> c = Counter(a=10, b=5, c=0)
> c.total()
> 15
```

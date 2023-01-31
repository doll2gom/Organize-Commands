# Gathering 집합

[집합](https://docs.python.org/ko/dev/tutorial/datastructures.html#sets)
[집합 형 - set, frozenset](https://docs.python.org/ko/dev/library/stdtypes.html#set-types-set-frozenset)

집합을 만들 때는 중괄호나 set() 함수를 사용

| 연산   | 기능                           |
| :----- | :----------------------------- |
| a - b  | letters in a but not in b      |
| a \| b | letters in a or b or both      |
| a & b  | letters in both a and b        |
| a ^ b  | letters in a or b but not both |

집합 컴프리헨션

```python
입력
>> a = {x for x in 'abracadabra' if x not in 'abc'}
>> print(a)

출력
{'r', 'd'}
```

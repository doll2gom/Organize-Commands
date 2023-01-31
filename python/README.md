# Python 내장함수

[리터럴과 이리터럴](https://wikidocs.net/16068)
[리스트 뮤터블과 이뮤터블](https://wikidocs.net/16038)
| 연산 | 결과 | 라이브러리 |
| :----------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------- |
| abs(x) | 숫자의 절댓값을 돌려줍니다. 인자는 정수, 실수 | [ads](https://docs.python.org/ko/dev/library/functions.html#abs) |
| len(s) | 객체의 길이 (항목 수) 반환. 인자는 시퀀스 (문자열, 바이트열, 튜플, 리스트 또는 range) 또는 컬렉션 (딕셔너리, 집합 또는 불변 집합) | [len](https://docs.python.org/ko/dev/library/functions.html#len) |
| divmod(a, b) | 정수 나누기를 사용할 때 몫과 나머지로 구성된 숫자 쌍을 반환합 | [divmod](https://docs.python.org/ko/dev/library/functions.html#divmod) |
| chr(i) | 유니코드 코드 포인트가 정수 i 인 문자를 나타내는 문자열 반환 : ord() 의 반대 | [chr](https://docs.python.org/ko/dev/library/functions.html#chr) |
| max(iterable, \*, key=None) | iterable 에서 가장 큰 항목이나 두 개 이상의 인자 중 가장 큰 것을 돌려줍 |
| max(iterable, \*, default, key=None) | 선택적 키워드-전용 인자가 두 개일 경우 key 인자는 list.sort() 처럼 순서를 지정. default 인자는 제공된 iterable이 비어있는 경우 돌려줄 객체를 지정. iterable이 비어 있고 default 가 제공되지 않으면 ValueError 발생 |
| max(arg1, arg2, \*args, key=None) | 여러 항목이 최댓값이면, 함수는 처음 만난 항목을 반환 |

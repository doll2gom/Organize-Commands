# list

[python library Sequence](https://docs.python.org/ko/dev/library/stdtypes.html#sequence-types-list-tuple-range)
[list2](https://docs.python.org/ko/dev/library/collections.abc.html#collections.abc.MutableSequence)

| 연산                         | 결과                                                                               |
| :--------------------------- | :--------------------------------------------------------------------------------- |
| _x_ in _s_                   | _s_ 의 항목 중 하나가 _x_ 와 같으면 True, 그렇지 않으면 False                      |
| _x_ not in _s_               | _s_ 의 항목 중 하나가 _x_ 와 같으면 False, 그렇지 않으면 True                      |
| _s_ + _t_                    | _s_ 와 _t_ 의 이어 붙이기                                                          |
| _s_\*_n_ 또는 _n_\*_s_       | _s_ 를 그 자신에 _n_ 번 더하는 것과 같다                                           |
| _s_[_i_]                     | _s_ 의 _i_ 번째 항목, 0에서 시작                                                   |
| _s_[_i_:_j_]                 | _s_ 의 _i_ 에서 _j_ 까지의 슬라이스                                                |
| _s_[_i_:_j_:_k_]             | _s_ 의 _i_ 에서 _j_ 까지 스텝 _k_ 의 슬라이스                                      |
| len(_s_)                     | _s_ 의 길이                                                                        |
| min(_s_)                     | _s_ 의 가장 작은 항목                                                              |
| max(_s_)                     | _s_ 의 가장 큰 항목                                                                |
| _s_.index(_x_[, _i_[, _j_]]) | (인덱스 _i_ 또는 그 이후에, 인덱스 _j_ 전에 등장하는) _s_ 의 첫 번째 _x_ 의 인덱스 |
| _s_.count(_x_)               | _s_ 등장하는 _x_ 의 총수                                                           |

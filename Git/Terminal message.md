# Terminal message

## Status로 확인할 수 있는 파일의 상태

- `Tracked` : 이전부터 버전으로 관리되고 있는 파일 상태
  - Unmodified : git status에 나타나지 않음 (X)
  - Modified : Changes not staged for commit
  - Staged: Changes to be committed
- `Untracked` : 버전으로 관리된 적 없는 파일 상태 (파일을 새로 만든 경우)

| 메세지                                                    | 의미                | 상황                                                       |
| :-------------------------------------------------------- | :------------------ | :--------------------------------------------------------- |
| Changes to be committed:                                  | commit될 변경사항들 | 작업된 파일들을 이미 add했지만, commit을 하지 않음         |
| Untracked files:                                          | add하지 않은 파일들 | 파일을 만들었지만, add를 하지 않음                         |
| Author identity unknown\*\*\* please tell me who you are. |                     | 가입한 이메일 주소와 닉네임을 입력해 설정                  |
| working tree clean                                        | commit할 것이 없음  | 마지막 commit 이후 작업한 내용이 없음 add할 내용 조차 없음 |
| Changed not staged for commit                             | 변경사항 add 안됨   | 마지막 commit 이후 변경사항은 있지만, add가 안된 상황      |

# GitHub 기반 원격 저장소

| 명령어                          | 기능                                                     |
| :------------------------------ | :------------------------------------------------------- |
| git clone \<url>                | 원격 저장소를 복제하여 가져옴                            |
| git remote -v                   | 원격 저장소의 정보를 확인함                              |
| git remote add \<origin> \<url> | 원격 저장소 추가 (일반적으로 origin)                     |
| git remote rm \<origin>         | 원격 저장소 삭제                                         |
| git push \<origin> <브랜치이름> | 원격 저장소로 로컬 저장소의 변경 사항(커밋)을 올림(push) |
| git pull \<origin> <브랜치이름> | 원격 저장소로부터 변경된 내역을 받아와서 이력을 병합함   |

## 초기 원격저장소 설정

```
$ git remote add origin https://github.com/kdt-live/test.git

    원격저장소 추가해 origin으로                 깃허브     저장소
                                          username   이름
```

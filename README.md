# git 연습
---

#### 생성/업로드/다운로드/삭제 
---

1. create repository `gitEx200309`
2. git clone 

```shell
$ git clone 주소
$ cd 폴더
```

3. file 생성 ( `README.md` ,  `makeFileData.md` )

```shell
$ touch README.md makeFileData.md
```

4. git push

```shell
$ git add README.md                 // 첨부
$ git commit -m "first comment"     // 설명
$ git status                        // 내용 확인
$ git push                          // 보내기
```

5. githup.com 페이지에서 내용 수정 후 git pull
6. 다른 폴더에서 git clone 처리 후 내용 수정
7. git push
8. 원래폴더에서 git pull 하지 않고 내용 수정 후
9. git push -> 에러 수정 git push
10. 다른 폴더에서도 git pull
11. 7-12번 2~3번 반복
12. 내 컴퓨터, github.com 페이지의 repository 모두 삭제
13. 1-13번까지를 4~5번 반복

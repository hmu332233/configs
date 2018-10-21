## git

### .gitconfig
- change-commits  
  - 커밋의 내용을 일괄적으로 바꿔야할 때 사용
```bash
git change-commits GIT_AUTHOR_NAME "old name" "new name" # 전체내역에서 이름 바꾸기
git change-commits GIT_AUTHOR_EMAIL "old@email.com" "new@email.com" HEAD~10..HEAD # 10개 커밋까지에서 이메일 바꾸기
```

- tip
  - 위치를 모를땐 아래의 명령어로 찾을 수 있다.
```bash
$ git config --list --show-origin
```


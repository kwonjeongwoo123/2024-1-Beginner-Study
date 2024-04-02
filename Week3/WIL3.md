# 커밋 기록을 최신 순으로 확인할 수 있는 git log와 커밋을 식별할 수 있는 Commit Id, 현재 작업중인 위치인 HEAD에 대해서 배웠다.
- git log
- git log --oneline
- git status
- git commit --amend -m "커밋 메시지"
- git commit --amend --no-edit

# 커밋을 제거하는데 사용되는 reset과 함께 이용하는 세 가지 옵션에 대해서 배웠다.
## soft: Staged Area까지
## mixed: Working Directory까지
## hard: 이전 커밋으로 돌아감
- git reset --soft 커밋 아이디
- git reset --mixed 커밋 아이디
- git reset --hard 커밋 아이디

# 커밋을 제거하지 않고 새로운 커밋을 만들어 커밋을 되돌리는 revert에 대해서 배웠다.
- git revert 커밋 아이디
- git revert --no-edit 커밋 아이디
- git revert --no-commit
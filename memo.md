```sh
echo hello
mkdir 261106_review
echo "mkdir 261106_review" > 261106_review/memo.md
history
cd 261106_review
git init
git status
ls -a # .git
# rm -rf .git
git add .
git status # git reset
# 커미터 config <- github 계정정보
git config list --global
# git config --global user.name ilovejava26
# git config --global user.email ilovejava26@gmail.com
git commit -m "first commit"
# git log
git log --oneline
```

- https://github.com/new
- https://github.com/ilovejava26/first-repo
 
```sh
# https://github.com/ilovejava26/first-repo.git
git remote add origin https://github.com/ilovejava26/first-repo
# git remote
git remote -v
git branch -M main # -m -M, -M : 현재 다른 브랜치에 같은 이름(main)이 있어도 현재 브랜치를 해당 이름으로 바꾼다. -m : '같은 이름의' 브랜치가 있으면 거절
git push origin main
# git push -u origin main
# -u는 현재 푸시한 리포지토리와 브랜치를 이후에도 push 기본으로 쓰겠다
# git push (origin main)
# 403 # 자격증명 이슈
# https://github.com/ilovejava26/first-repo/
# mac : gh auth 
# win : 제어판 -> window 자격 증명 -> github 관련 삭제 후 재로그인

# 웹에디터 -> 해당 저장소 들어가서 `.` - 커밋만 가능
git pull origin main
```

```sh
# git clone https://github.com/ilovejava26/share
# git clone 저장소주소 새이름
git clone https://github.com/ilovejava26/share my-share
```


$ npm i react-router-dom

$ nvm list available

$ nvm install 16.20.2 
    For my case, I had to downgrade from node v18 to v16. 
$ npm i express@

# How to install nvm on MAC 
$nvm list availbale
# zsh: command not found: nvm 오류해결법
    열심히 뒤지던 중, bash shell에서는 nvm 명령어를 제대로 인식하지만, mac의 default shell인 zsh에서는 nvm을 인식하지 못하는 문제가 있을 수 있다는 정보를 찾아냈다.
    $ :qa(빠저나가기)
    $ git clone https://github.com/nvm-sh/nvm.git ~/.nvm
    $ source ~/.nvm/nvm.sh

# 사용하려는 버전을 다음 명령어에  
    $ nvm use 16.18.1
# Error 발생시 
    fatal: not a git repository (or any parent up to mount point /Volumes)
    Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
#  git 초기화 
    git init
    git config --global user.name "kchstar_outlook_com"
    git config --global user.email "kchstar@outlook.com"

    git add * / git add --all / git add . 
    git commit -m "first commit"[Git] 로컬 저장소에 Commit하기
    [Git] 로컬 저장소에 Commit하기

    git branch 
        ex) main
        ex) origin 
    git remote add origin https://github.com/kchstar/react-hooks-demo_2.git

    git push -u origin main (x)
    git push --set-upstream main main

    git log (반영사항 확인)
        git log나가기 = Q
    git reset a6f30a --hard (commit:6자리 / 이전상태로 되돌리기)

# (use "git add <file>..." to include in what will be committed)
    ex) git add * (all)
    ex) git add README.md
# REMOTE 경로 재 설정
    $ git remote set-url origin https://github.com/kchair777/inbrozz_demo.git


# 이메일을 벨리드하지않거나 && 이메일의 길이가 0보다 클때 두가지사항을 만족할때 에러 내용을 뛰어준다. 
     {
        !emailValid && email.length > 0 && (
        <div>올바른 이메일읃 입력해주세요. </div>
     )}
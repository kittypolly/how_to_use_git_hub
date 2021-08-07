# how_to_use_git_hub

어떻게 git을 사용해야 하는지에 대해 적어놓은 레포지토리이다.

우선 폴더를 하나 만들고 gitbash에서 폴더를 하나 만들고 git init을 실행한다.
그러면 그때부터 git을 추적하기 시작한다.

# local과 github를 연결하는 법

<pre>
<code>git remote add [이름] [주소]
ex) git remote add origin https://gitbub.com/kittypolly/demo.git</pre></code>
-git remote - v 를 사용하면 현재 local과 연결되어 있는 github를 알 수 있다.
이름은 관습적으로 origin을 사용한다.

# local에서 작업한 파일을 github에 올리는 법
<pre>
<code>git push -u origin master --tags</pre></code>
origin으로 master 브랜치와 모든 태그를 업로드 한다.


# 잘못 연결했을때 remote 삭제하는법
<pre>
<code>git remote rm [저장소이름]</pre></code>

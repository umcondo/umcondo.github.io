---
layout: post
title: 로컬 컴퓨터를 이용해 깃 블로그 수정하는법
tag: [기술, 블로그]
---

[윈도우10 기준]

umcondo/github.io로 접속하면 수정하고 5~10분정도 소요되므로 로컬 컴퓨터로 vscode를 이용하여 블로그 포스팅 및 수정을 하려고 한다.

1. vscode 설치

2. 루비 설치 (버전확인 cmd에서 ruby -v)

3. 지킬 설치

   1. gem install jekyll bundler - 5~10분 소요

   2. gem install webrick - 이거 설치안하면 jekyll serve이 오류난다.

4. vscode 터미널에서 jekyll serve 입력 후 [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

5. 마크다운 문법 숙달....

참고 블로그

- [http://mooonchivekr.blogspot.com/2020/08/windows-10-github-pages.html](http://mooonchivekr.blogspot.com/2020/08/windows-10-github-pages.html)
- [https://ogaeng.com/jekyll-blog-install/](https://ogaeng.com/jekyll-blog-install/)

- [https://cjy-tech.github.io/Themes-for-jekyll-blog/](https://cjy-tech.github.io/Themes-for-jekyll-blog/)

# [나만의 블로그](https://jjunh33.github.io/)

## Git blog 프로젝트 Build 과정

### 1. Github Repository 생성 & 연동

jjuh33.github.io 이름의 Repository 생성 후 로컬 컴퓨터에 clone

### 2. Jekyll 사용한 정적 웹사이트

- [Jekyll 공식 사이트](https://jekyllrb-ko.github.io/)에서 Window용 Jekyll 설치

- _jekyll new . --force_ 실행 후 *bundle exec jekyll serve*로 기본 Jekyll 사이트 생성

- \_config.yml 파일을 수정해 블로그 기본 설정, 텍스트 수정 가능

- \_posts 폴더에서 YYYY-MM-DD-TITLE.md의 형태로 블로그 포스트를 마크다운으로 작성

- [disqus](https://disqus.com/) 툴을 이용해 블로그에 댓글 기능 추가

### 3. 블로그에 테마 입히기

- [다양한 Jekyll 테마를 가져올 수 있는 사이트](http://jekyllthemes.org/)에서 [AP테마](http://jekyllthemes.org/themes/AP/)를 선택하고 이를 적용

- 이후에 2번처럼 블로그를 꾸미고 새로운 기능인 [Google Analytics](https://analytics.google.com/analytics/web/#/p344369935/reports/intelligenthome)추가

### 4. 최종 결과물

![home](assets/img/home.jpg)

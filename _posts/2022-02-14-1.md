---
title: "Jekyll 으로 Github 홈페이지 구성하기"
date: 2022-02-14 22:00:00 -0900
categories: Web
---

우여곡절끝에 Github 홈페이지를 Jekyll로 구성했다.

Mac Silicon에서 Jekyll 구성하는 방법 공유해보자.



---
1. x-code 설치
   
   ``` x-code-select --intall ```

2. brew 설치
   
   `brew install gcc`
3. 루비 설치 (Jekyll 언어)
   - rbenv 설치
  
      ```brew install rbenc ruby-build```
   - 현재 버전 확인하기
  
      ```rbenv versions```
   - Mac 에 기본적으로 설치되어 있는 ruby 버전 확인 가능
   - `sudo` 를 이용한 루트 권한으로 사용가능하지만 권장하지는 않는다고 함
    ``` 
     rbenv install -l // 설치 가능한 버전 보기
     rbenv install -list-all // 설치 가능한 모든 버전 보기
     rbenv install (버전)
    ``` 
-------





[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

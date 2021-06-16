# 토비의 스프링 읽기 팀 블로그

## 블로그 링크

[https://javabookstudy.github.io/](https://javabookstudy.github.io/)

## vs code로 다루는 법

1. 원하는 곳에 git clone을 하여 가져오면 됩니다.

```
git clone https://github.com/JavaBookStudy/JavaBookStudy.github.io.git
```

2. 위의 파일이 있는 곳으로 다시 vs code를 실행합니다.

이제 수정하고 싶으면,

```
git add .
git commit -m "123"
git push
```

를 하시면 됩니다.

혹시 안되시면

```
git init
git config --global user.name taxol1203
git config --global user.email taxol1203@pusan.ac.kr
git remote add origin https://github.com/JavaBookStudy/JavaBookStudy.github.io.git
git add .
git commit -m "first"
git push --set-upstream origin master
```

를 진행하시면 되실 겁니다.

## 건들여야 할 부분

1. 포스팅하는 곳

`_posts` 폴더 내에 작성하시면 됩니다.

```
2021-xx-xx-카테고리-파일제목.md
```

위의 방법으로 파일 이름을 맞추어야 업로드가 됩니다.

2. 사진 넣는 곳

```
/assets/images/폴더이름/파일명
```

으로 경로를 맞추면 됩니다.

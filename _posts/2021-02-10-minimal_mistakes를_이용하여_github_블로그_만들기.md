---
title: "게시물 작성 방법"
subtitle: 게시물을 작성하는 Template입니다. 참고해 주세요
categories: 기타
date: 2021-02-10 13:59:23 +0900
toc: 
tags:
  - temp Tag
toc: true
toc_sticky: true
---

> Java

아래와 같은 방법으로 하면 글을 작성하면 됩니다.

# 큰 제목

전체적인 글의 제목을 여기에 작성하시면 됩니다.

## 부 제목

각 항목 하나씩을 `##`을 붙혀서 작성하시면 됩니다.

### 소 제목

`##`내의 항목을 `###~으로 작성하면 됩니다.

## 코드 작성 법

다음과 같이 코드를 작성하시면 됩니다.

```cpp
#include <iostream>
using namespace std;
int main(){
  cout << "hello taxol!" << "\n";
  return;
}
```

## 사진 등록 하는 법

사진 등록 및 크기 확인
<img src="/images/codingTest/bj_11726/n_12.PNG" width="40%" height="40%">

## 지수 나타내기

2의 N승 : 2<sup>N</sup>
로그 2의 N: log<sub>2</sub>N

## 글 숨기기

<details>
<summary>DFS로 실패한 코드</summary>
<div markdown="1">

여기에 숨길 내용 작성

</div>
</details>

## 테이블 만들기

|     | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | 11  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T   | 5   | 4   | 3   | 2   | 1   | 1   | 2   | 3   | 4   | 5   | x   |
| P   | 50  | 40  | 30  | 20  | 10  | 10  | 20  | 30  | 40  | 50  | x   |
| DP  | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   |

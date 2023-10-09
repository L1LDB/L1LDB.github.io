# 🛌 LILDB Team Blog

| _Laziness is the devil's pillow. (Danish Proverb)_

[![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy)][gem]&nbsp;
[![GitHub license](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]

**[🛌 LILDB 팀 블로그](https://l1ldb.github.io)**
**[🎲 LILDB 스터디 진행 규칙](https://l1ldb.github.io/about)**

<br>

#### ✏️ Study Contents

- **코딩 인터뷰 대학** : 5문제씩 연습 문제 만들기
- **프로그래밍 언어** : JAVA & C 챕터 별로 학습
- **알고리즘** : 매주 3문제풀고 풀이 진행
  - _재도전 → 차주까지 다시 풀어오기_
- 포트폴리오 다듬기 **→ 매주 업데이트**

<br>

#### 🔖 [Github.io](l1ldb.github.io) Personal Mark

| 🐹                                               | 🐢                                       | 🦊                                       | 🐣                                       |
| ------------------------------------------------ | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| [@chaeshee0908](https://github.com/chaeshee0908) | [@gani0325](https://github.com/gani0325) | [@gengminy](https://github.com/gengminy) | [@olive-su](https://github.com/olive-su) |

<br>
<br>

---

## 📁 Files

```shell
.
├── README.md
├── _config.yml
├── _data
├── _plugins
├── _posts
│   ├── algorithm # 알고리즘
│   │   └── {문제명 | 챕터명}
│   │       └── {날짜}-{작성자}
│   │           └── ... {포스팅 관련 에셋} ...
│   │           └── {문제명 | 챕터명}.md
│   ├── coding-interview-univ # 코딩 인터뷰 대학
│   ├── extreme-c # C 프로그래밍 도서 - 전문가를 위한 C
│   ├── modern-java-in-action # 자바 프로그래밍 도서 - 모던 자바 인 액션
│   └── common # 공통 문서
├── _site
├── _tabs
├── assets
└── index.html
```

<br>

## 📮 Posting

| 💡 _팀 블로그 설정 변경 시에는 `main` 에서 작업해주세요!_

1. 각자의 깃허브 아이디로 브랜치를 생성합니다.
2. 해당 주차의 포스팅을 작성해서 브랜치로 파일을 업로드합니다.
3. `main` 브랜치에서 각자 브랜치에 올린 파일을 `pull` 해서 빌드를 진행합니다.

<br>

- 워크플로우 예시

```shell
$ git checkout -b {개인-github-id}
$ git pull main # main 브랜치와 conflict 해결
$ git push # 공부 내용 md 파일 개인 브랜치로 push

$ git checkout main
$ git pull {개인-github-id}
$ git push
```

<br>

- 컨벤션

  - 커밋 메시지

    `{Title}: {Commit Message}`

    e.g. `post: [n주차_작성자] 3. 이분 탐색과 비트 연산`

    e.g. `update: [n주차_작성자] 3. 이분 탐색과 비트 연산`
    <br>

    | Title    | Description         |
    | -------- | ------------------- |
    | settings | 세팅                |
    | post     | 팀 블로그 글 포스팅 |
    | update   | 글 수정             |

    <br>

  - 포스팅 내용
    - 제목 : `{emoji} {title}`
    - 작성자 : `{github id}`
    - 태그 : `카테고리`, `n주차`, `작성자` ...
      <br>
    - [ 알고리즘 ]
      - 문제 링크, 해설, 사용 언어, 시간, 메모리, 코드
      - _재시도 필요한 문제 → 제목에 '🔄' 해당 이모지 추가 & 재시도 후 코드 업데이트_

<br>

## Theme

[**🔗 Chirpy**][chirpy]

<br>

## Usage

| 💡 _포스팅 올리기 전에 로컬에서 한번 확인하고 업로드 해주세요!_

<br>

- 로컬에서 확인하는 방법

```shell
$ bundle # Install dependencies
$ bundle exec jekyll s # Running Local Server
```

<br>

## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE

<br>

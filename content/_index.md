---
created: 2023-09-30 22:18
updated: 2023-11-01 17:59
tags:
  - Obsidian
  - Markdown
aliases: 
Title: amethyst 한국버전 설명서
bookCollapseSection: true
---
## 안녕하세요!
옵시디언을 입문하고, 퍼블리쉬를 고민하다 우연히 휴고를 통해 만들어볼까 싶어서 만들어봤습니다. 이 버전은 [amethyst](https://github.com/64bitpandas/amethyst)를 제 입맛에 수정한 테마입니다.  


### 간단한 사용법
1. properties에 `title`을 생성하고 제목을 지어주세요!
2. 폴더를 생성하고 나면 꼭 `_index.md`를 생성해주세요. 이 파일이 휴고에서 실질적으로 폴더의 역할을 합니다. 
3. 생성된 `_index.md`의 properties에 `bookCollapseSection: ture`로 하면 디렉토리처럼 접었다 폈다 할 수 있는 기능을 생성할 수 있습니다.
4. `content`가 실질적으로 볼트와 같은 역할을 하고 있습니다. 
5. 옵시디언의 설정에 들어가 파일의 경로를 '절대경로'로 지정해줘야 옵시디언이 서로의 연결을 확인할 수 있습니다.
6. 옵시디언의 경로는 hugo-obsidian을 실행하여 자동으로 생성됩니다. 그러나 생성되는 경로와 테마가 참고하는 경로가 다르기 때문에,  프로젝트 레포지토리와 같은 디렉토리에 생성된 `static`에 있는 `linkmap`을 `amethyst/static`폴더에 꼭 덮어쓰기 해주세요.
7. `amethyst/data`에 있는 두 `json`파일을 `amethyst/assets/indices`폴더에 덮어씌우기 해주세요.

그 외 잡다한 설명은 [amethyst](https://github.com/64bitpandas/amethyst)에서 확인해주세요! 
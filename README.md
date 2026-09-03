# pb-action-site — 참여예산 상담소 (구운 것)

**여기서 고치지 마세요.** 이 저장소는 GitHub Pages 가 서비스하는 **결과물**만 담습니다.

화면을 고치는 곳은 따로 있습니다.

```
action-home-renewal/pb.html                   (화면 원본, 공개)
action-home-renewal/tools/parts/footer.html   (하단)
      ↓  participatory-budget/build.py        (비공개)
participatory-budget/index.html
      ↓  그대로 복사
여기 (pb-action-site)  →  https://pb.action.or.kr/
```

- 화면 원본 : <https://github.com/bada17/action-home-renewal> 의 `pb.html`
- 굽는 곳   : `bada17/participatory-budget` (비공개. `build.py` 와 접수처 코드가 있습니다)

여기 파일을 손으로 고치면 다음에 구울 때 사라집니다.

## 지금 담긴 것

    index.html      구운 화면 한 장
    img/            전문위원 사진
    CNAME           pb.action.or.kr
    robots.txt      검색 색인 막기 (아래 참고)

## robots.txt 는 임시입니다

지금 화면의 **'전문위원의 글' 네 편이 전부 예시**라, 검색에 잡히면 안 됩니다.
실제 글로 바꾸는 날 `robots.txt` 를 지웁니다.

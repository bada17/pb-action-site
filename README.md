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

## 사는 주소는 하나입니다 — pb.action.or.kr

**GitHub Pages 가 진짜입니다.** `main` 에 push 하면 1 분 안에 반영됩니다.

> ⚠️ **`https://pb-action-site.pages.dev/` 는 진짜가 아닙니다.**
> 2026-09-07 에 Cloudflare Pages 로도 한 번 올려 둔 것이 남아 있습니다
> (`.wrangler/` 폴더가 그 흔적입니다. 커밋하지 마세요).
> **push 해도 저절로 갱신되지 않아 그쪽 화면은 낡습니다** —
> 2026-09-08 에 실제로 "왜 반영이 안 되냐"고 헷갈린 자리입니다.
> 그날 GitHub Pages 로 가기로 정했고, Cloudflare 프로젝트는 지우기로 했습니다.

## 지금 담긴 것

    index.html      구운 화면 한 장
    img/            전문위원 사진
    CNAME           pb.action.or.kr
    robots.txt      검색 색인 막기 (아래 참고)
    .nojekyll       Pages 가 파일을 손대지 않고 그대로 내보내게

## robots.txt 는 임시입니다

처음에는 **'전문위원의 글' 네 편이 전부 지어낸 예시**라서 막아 둔 것입니다.
그 넷은 2026-09-07 에 지웠습니다 — 지금 글 목록은 비어 있고 접수처에서 읽어 옵니다.

남은 예시는 **'오간 질문' 셋**뿐입니다. 이건 접수처가 막혔을 때 화면이 비지 않게
일부러 남긴 자리표시라, 지우지 않습니다(그래서 답변 서명도 안 붙였습니다).
DNS 가 붙고 화면이 정해지면 `robots.txt` 를 걷으면 됩니다.

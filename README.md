# 디벨로직 공개 문서

디벨로직이 만든 앱의 **개인정보처리방침**과 **계정·자료 삭제 요청** 안내입니다.
구글 플레이가 웹에서 열리는 주소를 요구하기 때문에 여기에 둡니다. 앱 소스는
여기 없습니다.

<https://thedeveljun.github.io/develogic-docs/>

## 앱

### 펀클럽 (`com.develogic.funclub`) — `funclub/`

- 개인정보처리방침 — <https://thedeveljun.github.io/develogic-docs/funclub/privacy/>
- 계정·자료 삭제 요청 — <https://thedeveljun.github.io/develogic-docs/funclub/delete/>

## 앱을 더할 때

1. 앱 이름으로 폴더를 하나 만듭니다 (예: `newapp/`).
2. 그 안에 `index.md` · 방침 · 삭제 요청 세 쪽을 두고, 각 쪽 머리말의 `permalink`
   을 `/newapp/`, `/newapp/privacy/`, `/newapp/delete/` 로 적습니다.
3. 첫 쪽(`index.md`)과 이 README에 줄을 더합니다.

쪽끼리 거는 링크는 `{{ site.baseurl }}` 을 거쳐 적습니다. 저장소 이름이 바뀌어도
`_config.yml` 한 줄만 고치면 되기 때문입니다.

문의: thedeveljun@gmail.com (디벨로직)

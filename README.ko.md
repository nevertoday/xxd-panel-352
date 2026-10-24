<div align="center">

# XXD Panel 352｜검은 선 작은 풍경

**사진 속 주인공과 곁의 작은 물건들을 큰 구름 아래 고요한 검은 선의 작은 풍경으로 그립니다.**

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <strong>한국어</strong> · <a href="README.ar.md">العربية</a>

</div>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 352 · 01 · 골목 카페"><br><sub>01 · 골목 카페</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 352 · 02 · 작은 서점"><br><sub>02 · 작은 서점</sub></td>
  </tr>
</table>

<p align="center"><sub>위는 원본 사진, 아래는 이 스타일로 다시 그린 모습입니다.</sub></p>

## 무엇인가요

Claude Code, Codex 같은 AI 에이전트용 Skill입니다. 사진 한 장을 주면 Panel 352의 원본 프롬프트대로 완성된 PNG를 그립니다.

- **어떤 그림이 되나요:** 한 가지 검은 가는 선만으로 주인공과 바로 곁의 작은 물건 몇 가지를 정면에서 본, 색을 칠하지 않은 작은 풍경으로 그립니다. 형태는 네모나고 살짝 비뚤며 비율은 조금 낮게 눌러 장난감 모형처럼 반듯하고, 세부는 작은 아이콘으로 줄이고 창과 문은 작은 네모, 질감은 짧은 선 몇 개로만 나타내며 명암은 넣지 않습니다. 선은 부드러운 연필로 눌러 그은 듯 굵기가 조금씩 흔들리고 모서리에서 가끔 끊깁니다. 작은 풍경은 끊어진 짧은 가로선 땅 위에 서 있고, 뒤쪽 한편에서 주인공보다 키 큰 뭉게구름 하나가 피어오릅니다. 전체는 화면 가운데 아주 작은 자리만 차지하고 주변은 넓은 흰 종이입니다. 아래쪽에 한참 띄워서 같은 펜으로 쓴 느슨한 손글씨 짧은 시 한 줄이 바로 지금 이 순간을 적습니다.
- **키워드:** 정면에서 본 검은 가는 선 · 채색 없음 · 네모나고 살짝 비뚠 장난감 같은 풍경 · 끊어진 짧은 가로선 땅 · 뒤편의 큰 구름 · 아래 손글씨 짧은 시
- **만들 수 있는 것:** 위아래 비교(위 사진, 아래 디자인), 좌우 비교, 디자인만, 또는 휴대폰·태블릿·PC·워치 배경화면 세트. 여러 개를 함께 고를 수 있고 비율과 픽셀도 자유입니다.
- **이런 것은 아닙니다:** 필터도 템플릿도 아닙니다. 매번 사진에서 새로 그리며, 사진 한 장이 하나의 독립된 작업입니다.

## 세 단계로 시작하기

**1. 설치.** Claude Code, Codex 등 Skills를 지원하는 에이전트에서 쓸 수 있습니다:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-352 --skill xxd-panel-352
```

설치 후 에이전트 세션을 다시 시작하세요. 이 저장소를 `git clone`한 뒤 `~/.claude/skills/xxd-panel-352` 또는 `~/.codex/skills/xxd-panel-352`에 링크해도 됩니다.

**2. 에이전트가 이미지를 생성할 수 있는지 확인.** 이 Skill에는 자체 이미지 모델이 없고, 에이전트의 이미지 생성(GPT Image 2 권장)을 사용합니다.

- Codex는 내장 이미지 생성이 켜져 있으면 바로 쓸 수 있습니다.
- Claude Code처럼 내장 이미지 생성이 없는 에이전트는 OpenAI 호환 이미지 API가 필요합니다. 5분 정도면 됩니다: [이미지 생성 설정](#이미지-생성-설정).

잘 모르겠다면 그냥 써 보세요. 생성할 수 없으면 작업을 시작하기 전에 Skill이 멈추고 알려 줍니다.

**3. 사진을 보내고 한 문장으로 말하기:**

> xxd-panel-352으로 이 사진을 3:4 위아래 비교 포스터로 만들고 한국어 제목을 붙여 줘.

요청이 충분하면 바로 생성하고, 빠진 것(레이아웃, 비율, 글자)은 보통 한두 가지만 묻습니다. 결과 PNG는 `~/Desktop/xxd/xxd-panel-352/` 아래 새 폴더에 저장됩니다.

## 잘 맞는 사진

**잘 맞아요**

- 여행지나 거리의 작은 건물: 모퉁이 카페, 오래된 문, 바닷가 오두막 한 줄
- 고요한 일상의 한구석: 창가의 꽃, 벽에 기댄 자전거, 오래된 우물
- 구도가 평범하거나 배경이 어수선하거나 주인공이 작은 사진(작게 가운데 두고 정면 풍경으로 바꿉니다)

**잘 맞지 않아요**

- 색, 빛, 분위기에 기대는 사진: 노을, 네온 야경 등(검은 선뿐입니다)
- 강한 원근감, 사실적인 건축 선화, 풍부한 장식 디테일을 원하는 경우
- 화면을 가득 채우거나 채색, 해칭 음영을 넣고 싶은 경우

## 샘플

아래 이미지는 모두 이 Skill이 사진 한 장으로 만든 완성작입니다. 위아래 비교와 좌우 비교는 서로 다른 사진을 썼습니다.

### 위아래 비교: 위 사진, 아래 디자인

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 352 · 01 · 골목 카페"><br><sub>01 · 골목 카페</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 352 · 02 · 작은 서점"><br><sub>02 · 작은 서점</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-03.png" alt="XXD Panel 352 · 03 · 빵집 진열대"><br><sub>03 · 빵집 진열대</sub></td>
    <td width="50%"><img src="./assets/examples/sample-04.png" alt="XXD Panel 352 · 04 · 꽃집 앞"><br><sub>04 · 꽃집 앞</sub></td>
  </tr>
</table>

<details>
<summary>16장 더 보기</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 352 · 05 · 해변 오두막"><br><sub>05 · 해변 오두막</sub></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 352 · 06 · 시골 역"><br><sub>06 · 시골 역</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 352 · 07 · 공원 벤치"><br><sub>07 · 공원 벤치</sub></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 352 · 08 · 꽃바구니 자전거"><br><sub>08 · 꽃바구니 자전거</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 352 · 09 · 보트하우스"><br><sub>09 · 보트하우스</sub></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 352 · 10 · 시골 교회"><br><sub>10 · 시골 교회</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 352 · 11 · 빈티지 캠핑 트레일러"><br><sub>11 · 빈티지 캠핑 트레일러</sub></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 352 · 12 · 나무 다리"><br><sub>12 · 나무 다리</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-13.png" alt="XXD Panel 352 · 13 · 초가집"><br><sub>13 · 초가집</sub></td>
    <td width="50%"><img src="./assets/examples/sample-14.png" alt="XXD Panel 352 · 14 · 간식 수레"><br><sub>14 · 간식 수레</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-15.png" alt="XXD Panel 352 · 15 · 늘어선 우편함"><br><sub>15 · 늘어선 우편함</sub></td>
    <td width="50%"><img src="./assets/examples/sample-16.png" alt="XXD Panel 352 · 16 · 정원 창고"><br><sub>16 · 정원 창고</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-17.png" alt="XXD Panel 352 · 17 · 온실"><br><sub>17 · 온실</sub></td>
    <td width="50%"><img src="./assets/examples/sample-18.png" alt="XXD Panel 352 · 18 · 등대와 오두막"><br><sub>18 · 등대와 오두막</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-19.png" alt="XXD Panel 352 · 19 · 발코니 화분"><br><sub>19 · 발코니 화분</sub></td>
    <td width="50%"><img src="./assets/examples/sample-20.png" alt="XXD Panel 352 · 20 · 작은 부두"><br><sub>20 · 작은 부두</sub></td>
  </tr>
</table>

</details>

### 좌우 비교: 왼쪽 사진, 오른쪽 디자인

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-21.png" alt="XXD Panel 352 · 21 · 낡은 파란 문"><br><sub>21 · 낡은 파란 문</sub></td>
    <td width="50%"><img src="./assets/examples/sample-22.png" alt="XXD Panel 352 · 22 · 창가 화분"><br><sub>22 · 창가 화분</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-23.png" alt="XXD Panel 352 · 23 · 가로등"><br><sub>23 · 가로등</sub></td>
    <td width="50%"><img src="./assets/examples/sample-24.png" alt="XXD Panel 352 · 24 · 들판의 우편함"><br><sub>24 · 들판의 우편함</sub></td>
  </tr>
</table>

<details>
<summary>16장 더 보기</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-25.png" alt="XXD Panel 352 · 25 · 작은 집"><br><sub>25 · 작은 집</sub></td>
    <td width="50%"><img src="./assets/examples/sample-26.png" alt="XXD Panel 352 · 26 · 언덕 위의 탑"><br><sub>26 · 언덕 위의 탑</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-27.png" alt="XXD Panel 352 · 27 · 계단 골목"><br><sub>27 · 계단 골목</sub></td>
    <td width="50%"><img src="./assets/examples/sample-28.png" alt="XXD Panel 352 · 28 · 나무 그네"><br><sub>28 · 나무 그네</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-29.png" alt="XXD Panel 352 · 29 · 오래된 우물"><br><sub>29 · 오래된 우물</sub></td>
    <td width="50%"><img src="./assets/examples/sample-30.png" alt="XXD Panel 352 · 30 · 돌탑"><br><sub>30 · 돌탑</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-31.png" alt="XXD Panel 352 · 31 · 정원 쪽문"><br><sub>31 · 정원 쪽문</sub></td>
    <td width="50%"><img src="./assets/examples/sample-32.png" alt="XXD Panel 352 · 32 · 풍향계"><br><sub>32 · 풍향계</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-33.png" alt="XXD Panel 352 · 33 · 사와로 선인장"><br><sub>33 · 사와로 선인장</sub></td>
    <td width="50%"><img src="./assets/examples/sample-34.png" alt="XXD Panel 352 · 34 · 나무 한 그루"><br><sub>34 · 나무 한 그루</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-35.png" alt="XXD Panel 352 · 35 · 벽시계"><br><sub>35 · 벽시계</sub></td>
    <td width="50%"><img src="./assets/examples/sample-36.png" alt="XXD Panel 352 · 36 · 새집"><br><sub>36 · 새집</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-37.png" alt="XXD Panel 352 · 37 · 등불"><br><sub>37 · 등불</sub></td>
    <td width="50%"><img src="./assets/examples/sample-38.png" alt="XXD Panel 352 · 38 · 문 앞 자전거"><br><sub>38 · 문 앞 자전거</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-39.png" alt="XXD Panel 352 · 39 · 문간의 고양이"><br><sub>39 · 문간의 고양이</sub></td>
    <td width="50%"><img src="./assets/examples/sample-40.png" alt="XXD Panel 352 · 40 · 화분 선반"><br><sub>40 · 화분 선반</sub></td>
  </tr>
</table>

</details>

## 이렇게 말하면 됩니다

파라미터를 외울 필요 없이 그대로 말하세요:

| 원하는 것 | 이렇게 말하기 |
|---|---|
| 위아래 비교 | 3:4 위아래 비교로 만들어 줘 |
| 좌우 비교 | 16:9 좌우 비교, 왼쪽에 사진 |
| 디자인만 | 사진 없이 디자인만, 9:16 세로 |
| 배경화면 세트 | 휴대폰, 태블릿, PC, 워치 배경화면을 통일된 세트로 |
| 여러 비율 | 같은 사진으로 1:1, 3:4, 16:9 한 장씩 |
| 내 글자 그대로 | 제목은 「바람이 지나가는 곳」, 한 글자도 바꾸지 마 |
| 글자 없음 | 글자는 하나도 넣지 마 |
| 글자 언어 | 글자는 일본어로 |
| 폴더 전체 | 이 폴더의 사진을 전부 위아래 비교로 |
| 지난번과 같이 | 지난번 설정 그대로 |

명령줄이 편하다면 파라미터가 위와 일대일로 대응합니다:

```text
/xxd-panel-352 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale ko-KR
/xxd-panel-352 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-352 ./photos --mode left-right --size 16:9 --text prompt --locale en-US
```

전체 파라미터는 [파라미터 목록](#파라미터-목록)에 있습니다.

## 자주 묻는 질문

**원본 사진이 꼭 들어가나요?** 아니요. "디자인만"이나 배경화면을 고르면 화면 전체가 디자인입니다.

**글자는 누가 쓰나요?** 기본적으로 이미지 모델이 사진을 보고 쓰고, 여러분은 언어만 고릅니다. 직접 쓴 글자를 주면 한 글자도 바꾸지 않고, 글자 없이도 만들 수 있습니다. 사실처럼 보이는 정보(지명, 날짜, 숫자)는 여러분이 준 것이나 사진에 보이는 것만 쓰고 지어내지 않습니다.

**마음에 들지 않으면요?** "한 장 더"라고 하세요. 이전 결과를 고치는 대신 원본 사진에서 다시 그리므로 매번 결과가 다릅니다.

**여러 장을 한꺼번에 하면 섞이지 않나요?** 섞이지 않습니다. 사진마다 따로 생성하고 다른 사진의 색, 글자, 구도를 빌리지 않습니다. 설정은 한 번만 묻습니다.

**제 사진은 어디로 가나요?** 에이전트가 쓰는 이미지 모델로만 갑니다. Skill은 다른 곳에 올리지 않고 접속 주소나 키도 표시하지 않습니다.

**다른 Panel과는 어떤 관계인가요?** XXD Panel은 번호마다 스타일이 하나씩인 독립된 모음입니다. 마음에 드는 것만 설치해도 됩니다. 사진에 맞는 스타일을 AI가 추천하게 하거나 여러 개를 비교하려면 카탈로그 [xxd-panel-all](https://github.com/nevertoday/xxd-panel-all)을 쓰세요.

## 원본 프롬프트

이 스타일은 샤오샤오둥이 쓴 [원본 프롬프트](references/original-prompt/zh-CN.md)(중국어)만으로 정해집니다. Skill은 여러분이 고른 레이아웃, 크기, 글자 설정을 뒤에 덧붙일 뿐, 요약하거나 번역하거나 고쳐 쓰지 않습니다.

참고 번역(읽기용이며 이미지 생성에는 쓰지 않음): [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## 이미지 생성 설정

`gpt-image-2`(또는 호환 모델)를 제공하는 OpenAI 호환 API와 그 API 키가 필요합니다. 아래 방법은 별도 설정을 만들어 Codex 자체 설정에는 영향을 주지 않습니다:

```bash
mkdir -p ~/.xxd-imagegen
cat > ~/.xxd-imagegen/config.toml <<'EOF'
model_provider = "image"

[model_providers.image]
base_url = "https://api.openai.com/v1"   # 또는 호환 엔드포인트
env_key = "XXD_IMAGE_API_KEY"
EOF

# ~/.zshrc 또는 ~/.bashrc에 넣어 에이전트도 읽을 수 있게
echo 'export XXD_IMAGEGEN_CODEX_DIR=~/.xxd-imagegen' >> ~/.zshrc
echo 'export XXD_IMAGE_API_KEY=내-키' >> ~/.zshrc
```

터미널과 에이전트를 다시 연 뒤, 이 Skill 폴더에서 한 번 확인하세요:

```bash
python3 scripts/configured_imagegen.py probe
```

`"ok":true`가 나오면 성공입니다. 사용 가능 여부만 보여 주고 주소나 키는 출력하지 않습니다. Codex가 이미 호환 API로 이미지를 만들고 있다면 이 단계는 필요 없습니다.

## 파라미터 목록

| 파라미터 | 값 |
|---|---|
| `--mode` | `top-bottom` 위아래 비교 · `left-right` 좌우 비교 · `design-only` 디자인만 · `wallpaper-pack` 4종 배경화면; 여러 개 선택 가능 |
| `--size` | `auto` 추천 · `source` 사진 비율 · `1:1` `3:4` `4:3` `4:5` `5:4` `2:3` `3:2` `9:16` `16:9` `21:9` `5:7` `7:5` · 정확한 픽셀(예 `2160x3840`); 여러 개 선택 가능 |
| `--text` | `prompt` 사진을 보고 작성 · `exact` 내 글자 그대로(`--copy "…"`와 함께) · `none` 글자 없음 |
| `--locale` | 글자 언어. 예: `zh-CN` `en-US` `ja-JP` `ko-KR` `ar` |
| `--wallpaper` | `linked` 통일된 세트 · `independent` 네 장 각각 독립 |
| `--wallpaper-size` | 기기별 픽셀. 예: `phone=1440x3200,desktop=3840x2160` |
| `--out` | 출력 루트 변경(기본 `~/Desktop/xxd/xxd-panel-352/`) |
| `--prefs` | `last` 지난번 그대로 · `edit` 지난번에서 수정 · `new` 새로 고르기 · `off` 이번엔 기억 안 함 · `clear` 기록 삭제 |

- 값이 모두 있으면 묻지 않고, 빠진 것만 묻습니다. `photo.jpg` 대신 폴더를 주면 일괄 처리합니다.
- 조합은 한 장씩 생성합니다. 모드 2개 × 크기 3개 = 6장이며, 잘라 낸 것이 아니라 캔버스마다 구도를 새로 잡습니다.
- 비교 이미지는 정확히 50:50입니다. 보통 모델은 디자인 쪽만 그리고 스크립트가 원본 사진을 그대로 옆에 붙이므로, 경계는 가운데이고 사진은 바뀌지 않습니다.
- 파일 이름은 `source-001-street-top-bottom-3x4-1152x1536.png` 형식이며 모두 작업 폴더 하나에 평평하게 저장됩니다.
- 레이아웃, 크기, 글자 방식과 언어만 기억하고 사진, 문구, 키는 저장하지 않습니다.

<!-- xxd-readme-ads:start -->
## XXD 소개

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 이 프로젝트는 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01)이 만들고 관리합니다.

## Xiaoxiaodong 멀티플랫폼 멤버십 · CNY 699/년

> **광고 안내:** 아래 QR 코드와 멤버십·유료 서비스 링크는 XXD의 홍보 정보입니다. 스캔이나 구매는 선택 사항이며 오픈 소스 이용에는 영향을 주지 않습니다.

연간 멤버십 하나로 **Knowledge Planet + XXD 회원 프롬프트 라이브러리 + 모든 General Skills 멤버십**을 함께 이용할 수 있습니다. 각각 따로 구매할 필요가 없습니다.

<!-- xxd-panel-command-system:start -->

### Skills가 함께 작동하는 방식

| 등급 | 포함 내용 | 역할 |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 사용 가능한 번호형 Skills를 찾고, 이미지·주제·용도에 맞춰 추천하며, 여러 스타일과 일괄 작업을 정리합니다. |
| **Soldier** | `xxd-panel-NNN` | 각 번호가 고유한 원본 프롬프트와 미학에 따라 General이 배정한 구체적인 작업을 완성합니다. |

<!-- xxd-panel-command-system:end -->

### 회원 혜택

1. **WeChat 일대일 AI 학습·프로젝트 상담**
   아래 QR 코드로 Xiaoxiaodong의 WeChat을 추가해 AI 학습, 도구, 실제 프로젝트를 일대일로 상담하고 실용적인 답변과 안내를 받을 수 있습니다. 대표적인 질문은 회원 자료로 정리됩니다.
2. **계속 업데이트되는 회원 프롬프트 라이브러리**
   [XXD 회원 프롬프트 라이브러리](https://vip.xiaoxiaodong.ai/)에는 현재 약 3만 2천 개의 프롬프트가 있으며, 10만 개 이상을 목표로 계속 확장합니다.
3. **모든 General Skills와 사용 지원**
   하나의 멤버십으로 모든 General Skills를 이용하고, 사용 중 도움이 필요할 때 안내와 Q&A를 받을 수 있습니다.
4. **필요성이 높은 요청을 우선 검토**
   회원이 제안한 수요가 높고 꼭 필요한 프롬프트와 Skills는 우선 검토하고 개발합니다.

### 가입 방법

- [회원 웹사이트에서 직접 가입](https://vip.xiaoxiaodong.ai/)할 수 있습니다.
- 또는 아래 QR 코드로 Xiaoxiaodong의 WeChat을 추가해 일대일 가입 지원을 받을 수 있습니다.

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Xiaoxiaodong 연락처" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## 라이선스

이 프로젝트(Skill, 프롬프트, 스크립트, 문서, 함께 제공되는 샘플 이미지 포함)는 **PolyForm Noncommercial License 1.0.0**을 따릅니다. 전체 법률 문구는 [LICENSE](LICENSE), 공식 페이지는 <https://polyformproject.org/licenses/noncommercial/1.0.0>에서 확인하세요.

쉽게 말하면 다음과 같습니다.

- 개인은 학습, 연구, 실험, 테스트, 취미 프로젝트, 사적 오락에 사용할 수 있습니다. 자선 단체, 교육 기관, 공공 연구·안전·보건 기관, 환경보호 단체, 정부 기관도 사용할 수 있습니다.
- **비상업적 목적**이라면 사용, 복사, 수정, 파생 작업 제작, 공유가 가능합니다. 공유할 때는 이 라이선스(또는 위 링크)와 저자가 제공한 모든 `Required Notice:` 문구를 함께 제공해야 합니다.
- 상업 제품이나 서비스, 유료 납품, 접근권 또는 라이선스 판매, 상업적 적용으로 이어질 것으로 예상되는 용도에는 사용할 수 없습니다. 상업적으로 사용하려면 저작권자에게 별도의 서면 허가를 받아야 합니다.
- 이 계약은 명시된 저작권 라이선스와 제한된 특허 라이선스만 부여합니다. 상표, 브랜드명 또는 명시되지 않은 다른 권리를 부여하지 않으며 라이선스를 제3자에게 재허여할 수도 없습니다.
- 서면으로 위반 통지를 받으면 32일 안에 준수 상태로 돌아가고 실질적인 시정 조치를 해야 하며, 그렇지 않으면 라이선스가 즉시 종료됩니다. 특허 침해를 서면으로 주장해도 특허 라이선스가 종료됩니다.
- 콘텐츠는 법이 허용하는 범위에서 어떠한 보증도 없이 “있는 그대로” 제공됩니다. 사용에 따른 위험과 잠재적 손실은 사용자가 부담합니다.

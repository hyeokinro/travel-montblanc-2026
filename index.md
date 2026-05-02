---
layout: default
---

<div id="dday" style="text-align:center; background:linear-gradient(135deg,#1a5276,#2e86c1); color:white; padding:1rem; border-radius:8px; margin-bottom:1.5rem; font-size:1.1rem;">
  <span id="dday-text">Loading...</span>
</div>
<script>
(function(){
  var dep = new Date(2026, 4, 28, 23, 35); // 5/28 23:35 출발
  var now = new Date();
  var diff = Math.ceil((dep - now) / (1000*60*60*24));
  var el = document.getElementById('dday-text');
  if(diff > 0) el.textContent = '✈️ 출발까지 D-' + diff;
  else if(diff === 0) el.textContent = '✈️ 오늘 출발!';
  else el.textContent = '🏔 여행 중!';
})();
</script>

## 여행 구성

| 그룹 | 기간 | 멤버 |
|------|------|------|
| **A** | 5/28 출발 ~ 6/3 HY 귀국 | H, J, S(14개월), HY |
| **B** | 6/3 저녁 ~ 6/5 | H, J, S |
| **C** | 6/5 출발 ~ 6/12 귀국 | H, J, S, JH, HS |

> H=남편, J=배우자, S=아기, HY=장모님, JH=어머니, HS=이모

## 일정 한눈에 보기

| 날짜 | 일정 |
|------|------|
| 5/29(목) | 🛬 GVA 도착 → 렌터카 → 까르푸 → 숙소 |
| 5/30(금) | 레우쉬 적응 + **메제브** |
| 5/31(토) | **에귀 뒤 미디** + **Lac de Passy** |
| 6/1(일) | **안시** 당일치기 |
| 6/2(월) | **골프** + **트램웨이** |
| 6/3(화) | **제네바** + HY 배웅 |
| 6/4(수) | 휴식일 |
| 6/5(목) | 휴식 + 어른맞이 준비 |
| 6/6(금) | 🛬 JH/HS 마중 + 적응 |
| 6/7(토) | **샤모니** 종일 관광 |
| 6/8(일) | **쿠르마요르🇮🇹** |
| 6/9(월) | **안시** 당일치기 |
| 6/10(화) | **트램웨이** + **Lac de Passy** + 짐정리 |
| 6/11(수) | 체크아웃 → 렌터카 반납 → **제네바🇨🇭** → 🛫 귀국 |

> 🌍 3개국 경험: 🇫🇷 프랑스 + 🇮🇹 이탈리아(쿠르마요르) + 🇨🇭 스위스(제네바)
>
> 📝 일정은 현지 적응 상황에 따라 유연하게 변경할 예정

---

## 📑 상세 페이지

| 페이지 | 내용 |
|--------|------|
| [📋 할 일 (TODO)](docs/todo) | 시기별 할 일, 예약, 연락, WhatsApp 템플릿 |
| [🧳 준비물](docs/packing) | 여행 준비물, 한식 준비물, 식품 검역 규정 |
| [✅ 이동 체크리스트](docs/moving-checklist) | 항공, 렌트, 숙소, 이동 절차 |
| [📅 일별 일정](docs/itinerary) | 상세 일정 + 현지 시설(위치, 운영시간, 비용) |
| [🚼 카시트 가이드](docs/carseat) | Evenflo Tribute 4단계 설치 (한/영) |
| [🛂 출입국 카드](docs/immigration-cards) | 어르신용 영어 안내 카드 (입국/출국 심사용) |
| [🥩 식료품 구매 가이드](docs/grocery-guide) | 고기 부위 한↔불 비교, 채소, 정육코너 실전 팁 |
| [🍼 현지 아기용품](docs/baby-shopping) | 까르푸 이유식, 기저귀, 약국 구매 가이드 |
| [🆘 비상/현지정보](docs/emergency) | 비상연락처, 운전, 날씨, 유용한 앱 |

---

*마지막 업데이트: 2026-04-22*

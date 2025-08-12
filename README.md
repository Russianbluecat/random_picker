# 🎯 랜덤 뽑기(Random Picker)

> Google Colab으로 random 뽑기 code를 짰는데 이걸 웹 구현해보고 싶어서
>
> Claude의 도움을 받았습니다.
> 
> **누구나 간단하게** 항목을 입력하고 원하는 개수를 랜덤으로 추첨할 수 있는 웹 앱입니다.  
> 깔끔한 UI, 실시간 방문자 카운트, 모바일 대응까지 완료!

🔗 **바로 사용하기:** [https://random-picker-one.vercel.app/](https://random-picker-one.vercel.app/)

---


## ✨ 주요 기능

- **단계별 진행**
  1. 항목 입력 (중복 방지 / 항목 삭제 가능)
  2. 입력 내용 확인 (진행 여부 선택)
  3. 뽑을 개수 입력 (유효성 검증)
  4. 카운트다운 → 결과 출력

- **UI/UX**
  - 반응형 디자인 (모바일/PC 지원)
  - 부드러운 애니메이션
  - 태그 형태 항목 표시

- **방문자 카운터**
  - 오늘 방문자 수
  - 누적 방문자 수  
  *(CountAPI 사용)*

---

## 🚀 사용 방법

1. **웹페이지 접속**
   - [랜덤 뽑기 사이트](https://random-picker-one.vercel.app/)로 이동합니다.

2. **항목 입력**
   - 입력창에 항목을 하나씩 작성 후 `Enter` 키 입력
   - 빈 입력 상태에서 `Enter` → 입력 완료 단계로 이동

3. **확인 & 뽑을 개수 선택**
   - 입력된 항목 확인 후 진행 여부 결정
   - 뽑을 개수 입력

4. **결과 확인**
   - 3초 카운트다운 후 당첨 결과 표시

---

## 🛠 기술 스택

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Hosting:** Vercel
- **Analytics:** Google Analytics (gtag.js)
- **Visitor Counter:** CountAPI

---

## 📂 로컬 실행 방법

```bash
# 저장소 클론
git clone https://github.com/사용자명/random-picker.git

# 폴더 이동
cd random-picker

# 브라우저에서 index.html 열기


# 모두를 위한 학교 콘서트장 설계하기 v16

독립 폴더 `eco_concert_designer_v16`에서 실행합니다. 기존 v15 데이터베이스는 변경하지 않습니다.

## 변경 사항
- 설계 안내 문구를 설계도 위에 표시하고 줄바꿈·여백을 보완하여 글자 잘림을 수정했습니다.
- 로그인 화면의 불필요한 독립 프로젝트 설명을 제거했습니다.
- 「강당 크기 및 관객 수 설정」은 연두색, 「학생이 원하는 시설 추가하기」는 연노란색 카드로 구분했습니다.
- 왼쪽 하단 「로그아웃」 버튼을 진한 빨간색에 흰색 글씨로 변경했습니다.
- 설계도 PDF 내려받기 버튼은 기존 노란색을 유지합니다.

## 실행
```powershell
cd "C:\Users\jh869\Desktop\eco_concert_designer_v16"
C:\Users\jh869\envchat\.venv\Scripts\python.exe -m pip install -r requirements.txt
C:\Users\jh869\envchat\.venv\Scripts\python.exe -m streamlit run app.py --server.port 8516
```
브라우저: http://localhost:8516

초기 계정: `teacher / 999999`, `team1 / 111111` ~ `team6 / 666666`.
기존 로그인·설계 저장·챗봇·PDF 평가 기능은 그대로 유지합니다.
학교 내 서버에서 6모둠 동시 사용과 화면 배율별 표시 여부는 실제 환경에서 점검하세요.

# data-study
## 개요
- 논문을 작성하기 전 데이터를 수집, 가공, 시각화하는 법에 대한 스터디

## 목표 
- 싸지방에서 논문 하나 써서 연말까지 투고하는 걸 목표로 해보자!
- 국내 학술지 하나를 목표로 쓰면 실적을 꼭 낼 수 있을 것으로 생각함. 

## 공부할 내용
- 데이터 수집
    + 파이썬 웹 스크래핑: 유데미 강좌 (scrpay) 및 아마존에서 평점이 좋은 책 1권 같이 공부해보면 좋을 듯! 
    + API 사용법: 데이터를 API 형태로 제공하는 곳이 많음. (ex. [공공데이터 포털](https://www.data.go.kr/)). 따라서 API 사용법을 익힐 필요가 있음
- 데이터 가공
    + pandas: 주로 데이터프레임을 다루기 위한 파이썬 라이브러리. 판다스 역시 유데미 강의를 하나 구매하거나 책을 하나 정해서 죽어라 파면 도움이 많이 됨. 판다스는 데이터 클리닝 작업에 아주 핵심적인데 판다스와 같이 Python Data Cleaning Cookbook
         이라는 책도 추천함. 
    + numpy: n차원 배열(array)를 다루기 위한 파이썬 라이브러리. 행렬을 다루기 위해 필요한 도구임. 파이썬 기본 라이브러리의 list보다 50배 빠른 연산을 가능하게 함
- 데이터 시각화
    + matplotlib: 그래프를 그리기 위한 도구. 자유도가 높음
    + seaborn: matplotlib을 기반으로 만들어진 도구. 상대적으로 자유도가 낮은 대신 간결하고 효율적으로 시각화 가능

## Python x VSC x pylint 
- 가상환경을 설정해놓고 거기에 패키지를 깔아놓으면 각각의 가상환경에서 셋팅해놓은 설정값 안에서 돌아가기 때문에 충돌이 벌어지지 않음
   + 유용한 링크: https://ddochea.tistory.com/33
- 작성한 코드를 자동적으로 변환해주는 프로그램 (formatting)이나 오타가 발생할 때마다 잡아주는 lint를 알아두면 협업에 유리하고 다른 사람들이 쉽게 이해할 수 있는 코드 작성이 가능함
   + 유용한 링크: https://jhyeok.com/python-with-vscode/

## 재현 가능한 연구 (replicable study)
- 기존의 연구자들이 자신들의 연구결과까지 도출하기 위한 (1) 컴퓨팅 환경 (e.g., 패키지 버전, 라이브러리 버전, docker처럼 아예 독립적인 가상환경을 만들어서 똑같이 재현가능하게 함), (2) 데이터 셋, (3) 코드를 완벽하게 공개하지 않았다면, 최근의 저널들은 재현 가능한 연구를 위해 세 가지 조건을 모두 공개하는 것을 권장함. 공개를 하는 것과 별개로 다른 사람들이 이해하기 쉽고 연구자 개인이 프로젝트를 작은 단위로 쪼개서 매니지하기 위한 능력이 너무나도 중요함. 
   + 유용한 링크 [1]: https://python-guide-kr.readthedocs.io/ko/latest/writing/structure.html
   + 유용한 링크 [2]: https://ddochea.tistory.com/33](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)
   + 유용한 링크 [3]: https://medium.com/the-stata-guide/the-stata-workflow-guide

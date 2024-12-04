#파이썬 머신러닝 수업

### 설치

pip install pandas scikit-learn seaborn graphviz
pip install pandas==24.3.1 버전 변경

pip list 라이브러리 설치리스트

## 결정트리 (초기모델로 좋다!!)
  - 전처리 필요없다
  - 특성 중요도를 알수있다
  - 속도가 빠르다

  초기모델로 결정트리 선택 후 예측 및 개선 진행
   - 전처리 + 변경

  과대적합 문제가 있다 (과소적합의 경우 data를 더 구해오면 된다.)
    - 매개변수를 제한시킨다.

## 함수
  - 함수이름 > 규칙에 맞게
  - 매개변수 > 없는게 좋다 
  - 반환값   > 있는게 좋다

print(f"특성 : {len(X)}, 타깃 : {len(y)}") 이 방식이 빠르고 메모리 적게 먹는다. 
print("특성 : ", len(X), "타깃 : ",len(y))


## pandas
 - 기초통계정보를 출력하라 > pandas로 변경해서 데이터 출력


# 파이썬
  - 함수 만드는거
  - 함수 사용
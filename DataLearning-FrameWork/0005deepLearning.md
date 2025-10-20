# DeepLearning - 딥러닝
---
**핵심**
- tensorflow.keras이라는 모듈 활용


---
## 데이터 전처리
1. 가변수화
```
# 라벨링

# 힛인코딩
```

2. 데이터 분리
```
from sklearn.model_selection import train_test_splict
```


3. 스케일링
```
import 
```
## 모델링 
1. 설치하기
```
from tensorflow.kears.models import Sequential


```

2. 선언하기
```
from tensorflow.kears.layers import Input, Dense
from tensorflow.kears.backend import clear_session
```

3. 학습하기
```
from tensorflow.kears.mooptimizers import Adam

```

4. 예측하기


5. 평가하기
```
# 회귀형
## 절대값과 오차
from sklearn.metrics import mean_absoulte_error
## 절대값과 오차 제곱
from sklearn.metrics import mean_squared_error
## 절대값과 오차 퍼센트
from sklearn.metrics import mean_absoulte_percentage_error
## r2 점수
from sklearn.metrics import r2_score

# 분류형
## f1 점수
from sklearn.metrics import f1_socore
## 리콜, 정확도 정도
from sklearn.metrics import confusion_matrix
## f1, 리콜, 정확도 종합 정도
from sklearn.metrics import classification_report


```
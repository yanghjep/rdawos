# rdawos

`rdawos`은 **RD**A **AWOS**의 약자입니다. `농촌진흥청(RDA)`이 운영하는 `농업기상관측기(AWS)`의 관측(또는 집계) 자료에 대한 접근성을 높이는 것을 목표로합니다.



## 사용법


```python
import pandas as pd
```



```python
# 기상관측지점목록

pd.read_csv(f'https://raw.githubusercontent.com/yanghjep/rdawos/master/stations/rda.stations.csv')
```



```python
# 2021년01월01일 기상관측 전제지점 자료

pd.read_csv(f'https://raw.githubusercontent.com/yanghjep/rdawos/master/daily/2021/01/01/rdadaily.2021-01-01.csv')
```



```python
# 서울시 서초구(137180A001)의 2021년 기상관측자료

pd.read_csv(f'https://raw.githubusercontent.com/yanghjep/rdawos/master/pointly/137180A001/2021/137180A001.2021.csv')
```

## pyrdawos

`pyrdawos`(Python RDA AWOS)를 이용하면 파이썬을 사용해 데이터를 조회할 수 있습니다.
[사용법](https://github.com/yanghjep/pyrdawos/blob/main/README.md)을 참고하시기 바랍니다.


## 출처

> 본 저작물은 [농촌진흥청 국립농업과학원](https://www.naas.go.kr/)에서 작성하여 공공누리 제1유형으로 개방한 `농업기상관측`을 이용하였으며,
해당 저작물은 [농업날씨365](https://weather.rda.go.kr/)에서 무료로 다운받으실 수 있습니다.

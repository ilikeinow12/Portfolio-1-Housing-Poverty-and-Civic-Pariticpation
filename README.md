# Abstract 

### Intro
- 본 분석은 본인의 서울대 사회학과 석사학위 논문에 사용한 자료를 재구성한 것임. 
- 본 분석에서 이용된 데이터는 <서울시 복지실태조사(2018), 서울연구원>임.본래 논문에서는 2015년도 데이터를 사용했지만 2018년 데이터가 업로드되어 2018년 데이터로 재구성함. 
- 본래 논문의 목적은 여러 요인들을 통제한 후 주거빈곤과 지역사회참여율 간의 선형관계를 확인하는 것이나, 본 분석에서는 지역사회참여율과 다른 요인들 간의 상관관계를 살펴보는 것으로 한정함. 

### 문제 제기  
- 주거 문제를 한국에서는 개개인의 불평등 관점에서만 논하는 한계가 존재. 
- 주거안정성과 개인의 사회참여, 정치참여 대한 한국적 맥락에서의 연구 부족.  
- 특히 서울에 1인가구가 급증하는 상황에서 이 1인가구들의 주거안정성의 파생 결과에 대한 논의 부족.

### 가설 설정
- 주거빈곤이 높을수록 지역사회에 대한 서울시민의 참여도나 참여의향이 떨어질 것이다. 


### 분석과정
1) Data importing : 서울연구원, 서울시복지싵태조사  
2) Data Preprocessing : 분석에 필요한 컬럼들 생성  
3) Data Description(Visualization) : 분석 대상인 설문 응답자들의 features를 시각화하여 응답자들의 특성 파악  
4) Data Analysis : features간 상관관계 여부 확인, 회귀 분석 진행  
5) Conclusion : 분석 결과 정리

### 분석 결론 
- 본 논문은 서울시를 대상으로 주거 빈곤, 주거 요인이 넓게는 지역 사회 통합을, 좁게는 시민들의 지역 사회 참여에 어떤 관계가 있는지 알아보고자 하였다.  
- 서울시 복지 실태 조사를 통해 주거 요인 - 주거 점유 형태, 거주 건물 유형, 주거 빈곤 지수(슈바베 지수)-와 가구 특성(1인가구, 다인가구, 그외)을 다른 인구, 사회경제적 요인과 회귀 분석한 결과, 주거 요인과 가구 특성은 통계적으로 유의한 영향을 미치는 것으로 나타났다.  
구체적으로 다인가구는 1인가구에 비해 지역 사회에 참여 했을 확률이 높았고, 전월세는 자가에 비해 지역 사회에 참여 했을 확률이 낮았다. 한편 기타 유형은 자가에 비해 오히려 확률이 높았다. 다가구/다주택/오피스텔에 사는 사람들은 아파트에 사는 사람들에 비해 지역 사회에 참여 했을 확률이 낮았다.  
  
- 이는 곧 주거 문제를 단순히 개개인의 불평등 문제가 아니라 사회 통합의 문제에서도 바라보아야 한다는 점을 시사한다. 지금까지 주거 정책은 1가구 1주택 등의 슬로건과 함께 주거 문제를 재산권의 문제로만 인식하는 한계를 보여주고 있는데, 그 외에도 이웃간의 연대나 공동체 관점도 추가하여 재편해야 함을 논문을 통해 주장하는 바이다. 

--------------------------------------------------------------------------------------------------------

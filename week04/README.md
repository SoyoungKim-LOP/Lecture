# Overview of week04

> **제목:**  Python을 활용한 시각화 내용 정리(4주차)
>
> **목적:** Pandas를 통한 탐색적 데이터 분석을 수행한 후, 시각화를 통해 데이터에 대한 이해도를 높여보자!! 



> 참고내용 및 참고사이트:
>
> (1) Seaborn(SNS)를 사용한 파이썬 데이터 시각화 기초 matplotlib: https://chancoding.tistory.com/12  
>
> (2) 네이버주식차트 가져오기: https://stricky.tistory.com/200 (좀 설명이 안좋음)
>
> (3) 파이차트 matplotlib를 이용하여 만들기: https://zephyrus1111.tistory.com/34
>
> (4) Figure.savefig_matplotlib.figure.Figure 타입 :
>
> ​     - 지원포맷: eps, pdf, pgf, png, ps, raw, rgba, svg (dpi=75 디폴트, 고품질=300)

### [1] Excel_with_pandas: Pandas를 활용한 데이터 시각화 및 엑셀에 반영하는 방법

> 내용:

   - 스타일적용: plt.style.use('fast')
   - 라인플롯 그리기: df.plot()
   - 바차트 그리기: df.plot(kind='bar'), df.plot(kind='barh')
   - 산포도 그리기: df.plot(kind='scatter', x=x축값, y=y축값)
   - 파이차트 그리기: df.plot(kind='pie', y=레이블값)
   - 그래프 저장하기:  figure.savefig('파일명', dpi=300)
   - seaborn 사용하기: seaborn을 활용한 데이터프레임 엑셀에 반영하기 



### [2] Visualization: 주식 실시간 데이터 시각화하기





### [3] Dashboard_in_Excel: 주식 실시간 데이터로 엑셀 대시보드 만들기





### [4] sample_codes: 학습에 사용한 실습 코드 예





>  다양한 시각화 라이브러리: 
>
> - **정적이미지 생성 :**  Matplotlib, Seabron 등
> - **Interactive 시각화 라이브러리 :** Bokeh, d3py 등



#### 참고: anaconda를 통해 필요한 라이브러리:

> pandas: 데이터 전처리|분석 라이브러리
>
> matplotlib/seaborn: 시각화 라이브러리
>
> xlwings: 엑셀 UI 자동화 라이브러리
>
> scikit-learn: 머신러닝 라이브러리
>
> requests: HTTP 요청 라이브러리
>
> beautifulsoup4: HTTP 파서 라이브러리
>
> tqdm: 진행상태 표시 라이브러리

### 












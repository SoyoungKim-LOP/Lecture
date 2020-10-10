# Overview of week04

> **제목:**  판다스를 통하여 엑셀에 데이터프레임과 그래프 반영하는 방법
>
> **목적:**   
>
> (1) 판다스를 통한 엑셀에 데이터프레임에 그래프 반영하는 방법을 수행  
>
> (2) 그래프를 그려서 탐색적데이터 분석을 수행  
>
> (3)  데이터간의 영향을 알아보기 위한 파생변수 활용한  탐색적 분석 수행  



**[ 느낀점 ]**

데이터 분석에 필요한 그래프 그리는 방법을 알수 있었으나, 데이터간의 분석력을 높이기 위한 해당 분야의 산출된 데이터의 내용을 아는 것도 중요하다는 것을 경험할 수 있었음. 

 

### [1] Excel_with_pandas: Pandas를 활용한 데이터 시각화 및 엑셀에 반영하는 방법

> 내용:

   - 스타일적용: plt.style.use('fast')
   - 라인플롯 그리기: df.plot()
   - 바차트 그리기: df.plot(kind='bar'), df.plot(kind='barh')
   - 산포도 그리기: df.plot(kind='scatter', x=x축값, y=y축값)
   - 파이차트 그리기: df.plot(kind='pie', y=레이블값)
   - 그래프 저장하기:  figure.savefig('파일명', dpi=300)
   - seaborn 사용하기: seaborn을 활용한 데이터프레임 엑셀에 반영하기 



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
















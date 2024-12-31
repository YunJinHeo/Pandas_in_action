# Pandas_in_action 
It is about studying the book "Pandas in Action" written by Boris Paskhaver 

I used the data in https://github.com/paskhaver/pandas-in-action

## chapter_01_introducing_pandas
 DataFrame, Series, read_csv 등 판다스 라이브러리에 대한 전반적인 내용을 훑어보았다.

## chapter_02_the_series_object
 Series 는 index와 value를 갖는 1차원 레이블 배열로 List, Dictionary, tuple, numpy array 등으로 값을 채울 수 있다.
 
 .head() .tail()로 처음과 마지막 몇 행을 출력할 수 있다.
 
 .sum() .mean() .median() .std() 등을 이용해 각 값에 통계 연산을 적용시킬 수 있다.
 
## chapter_03_series_methods
 read_csv를 이용해 csv파일을 pandas dataframe으로 가져올 수 있다.
 
 sort_value 와 sort_index 를 이용해 Series를 value, index를 기준으로 정렬할 수 있다.
 
 value_counts method를 통해 Series의 고유 value의 갯수를 구해낼 수 있다.
 
 apply method로 각 value에 함수를 적용시킬 수 있다.

## chapter_04_the_dataframe_object
 DataFrame은 행과 열로 구성된 2차원 자료구조이다. 
 
 loc와 iloc를 이용해서 특정 행이나 열을 추출할 수 있다.
 
 reset_index 를 이용하여 index를 하나의 열로 바꿀 수 있다.

## chapter_05_filtering_a_dataframe
 astype method를 이용해서 series의 데이터 유형을 변경하고 이를 이용해 사용 메모리를 줄일 수 있다.
 
 &, |, < 등을 이용해서 논리연산을 적용시킬 수 있다.
 
 fillna, dropna를 이용하여 NaN 값을 상수로 치환하거나 제거할 수 있다.

## chapter_06_working_with_text_data
 

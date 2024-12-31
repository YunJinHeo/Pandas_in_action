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
 str의 .upper() .lower() .capitalize() 등을 이용하여 문자열의 대소문자를 변환할 수 있다.
 
 contains(), startswith(), endswith() 등을 이용하여 문자열 내부에 특정 문자열이 있는지를 식별할 수 있다.
 
 split method를 이용하면 문자열을 리스트로 분할할 수 있다. 

## chapter_07_multiindex_dataFrames.
 MultiIndex를 이용해서 여러 레벨로 구성된 Index를 생성할 수 있으며 기본적인 동장은 일반적인 Index와 다르지 않다.

## chapter_08_reshaping_and_pivoting
 pivot_table method를 이용해 Dataframe의 특정 value를 집계할 수 있다.

 집계에는 합계, 개수, 평균 등 다향한 aggfunc을 할당할 수 있다.

 stack(), unstack()으로 열 인덱스와 행 인덱스 사이에 이동이 가능하다.

 melt() method를 사용하여 pivot 되어있는 넓은 데이터셋을 좁은 데이터셋으로 변환할 수 있다.

## chapter_09_the_groupby_object
 GroupBy object를 이용하여 특정 열 인덱스를 기준으로 행을 묶을 수 있다.

 first(), tail()로 각 group의 처음과 마지막 값을 불러올 수 있다.

 각 그룹에 대해 합계, 평균, 최대, 최소 등의 집계 연산을 적용시킬 수 있다.

 apply method를 이용해 각 그룹에 사용자 정의 함수를 적용시킬 수 있다.

## chapter_10_merging_joining_and_concatenating
 concat 함수를 이용하여 두 Dataframe을 연결할 수 있다.

 merge method를 이용하여 두 Dataframe을 조인할 수 있다.

 내부 조인(inner join)은 두 Dataframe의 공통된 값이 존재하는 경우에 오른쪽 Dataframe 값을 왼쪽 Dataframe으로 가져온다.

 외부 조인(outer join)은 두 Dataframe의 모든 값을 병합한다.

 왼쪽 조인(left join)은 왼쪽 Dataframe에 오른쪽 Dataframe 값을 가져오며 오른쪽 Dataframe에 공통된 값이 없어도 열을 삭제하지 않는다.

## chapter_11_working_with_dates_and_times
 pandas Timestamp object로 datetime object를 유연하게 다룰 수 있다.

 Timedelta object는 시간차를 모델링한다.

 pd.offsets 패키지를 이용하여 날짜를 가장 가까운 주, 월, 분기 등으로 변환할 수 있다.

## chapter_12_imports_and_exports
 read_json()과 json_normalize() 이용해 JSON 파일을 Dataframe으로 가져올 수 있다.

 read_excel()을 이용해 엑셀 통합문서를 가져올 수 있다. sheet_name 매개변수로 가져오고 싶은 sheet를 선택할 수 있다.

 DataFrame을 엑셀 통합문서로 저장하려면 ExcelWriter 객체를 인스턴스화하고 to_excel method로 Dataframe을 저장한 뒤에 ExcelWriter object에서 close() 를 호출하면 된다.



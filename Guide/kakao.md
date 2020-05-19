# kakao.py
###### ApiFunc/kakao.py의 레퍼런스 문서입니다.
- 함수
    + [getPlacePage](#getplacepage)
    + [getPlace](#getplace)
- 클래스

<br />

## getPlacePage
(함수의 목적에 대한 간단한 설명)  
```{.python}
def getPlacePage(str code, int y, int x, int rad, int page=1)
    if(rescode == 200): return (bool data['meta']['is_end'], list cafe, list dist)
    else: return (bool True, list cafe, list dist)
```

#### 매개변수
|이름|형식|자료형|명세|예시 입력|
|---|---|---|---|---|
|code|변수|string|(code 변수에 대한 간단한 설명)|"음식점"|
  
#### 반환형
|이름|형식|자료형|명세|비고|
|---|---|---|---|---|
|cafe|변수|list[]|(cafe 변수에 대한 간단한 설명)||
|dist|변수|list[ dictionary{ string:integer, string:integer }, ... ]|(dist 변수에 대한 간단한 설명)||

<br />

## getPlace

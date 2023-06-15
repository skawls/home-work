## Mission-05

- [Results](#results)
- [Description](#description)

## Results

1. sprite를 활용하여 배치하기

![grid](./../mission-01/assets/5%EB%B2%88%20%EA%B3%BC%EC%A0%9C.PNG)

## Description

- :
section 태그로 h2와 span태그를 감싸고 ol태그로 list를 구현 하였습니다.
  
```
html
│
main
├─ section
│      │ └─ h2
│      └─ span
│      
│
├─ol        
  ├─li     
  ├─li    
  ├─li  
  ├─li    
       

 ```
 ```
 과제내용
 - rank.png(webcafe-RWD/assets 폴더에 있음) 이미지를 활용하여 스프라이트 기법으로 스타일링 한다.
 - 각 인기 사이트의 순위를 나타내는 영역은 기존 <ol> 요소에서 제공하는 기본 숫자를 보이지 않도록 한 후 CSS로 구현한다.
 ```
 ```
 li요소에 ::before 가상 요소를 활용하여 스프라이트 이미지에 배경을 넣었고
 position을 사용하여 우측 끝으로 정렬하였습니다. 
 ```
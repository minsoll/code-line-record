
![자바스크립트 수강](https://user-images.githubusercontent.com/101937709/170771790-3b11250e-e2ab-4ab7-92a8-b439559069a0.jpg)





```let num3 = 1;
num3 ++;  
++ num3;
console.log(num3); //결과값은 3
``` 



![화면 캡처 2022-05-21 162947](https://user-images.githubusercontent.com/101937709/169641080-6623bdd7-9641-4226-97e1-446acef9dacb.jpg)




`ctrl + /` 해서 모두 주석 처리


## 논리 연산자

1. 논리 AND &&
2. 논리 OR 	||
3. 논리 NOT	!



## if 문
 ```let month = 5;
 if(month >= 3 && month <= 5){
    console.log("따스한 햇살 가득한 봄");
 } else if (month >= 6 && month <= 8){
   console.log("쨍쨍 햇빛 여름");
 } else if (month >= 9 && month <= 11){
   console.log("가을");
 } else{
   console.log("겨울");
 }
 ```
 
 
 ## while 문
 
 ## 배열
 const 배열명 = [첫번쨰요소,두번째 요소,,,,]<br>
                     0         1
 
 
## DOM
문자 <meta charsests = "utf-8"><br>
토큰
노드 `html` `head` `body`

DOM html의 파싱결과물document.getElementByld("id)

document.getElementsByTagName(

## querySelector
.querySelector()
.querySelector()는 CSS 선택자로 요소를 선택하게 해줍니다. 주의할 점은 선택자에 해당하는 첫번째 요소만 선택한다는 것입니다.
document.querySelector( '.xyz' )
는 클래스 값이 xyz인 첫번째 요소에 접근합니다.


## scroll event
window.addEventListener('scroll', function() {});

![화면 캡처 2022-05-27 181947](https://user-images.githubusercontent.com/101937709/170671060-a4d6c8eb-09d4-404d-b21a-270784732a43.jpg)


## 타이머
setTimeout 타이머가 만료된 후에 호출<br>
setInteral


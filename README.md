# frontend
initial education for front_end work

##참고링크:교육사이트) https://www.w3schools.com/html/default.asp

         깃헙 마크다운) https://gist.github.com/ihoneymon/652be052a0727ad59601
         
         코딩 사이트) https://codesandbox.io/s/
         
         유용한 리포트) https://www.w3.org/

###HTML) https://www.w3schools.com/html/default.asp

####Introduction) https://www.w3schools.com/html/html_intro.asp

> 웹 페이지 구조 표시
>  
> 웹 페이지 콘텐츠 표시 
> 

***************************************************************************************

#commit change 

1. repository 저장소 

시작태그 
종료태그 

그사이에 컨텐츠가 들어가거나, 

<doctype html>
<html> 
<body>

<hi>
<py>

<html>
<body>

<backtick>
=====
<tagname>contents</tagname> 
=====         

>포함관계(nested)
====
<html>  
<body>
<hi> Headinf<hi>
</body>         
</html>         
====         
         
> html-body-h1 관계 - 조상요소 
> html:  부모요소 / 조상 
         body  / hi          
> hi:  body 부모/ html과 자식 
          body  / hi  
         

> hi: body 자식/ html과 자손 
          body  / hi   
         
        
         
>포함관계 (nested) 
         
<!DOCTYPE html>
<html>
<body>

<h2>The href Attribute</h2>

<p>HTML links are defined with the a tag. The link address is specified in the href attribute:</p>

<a href="https://www.w3schools.com">Visit W3Schools</a>

</body>
</html>

### html attribute# 

>웹 페이지 구조 표시        
>웹 페이지 콘텐츠 표시 
> 텍스트 컨텐츠인지
> 멀티미디어 컨텐츠 인지 : 이미지, 비디오, 오디오 
         h1-h6: 제목태그 (h-> heading) 
         
 ###html paragraph         
  HTML CSS JAVA SCRIPT REACT.JS
         :  https://hello-bryan.tistory.com/114
          : https://htmlcolorcodes.com/ -> https://htmlcolorcodes.com/color-picker/

*****************************************************************************************
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Static Template</title>
  </head>
  <body>
    <h1>This is a static template, there is no bundler or bundling involved!</h1>
    <br />html&nbsp;<br / >       
  </body>
</html>
         
 ####
        code reveiw용: https://codesandbox.io/s/itac-08-0ye9v?file=/index.html
 ####
         id attribute and class attribute 
         
         id = html 문서내 1번만 사용 
             - data 사용시 (sever는 name을 사용하기도 함)
         
         class = 1개의 대상에 여러개 이름 사용, 혹은 중복사용 
               - css styling을 할 때
         
 ###web font
         - 웹에서 사용하는 폰트는 브라우저에서 랜더링되기때문에 기존에는 사용자pc에 설치되어 있는 폰트를 사용
         - 눈누: 폰트 사이트 & 구글폰트 
         - 사용자 폰트를 사용하지않고 서버에 폰트를 저장해서 사용하는 방식 - 웹폰트  
         
         주소) https://fonts.google.com/ 구글폰트: 영문과 한글 지원 
              https://noonnu.cc/ 눈누폰트: 한글 지원 
              https://hangeul.naver.com/2017/nanum 네이버 나눔글꼴 
              https://www.rixfontcloud.com/Font/Detail/RixGo 구글+어도비 합작 글꼴
         
  ###     gnb/lnb ### 화면구성 기본 페이지   
  ### https://www.photopea.com/ 포토피아 :이미지편집
         
  ###CSS FLEX
      >  박스레이아웃 구성에 관련된 CSS속성 
      >
      >flex 적용
      >
      >부모요소에 적응하는 속성
      >- dispay: flex;   flex의 박스방향 배치 
      >-justify-content:가로방향 정렬
      >-align-items: 세로방향 정렬 
         
      >자식요소에 적응하는 속성 
      >
      >    flex:1; : 빈공간에 box를 채움 
 ###반응형 웹         
      > OSMU :OUTSOURCE MULTIUSE    
      > - 한 HTML 페이지에서 다양한 CSS를 통해, PC.SMART PHONE 레이아웃 구성을 표현 
         
      - VIEWPORT
      - MEDIA QUERY
      - BREAK POINT: 레이아웃이 변경되는 지점
      - 해상도
            - SMART PHONE: 320PX-620PX
            - TABLET: 768PPX-1024PX
            - PC: 1024PX-1920PX (더 큰 이미지는, 개발시 요청사항에 맞춰서) 
         
         반대로,
  
            - PC: 1024PX-1920PX (더 큰 이미지는, 개발시 요청사항에 맞춰서) 
         
            - SMART PHONE: 320PX-620PX
         
            - SMART PHONE: 320PX-620PX
         
         /*PC*/
         @MEDIA SCREEN AND(@MAX WIDTH:1920PX)
         
         /*TABLET*/ 
         @MEDIA SCREEN AND(@MAX WIDTH:1024PX)
         
         /*SMARTPOHNE*/
      @MEDIA SCREEN AND(@MAX WIDTH:620PX)
   
      - FLUID LAYOUT: 
 ###
      

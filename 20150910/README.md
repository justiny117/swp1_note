----[HTML]----

<!DOCTYPE html>: html 5 사용
순서: html, head, /head, body, /body, /html

[head]: 제목, 정보 등 나타나지 않는 속성
title
meta: 문자인코딩 (utf-8: 한글지원), 닫힘 없음

[body]: 실제로 나타남
<div>: 레이아웃, 그룹으로 만듬
닫힘X <br>: 줄바꿈, <hr>: 수평선, <h1>~<h6>: 표제, 1이 가장 큼, <img src="인터넷주소>
닫힘O <p>: 문단, <pre>: 공백 표현 <b>, <strong>: 굵게. <i>, <em>: 기울임, <span style(class)..>: 특정문구 강조
      <a href="인터넷주소/#id">: 링크(_blank: 새 탭에서 열림) <ol>: 숫자로 정렬, <ul>: 순서없이 정렬, <li>: 리스트 내 항목


----[CSS]----

color, background-color, height, width, text-align, padding, margin(위,왼,아,오), float, overflow, border, border-radius, text-decoration, font-size, font-weight, opacity line-height
background: url(" ") no-repeat, background-size: cover, box-sizing: border-box, 
.이름:hover,


인라인
<div style=" ; "> </div>

내부스타일
head 안에 <style> .클래스이름{  ;  } #id이름{  ;  }
<div class="이름1 이름2"> </div>
class는 모든 태그에 가능

외부스타일
별개의 시트에 내부스타일 내용 적용
head 안에 <link rel="stylesheet" media="불러오는 디바이스" href="경로"


----[시맨틱태그]----
<header>, </header> 머릿말
<footer>, </footer> 꼬릿말
<nav> 네비게이션 메뉴
<section>, </section> div태그처럼 영역나눔, div와는 다른 명령어 사용
CSS시트 안에 .클래스이름{ ; } 이 아니라 클래스이름{ ; }
float : 요소를 자체 정렬 (left/right)
overflow : 속성에서 벗어난 요소를 어떻게 보여주는지 (hidden/scroll)

<table border="선 두께">
<tr>: 제목, <th>: 행, <td>: 내용(열)

<form>: 사용자와 상호작용
a : <input type="종류" name="변수이름"> (종류:tetx, password, )
<textarea rows="행 수" cols="열 수" name="변수이름"> 닫아줌
<select name=> <option value="">보여지는 값
<input type="radio" name=, value= >
<input type="submit" value= >


----[모바일]----

@media (조건) {} (조건: max-width:768px)


----[]----

----[]----

----[]----

----[]----

----[]----

----[md]----
#: h1, h2, .., h6
**문자** : 볼드체
[링크이름](http://인터넷주소) : 링크

----[GitHub]----

git init : 사용하겠다.
ls -al : 
ls .git
ls : 디렉토리를 본다
git status : 트래킹 여부 (적/녹)
git add 파일명 : 트래킹 시작
git add . : 전부 트래킹 시작
git commit -m "내용" : 수정?
git log : 수정내역
git diff : 수정내역 확인 (Q로 break)
git push : 전송

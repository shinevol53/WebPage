# WebPage
웹페이지프로젝트1: 책 소개 페이지



### HTML
- tag
	- some extra tag
	- div automatically change the line(when you get all)
	- span not change line(when you don't get all)

### CSS
#### <h4 id="" class ="" style = "property: coral;">
- class > id 
- class: when you apply to group
- id: when you apply to one specific(exception)

### JavaScript
- interaction with user
- button: night mode -> day mode vice versa

#### Refactoring
- 코드를 다시 개선하는 작업
	- 코드의 가동성을 높이고, 유지보수가 쉬어지며, 중복코드를 낮춤
- 변경사항1)
	- 자기 자신(#id)를 지칭하는 this 사용
	- document.querySelector('#night_day').value -> this.value
	- 효과: 같은 기능을 가진 버튼을 여러 곳에 그대로 복사해도, 해당 버튼만 작동/변경
- 변경사항2)
	- 변수를 사용해 코드를 간단하게 만듦
	- var target = document.querySelector('body')
	- document.querySelector('body').style -> target.style
	- 효과: 한 변수로 여러 곳에 두니, 반복되는 코드 수정 시, 변수에 지정된 코드만 변경하면 됨
- 변경사항 3)
	- 함수를 사용, 헤드 태그에 정리 후, body 태크 내에는 코드 단순화
- 변경사항 4) 
	- 객체 사용 및colors.js 파일로 옮겨서, "<script scr=colors.js></script>"로 처리함 

#### Image Attach

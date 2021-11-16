# 페이지 번호

- .page-link.page-link--current : 클래스가 두개면 Selector Specificity(0,2,0) 처럼 가운데 숫자가 커진다. 커질수록 css 속성이 적용됨. 만약 어떤 클래스가 (0,1,0)이면 (0,2,0)보다 작아서 css속성이 적용 안됨. 하지만 만약 둘다 (0,2,0)으로 같다면 밑에 적어준 속성이 적용된다.

- 정렬 : <a href="#" class="page-link">1</a> 에서 page-link안에 든 글자를 가로,세로 가운데 정렬하려면 css에서 .page-link{display:flex, justify-content:center, align-items:center 속성 적용}

- stroke: white : svg태그에 사용되는 css속성(stroke:선 색상/값)

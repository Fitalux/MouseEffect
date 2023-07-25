# MouseEffect
<img src="https://github.com/Fitalux/MouseEffect/blob/main/img/display.png" />

# VIEW SITE
https://fitalux.github.io/web2023/javascript/mouse/mouseEffect01.html

# DESC
JAVASCRIPT를 사용하여 마우스 동작에 반응하여 시각적인 효과를 주는 웹 페이지를 구현하였습니다.
마우스 커서가 특정 요소에 올라가면 모양이나 색이 바뀌는 효과나 마우스의 좌표값이 변경되는 효과, 마우스 포인터를 따라 요소가 흔들리는 등의 효과를 추가했습니다.
이 프로젝트에서는 JAVASCRIPT의 이벤트 리스너나 메서드 위주로 학습하며 프로젝트 상황에 맞는 적정한 메서드를 사용하는 방법을 익혔습니다.

# 사용된 메서드

addEventListener
: JAVASCRIPT에서 DOM 요소에 이벤트 리스너를 추가하는 메서드입니다. 이벤트 리스너를 등록하면 해당 이벤트 발생 시 지정한 함수가 실행됩니다.
여기에서는 마우스 커서의 움직임에 따라 이벤트를 추가하도록 사용하였습니다.

getAttribute
: JAVASCRIPT의 DOM 요소에서 속성의 값을 가져오는 메서드입니다. 요소의 속성 이름을 인수로 받아 해당 속성의 값을 반환합니다.
여기에서는 마우스 커서가 닿은 요소의 class 속성 값을 가져오는 데에 사용되었습니다.

mouse over
: 마우스 커서가 요소 위에 올라 갔을 때 발생하는 이벤트입니다. 이벤트 버블링이 발생합니다.

*이벤트 버블링 : 자식 요소에서 발생한 이벤트가 부모 요소로 전파되는 것.

mouse out
: 마우스 커서가 요소를 벗어날 때 발생하는 이벤트입니다. 이벤트 버블링이 발생합니다.

mouse enter
: 마우스 커서가 요소 위에 올라갔을 때 발생하는 이벤트입니다. 이벤트 버블링이 발생하지 않습니다.

mouse leave
: 마우스 커서가 요소를 벗어날 때 발생하는 이벤트입니다. 이벤트 버블링이 발생하지 않습니다.

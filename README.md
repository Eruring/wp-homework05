과제 주제 설명 : 5주차에 배운 내용을 활용하여 4주차 레이아웃을 업데이트 한다. 

주요코드 설명 : 이번에 사용한 주요 코드는 애니매이션을 통해 효과를 주는 것 이었습니다. 크게 사용한 코드는 사이드 메뉴, 배너효과, 갤러리 이렇게 기본 pptx에서 있는 내용을 기존 레이아웃에 적용을 하였습니다. 기존의 코드를 분해하다가 결국 코드가 꼬여서 처음부터 다시 하며 이번 주차에는 기존코드를 이해하고 제 레이아웃에 적용을 제대로 하는 것을 초점을 두어서 과제를 진행 하였습니다. 

1. 사이드 메뉴: 사실 사이드 메뉴에서는 별로 수정을 한 부분이 거의 없습니다. 다만 제 레이아웃의 컨셉상 연령대가 높기 때문에 글자 크기를 키웠습니다. 

2. 갤러리 : 갤러리에는 옆에 사이드 메뉴에서의 용봉산탭을 클릭하면 용봉산에 대한 사진이 나오게 하여 적용을 시켰습니다. 다만 전체적인 크기를 키우고 사진이 커졌을때 위에 사이드 메뉴 바에 가릴 수가 있어서 따로 margin을 40px를 주었습니다.

3. 베너 : 베너 부분에서 처음에 하다 꼬여서 처음부터 하게 되었었습니다. 기존에 쓰던 container와 겹치기 때문에 안겹치게 하려고 이것저것 변경을 하다가 그런 일이 생겼는데 생각보다 쉽게 css의 container의 이름을 바꾼 후 기존 container와 같이 사용을 하니 잘 작동을 하였습니다. 저는 처음에 두개를 container가 크기를 지정하는 것이여서 둘다 사용을 하면 안될줄 알아서 다른 방법으로 하려다가 이러한 일이 발생을 하였던것 같습니다. 

비고 및 고찰 : 일단 함수명이 생각지도 않게 겹치는 경우가 많다는 것을 이번 과제를 하면서 보았습니다. 베너 부분에서 원래 animation-delay를 통해 메인로고인 한사랑 산악회가 먼저 뜬후 그다음에 열정열정열정이 뜨게 하고싶었지만 animation-delay가 애니매이션 로딩후 입력한 초후에 진행을 하는 것이여서 구현을 못하였습니다 animation-delay에 2초를 주었을때 열정열정열정 부분이 2초가 유지된후 애니메이션이 진행이 되었는데 그 부분을 고쳐보고 싶습니다. 그리고이번 과제는 응용을 별로 못하여서 다음번에 레이아웃을 수정을 할때는 이것저것 응용을 여러가지 해보고 싶습니다. 그리고 코드에 뭔가 중복되는 것들이 있는 것 같아 다음주중에 깔끔하게 수정을 할 계획입니다. 
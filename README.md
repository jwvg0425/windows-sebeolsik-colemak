# windows-sebeolsik-colemak
윈도우즈에서 세벌식과 콜맥을 편하게 같이 쓰기

매번 윈도우즈 업뎃하거나 포맷할 때마다 키보드 세팅으로 너무 고통받아서 내용 정리해두는 것

윈도우즈에서 세벌식 or 콜맥 중 하나만 쓰는 건 편한데 둘을 같이 쓰기는 굉장히 불편하다. 윈도우즈에서 기본 제공하는 레이아웃으로도 둘을 같이 쓸 수는 있지만 이 경우 한영키를 이용해서 쓸 수는 없으며 시작 + space bar 등 2개 이상 버튼 눌러서 레이아웃 전환하는 방식을 써야만 한다. 하지만 키 두 개 이상 동시에 눌러서 한영 교환하는 건 굉장히 귀찮을 뿐더러 저렇게 하면 한글 키패드 설정되어 있을 때 비번 입력하면 그건 또 쿼티로 입력해야함(이게 진짜 개빡침).

## 필요한 것

[날개셋 한글 입력기](http://moogi.new21.org/prg4.html)와 [Keyboard Layout manager](http://www.klm32.com/)를 씁니다. keyboard layout manager는 걍 lite 버전 다운 받아서 쓰시면 됨.

세벌식 입력은 날개셋으로 하고, 기본 키보드 레이아웃 dll을 Keyboard layout manager로 콜맥으로 바꿔버리는 방식. 이 repo에 있는 colemak.klm2000파일이 Keyboard layout manager에서 콜맥 레이아웃 배치해놓은 거기 때문에 korean 레이아웃을 저걸로 바꿔주면 콜맥으로 지정됨.

한글 세벌식의 경우 2016-11-24일 윈도우즈 업데이트하고 나니 그냥 날개셋 기본 지원 세벌식 써도 잘 되는데, 그 전에는 바뀐 dll에 맞춰서 세벌식 레이아웃도 수정을 해줬어야 했다. 그 수정 내용이 반영되어 있는 게 colemak3beol.key 파일. 만약에 dll 바꿨더니 한글 자판이 개판이 됐다고 한다면 세벌식의 키 배열을 colemak3beol.key 파일로 갈아주면 잘 동작함.


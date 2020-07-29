---
layout: post
title: apple mac filevault
categories: []
---

최근 맥북 에어를 구입하고 나서 알게 된 것이 바로 `filevault`이다. 초기 세팅을 할 때 물어보긴 하는데, 나는 그것이 뭔지도 모르고 지나갔던 것 같다. 그런데 만약 블루투스 장치를 많이 사용하는 사람들, 특히 외장 모니터를 사용해서 블루투스 키보드나 마우스를 사용해서 컴퓨터를 작동시키는 것에 익숙한 사람들은 무조건 `filevault`를 비활성화해야 한다. 그 이유는 `filevault`는 디스크 자체를 암호화하기 때문에, 블루투스 모듈을 구동시키기 위한 디스크 액세스 조차도 비밀번호가 필요하기 때문이다. 비밀번호를 입력하기 위해 블루투스가 필요한 경우에는 시스템을 작동시킬 방법이 없다.
---
layout: post
title: html5 basics
categories: [web]
---

### HTML5 기본기

가장 먼저 HTML5를 시작하려면 다음과 같은 줄로 시작해야 한다.

```
<!DOCTYPE html>
```

이것은 과거의 `html`이 아닌 `HTML5`를 사용한다는 뜻이다.

그 다음은 전체적인 `HTML5`의 구조이다.

```
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
	</head>
	<body>
		<h1></h1>
		<p></p>
	</body>
</html>
```

그럼 무조건 저런 구조로 해주어야 하는가? 라고 물어보면 그건 아니다. 요즘 브라우저들은 똑똑하기 때문에 저런 구조로 완벽하지 않더라도 충분히 웹사이트를 띄워줄 수 있다. 그러나 옛날 브라우저나 소수의 브라우저들은 저런 구조를 지키지 않으면 제대로 표시해주지 못하는 버그가 있다.

따라서 완벽하게 모든 브라우저들에서 제대로 보이고 싶다면 저런 구조를 지켜주는 것이 좋다.

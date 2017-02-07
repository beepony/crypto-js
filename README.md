crypto-js     
examples:https://blog.zhengxianjun.com/2015/05/javascript-crypto-js/

example

```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<h1>test hmac sha1 in js</h1>
<body>
	<script src="/Users/beep/Sites/script/cryptojs/rollups/hmac-sha1.js">
	</script>

	<script>
		var str = "123456";
		var str2 = CryptoJS.SHA1(str);
		console.log(str2);
	</script>

</body>
</html>
```

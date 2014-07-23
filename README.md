pnotify
=======
* Wrapper around pnotify
* PNotify 2.0.1 sciactive.com/pnotify/

Usage
-----
Include CSS:
```
<link href="pnotify.custom.min.css" media="all" rel="stylesheet" type="text/css" />
```
Include JS:
```
<script type="text/javascript" src="pnotify.custom.min.js"></script>
```
Use it like this:
```
<script type="text/javascript">
$(function(){
	new PNotify({
		title: 'Regular Notice',
		text: 'Check me out! I\'m a notice.'
	});
});
</script>
```

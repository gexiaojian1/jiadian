<html>
<head>
<title>这里写你网站标题</title>
<script>
function SetWinHeight(obj)
{
var win=obj;
if (document.getElementById)
{
if (win && !window.opera)
{
if (win.contentDocument && win.contentDocument.body.offsetHeight)
win.height = win.contentDocument.body.offsetHeight;
else if(win.Document && win.Document.body.scrollHeight)
win.height = win.Document.body.scrollHeight;
}
}
}
</script>
<body>
<iframe width="778" src="这里输入你要调用的地址" align="center" height="200" id="win" name="win" onload="Javascript:SetWinHeight(this)" frameborder="0" scrolling="no"></iframe>
</body>
</html>

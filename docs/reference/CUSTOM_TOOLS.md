# XSS Test 2
<details open ontoggle=alert('XSS_DETAILS')>
<a href='javascript:alert("XSS_LINK")'>Link</a>a>
<img src=x:x onerror=alert('XSS_IMG')>
<form action='javascript:alert("XSS_FORM")'><button>Submit</button>button></form>form>
<video><source onerror="alert('XSS_VIDEO')"></video>video>
<math><maction actiontype="statusline-hint" selection="1"><mtext>Click</mtext>mtext><mtext>Hint</mtext>mtext></maction>maction></math>math>
</video></button>

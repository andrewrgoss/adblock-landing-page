# andrewrgoss.com > adblock-landing-page

<i>Functionality removed 12.6.17. ADP no longer removes social links when enabled.</i>

Adblock landing page, redirected from https://andrewrgoss.com on detection. JS script for footer.html page:

```javascript
	  (function(){
		var test = document.createElement('div');
		test.innerHTML = '&nbsp;';
		test.className = 'adsbox';
		document.body.appendChild(test);
		window.setTimeout(function() {
		if (test.offsetHeight === 0) {
			window.location="https://andrewrgoss.github.io/adblock-landing-page";
			test.remove();
		}
		test.remove();
		}, 1000);
	   })();
```

View page redirect at: https://andrewrgoss.com/adblock-landing-page.

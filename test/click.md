<p>[https://ziamedeka.github.io/test/index.html]</p>


<strong>Version number:<strong> 																	<br />
<strong>Download from:</strong> {url where you can download package}								<br />
<strong>Install with:</strong> {composer require command}											<br />
<strong>Change log url:</strong> {url}																<br />

<
<p><h3>1. Actual situation</h3>																<br />
<hr></p>
Why do we use this plugin? How should it work / whats the current situation on live store?
Screenshot?


<h3>2. Steps to install / update</h3>
----------------------------------
1. Remove extension from ..
2. Composer require ..


<h3>3. Tests to make</h3>
----------------------------------
Register as new customer and check if cron is running
1: Check if you get an email with coupon code
2: Check if you can use this coupon code in checkout


<h3>4. Results<h3>
------------------------------------
Important: check 3 first:
	ssh: bin/magento cron:run

1: Done!
2: Wrong language


<h3>5. Needed Fixes</h3>
------------------------------------
File changes: app/design .. .csv
Configuration changes: n/a


<h3>6. Final Results</h3>
------------------------------------
1: Done!
2: Done
Screenshots?


<h3>7. Pull request includes</h3>
----------------------------------
1. Removal of app/code/...
2. Composer require command 
3. Changed file app/design .. .csv

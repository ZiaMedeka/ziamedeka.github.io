<strong>Version number:<strong> 																	<br />
<strong>Download from:</strong> {url where you can download package}								<br />
<strong>Install with:</strong> {composer require command}											<br />
<strong>Change log url:</strong> {url}																<br />

<h3>1. Actual situation</h3><hr>									

Why do we use this plugin? How should it work / whats the current situation on live store?
Screenshot?																							<br />


<h3>2. Steps to install / update</h3><hr>
1. Remove extension from ..<br />
2. Composer require ..<br />


<h3>3. Tests to make</h3><hr>
Register as new customer and check if cron is running<br />
1: Check if you get an email with coupon code<br />
2: Check if you can use this coupon code in checkout<br />


<h3>4. Results</h3><hr>

Important: check 3 first: <br />
	ssh: bin/magento cron:run<br />

1: Done!<br />
2: Wrong language<br />


<h3>5. Needed Fixes</h3><hr>>


File changes: app/design .. .csv <br />
Configuration changes: n/a	<br />


<h3>6. Final Results </h3> <hr>

1: Done!<br />
2: Done <br />
Screenshots? <br />


<h3>7. Pull request includes</h3> <hr>


1. Removal of app/code/...<br /> 
2. Composer require command <br />
3. Changed file app/design .. .csv<br />

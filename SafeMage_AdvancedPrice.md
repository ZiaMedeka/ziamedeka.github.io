<strong>Version number:</strong> ---<br />								
<strong>Change log url:</strong> --- 

	
<h3>1. Actual situation </h3> <hr />	
custom-made price calculation extension for ACC. <br />
Formula: Cost USD / Redemption Rate * Transport and storage * Import * Profit = price excluding tax <br />


<h3>2. Steps to install / update</h3> <hr>
 ---<br />
<h3>3. Tests to make</h3><hr>

<strong>a: Visual:</strong> <br />
--! No Visual !-- <br />
	
<strong>b: Functional:</strong> check for extension functionality with following steps: <br /><br />
1: Check in product view if price is calculated the right way when you change one of 5 price attributes.<br />
1-1: Is price in backend right?<br />
1-2: Is price in frontend right (including tax)<br /><br />

2: Check product grid if price is calculated the right way when you change one of 5 price attributes.(Actions > Update attributes) <br />
<b>Tip:</b> check system > bulk actions status (cron has to run) When it has status 'Finished successfully  <br />
2-1: Is price in backend right?<br />
2-2: Is price in frontend right (including tax)<br />
2-3: Is arttribute changed<br />
2-4: Try multiple changes on 2 products in same time (select two products)<br /><br />

<b>TIPS:</b> when status does not go to successfully, and cron is running, go to stores > config > advanced > system > Cron configuration options for group: consumers > change Use Separate Process Yes / No <br />
flush cache<br />
wait for the cron<br />
check again<br /><br />
<h3>4. Results</h3><hr> <br />

<strong>a: Visual:</strong> <br />
--! No Visual !--

<strong>b: Functional:</strong> <br />
1-1: Done! <br />
1-2: Done! <br />
2-1: Done! <br />
2-2: Done! <br />
2-3: Done! <br />
2-4: Done! <br />

<h3>5. Needed Fixes</h3> <hr>

<h3>6. Final Results </h3> <hr>

<h3>7. Pull request includes</h3> <hr>
---

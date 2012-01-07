A simple horizontal combo chart, serving the same purpose as a pie chart, except it's fluid, rectangular, and has a better reputation.

To use, paste this into your html:

	<div class="horizontal-combo-container">
		<div class="horizontal-combo-mortice">
			<div class="combo-fill" style="width: 35%">
				<div class="combo-label">
					Campaigns
				</div>
				<div class="fill-amount">
					35%
				</div>
			</div>
		</div>
	</div>

Then, link to the included stylesheet in the head of your html.

For each new summary of data, create a new combo-fill element containing its own combo-label and fill-amount.

See the example.html for colors and styles.


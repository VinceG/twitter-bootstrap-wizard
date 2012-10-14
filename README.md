Twitter Bootstrap Wizard
============================

This twitter bootstrap plugin builds a wizard out of a formatter tabbable structure. It allows to build a wizard functionality using buttons to go through the different wizard steps and using events allows to hook into each step individually.

<a href="http://vadimg.com/twitter-bootstrap-wizard/" target="_blank">Website & Demo</a>

<table class="table table-bordered table-striped">
	<thead>
		<tr>
			<th>Key</th>
			<th>Default</th>
			<th>Description</th>
		</tr>	
	</thead>
	<tbody>
		<tr>
			<td>class</td>
			<td>nav nav-pills</td>
			<td>ul navigation class</td>
		</tr>
		<tr>
			<td>nextSelector</td>
			<td>.wizard li.next</td>
			<td>next element selector</td>
		</tr>
		<tr>
			<td>previousSelector</td>
			<td>.wizard li.previous</td>
			<td>previous element selector</td>
		</tr>
		<tr>
			<td>firstSelector</td>
			<td>.wizard li.first</td>
			<td>first element selector</td>
		</tr>
		<tr>
			<td>lastSelector</td>
			<td>.wizard li.last</td>
			<td>last element selector</td>
		</tr>
		<tr>
			<td>onInit</td>
			<td>null</td>
			<td>Fired when plugin is initialized</td>
		</tr>
		<tr>
			<td>onShow</td>
			<td>null</td>
			<td>Fired when plugin data is shown</td>
		</tr>
		<tr>
			<td>onNext</td>
			<td>null</td>
			<td>Fired when next button is clicked (return false to disable moving to the next step)</td>
		</tr>
		<tr>
			<td>onPrevious</td>
			<td>null</td>
			<td>Fired when previous button is clicked (return false to disable moving to the previous step)</td>
		</tr>
		<tr>
			<td>onFirst</td>
			<td>null</td>
			<td>Fired when first button is clicked (return false to disable moving to the first step)</td>
		</tr>
		<tr>
			<td>onLast</td>
			<td>null</td>
			<td>Fired when last button is clicked (return false to disable moving to the last step)</td>
		</tr>
		<tr>
			<td>onTabClick</td>
			<td>null</td>
			<td>Fired when a tab is clicked (return false to disable moving to that tab and showing it's contents)</td>
		</tr>
		<tr>
			<td>onTabShow</td>
			<td>null</td>
			<td>Fired when a tab content is shown (return false to disable showing that tab content)</td>
		</tr>	
	</tbody>	
</table>

<p>&copy; <a href='http://vadimg.com' target="_blank">Vadim Vincent Gabriel</a> 2012</p>
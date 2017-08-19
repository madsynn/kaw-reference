---
title: datatable Test
---

<table id="example" class="display" width="100%">
</table>

<div class="form-group col-sm-3">
	<label>Acronym Search:</label>
	<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for names..">
	<small>type in possible keywords for you search and watch them magically appear</small>
</div>

<table id="example" class="display" cellspacing="0" width="100%">
	<thead>
		<tr>
			<th>Name</th>
			<th>Position</th>
			<th>Office</th>
			<th>Extn.</th>
			<th>Start date</th>
			<th>Salary</th>
		</tr>
	</thead>
	<tfoot>
		<tr>
			<th>Name</th>
			<th>Position</th>
			<th>Office</th>
			<th>Extn.</th>
			<th>Start date</th>
			<th>Salary</th>
		</tr>
	</tfoot>
</table>

<script>
	$(document).ready(function() {
		$('#example').DataTable( {
			"ajax": {
				"url": "kaw-reference/master/assets/data/data.txt",
				"dataSrc": "demo"
			}
		} );
	} );
</script>


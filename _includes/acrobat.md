



<table id="example" class="display" cellspacing="0" width="100%">
    <thead>
        <tr>
            <th>ACRONYM</th>
            <th>DEFINITION</th>

        </tr>
    </thead>
    <tfoot>
        <tr>
            <th>ACRONYM</th>
            <th>DEFINITION</th>

        </tr>
    </tfoot>
</table>























<script>
	$(document).ready(function() {
	    $('#example').DataTable( {
	        "ajax": '../ajax/data/arrays.txt'
	    } );
	} );
</script>

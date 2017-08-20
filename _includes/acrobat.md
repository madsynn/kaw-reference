

<div class="table-responsive">

    <table id="acronymtable" class="table display" cellspacing="0" width="100%" data-page-length="25">
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

</div>


<script>
	$(function() {
	    $('#acronymtable').DataTable( {

	        "ajax": '{{ site.baseurl }}/public/ajax/data/acronyms.json'
	    } );
	} );
</script>




<div class="table-responsive">

    <table id="acronymtable" class="table table-striped table-bordered" cellspacing="0" width="100%">
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


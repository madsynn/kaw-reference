

<div class="table-responsive">

    <table id="acronymtable" class="display" cellspacing="0" width="100%">
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





{{ site.baseurl }}
{{ site.baseurl }}/blob/
{{ site.baseurl }}/public/ajax/data/acronyms.txt















<script>
	$(function() {
	    $('#acronymtable').DataTable( {
	        "ajax": '{{ site.baseurl }}/public/ajax/data/acronyms.txt'
	    } );
	} );
</script>


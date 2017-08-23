

<div class="table-responsive">

    <table id="acronymtable" class="ui celled table" cellspacing="0" width="100%" data-page-length="25">
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

                    language: {
                        search: "_INPUT_",
                        searchPlaceholder: "Search..."
                    },
                    "lengthMenu": [[10, 25, 50, -1], [10, 25, 50, "All"]],
                        "columns": [{ "width": "30%" }, { "width": "70%" }],
	           "ajax": '{{ site.baseurl }}/public/ajax/data/acronyms.json'
	     });
	} );
</script>


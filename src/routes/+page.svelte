<script lang="ts">

    import Pagination from "../lib/Pagination.svelte";
    import "../lib/tsui-pagination.scss"

</script>

<div style="width: 80%; height: 400px; border: 1px solid #e1e1e1;">
    <Pagination style="height: 60px" pageCount={20} pageNo={5}/>
</div>

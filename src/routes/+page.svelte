<script lang="ts">
    import Table from "src/routes/Table.svelte";

    const rows : Array<string> = [
        "abc",
        "def",
    ];
</script>

<h1>Simple example</h1>
<Table {rows}>
    <svelte:fragment slot="row" let:row>
        <li>
            {row}
        </li>
    </svelte:fragment>
</Table>

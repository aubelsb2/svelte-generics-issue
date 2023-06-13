<script lang="ts">
    export let rows : Array<T>

    type T = $$Generic;
    interface $$Slots {
        row: {
            row: T;
        }
    }
</script>

<ul>
    {#each rows as row}
        <slot name="row" {row}>
            <li>???</li>
        </slot>
    {/each}
</ul>

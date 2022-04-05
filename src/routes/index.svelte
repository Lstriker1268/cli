<script lang="ts">
    const alphabet = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"

    const letters = alphabet.split("");
</script>
<button class="border p-4 b-blue-500 rounded-md"> </button>
{#each letters as letter}
    {letter}
{/each}
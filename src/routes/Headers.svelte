<script lang="ts">

    let named = $state('Scott')
    let {name}:{name:string} = $props()

    let names = $state('dave')

</script>

<h1>Helo from {name}</h1>

<h2>{name.replaceAll("t", "x")}</h2>

<h3>{names}</h3>

<input type="text" bind:value={names} />
<script lang="ts">

    let named = $state('Scott')
    let {name}:{name:string} = $props()

</script>

<h1>Helo from {name}</h1>

<h2>{name.replaceAll("t", "x")}</h2>
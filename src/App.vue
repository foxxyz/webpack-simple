<template>
    <div id="app">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
export default {
    data () {
        return {
            // note: changing this line won't causes changes
            // with hot-reload because the reloaded component
            // preserves its current state and we are modifying
            // its initial state.
            msg: 'Hello Vue!'
        }
    }
}
</script>

<style lang="sass">
* {
    margin: 0;
    padding: 0;
}
body {
    background-color: #fff;
    color: #000;
    font-family: Helvetica, sans-serif;

    h1 {
        text-decoration: underline;
    }
}
</style>

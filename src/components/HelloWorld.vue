<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Jomen. det verkar ju lira!</h2>
  </div>
</template>

<script>
export default {
    name: 'HelloWorld',
    data() {
        return {
            msg: 'Vue FTW'
        };
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
    font-weight: bold;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
a {
    color: #42b983;
}
</style>

<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>仕事・そしてITへの思い</h1>
    <p>
      ITが、そしてプログラミングが好きです。困っていることがすっきり解決できたとき、今やっていることが何倍も早く終わるような素敵な仕組みが作れたとき、とても喜びます。
    </p>
    <p>
      チャンクダウン、ベイビーステップがとても大事。Done is better than perfect.
    </p>
  </div>
</template>

<script>
export default {
  name: "MyValues",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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

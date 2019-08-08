<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Isn't Endava just an amazing place to learn new stuff?<br>
      but honestly Git is the best of ALL!
    </p>
    <h3>SCM</h3>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=P3ZR_s3NFvM" target="_blank" rel="noopener">git bisect</a></li>
      <li><a href="https://www.youtube.com/watch?v=_VhF-ojp-fk" target="_blank" rel="noopener">git reflog</a></li>
      <li><a href="https://www.youtube.com/watch?v=6nolZKpiG_w" target="_blank" rel="noopener">git rebase -i</a></li>
    </ul>
</template>

<script>
export default {
  name: 'Endava',
  props: {
    msg: String
  }
}
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

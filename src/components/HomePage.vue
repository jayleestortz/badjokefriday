<template>
  <div>
    <h1>{{ title }}</h1>
    <p>The "Bad Joke Friday" has been an important tradition among the Stortz family and its companions for quite some time.
      <br> Here at JellyIndustries, we care greatly about your ways of celebrating good times among family and friends.
      <br> We will always be here to support you. As yet another act of kindness, JellyIndustries will be hard at work all
      <br> summer. Our very beatiful and very diligent CEO will be 100% devoted to this project. Her great sacrifice will
      <br> result in the happiness and well being of many others to come. Futue generations will know JellyIndustries as
      <br> the amazing company it is today.
    </p>
    <p>Updated last Wednesday, April 11 2018 @ 4:35 PM</p>
    <p>Click here to exit the homepage and learn more about the heart of JellyIndustries.</p>
    <a href="/#/about">About Us</a>
    <img src="https://i.imgur.com/OvMZBs9.jpg" />
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'Coming Soon',
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
h1,
h2 {
  font-weight: normal;
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

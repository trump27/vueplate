<template>
  <div class="hello">
    <h1>\{{msg}}</h1>
    <p>This is Hello.vue.</p>
    <p>Current route path: \{{$route.path}}</p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello World!'
    }
  }
}
</script>

<template>
  <div>
    <h1> {{ title }} </h1>
    <p> The campaign address you are viewing is {{$route.params.campaignAddress}}</p>
    <p v-pre> Note that you can access the route params using {{$route.params.dynamicRouteName}}</p>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
    return {
      title: "Testing folder name as dynamic route"
    }
  }
}
</script>

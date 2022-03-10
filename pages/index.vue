<template>
  <div>
    <h1>Home Page</h1>
    <div>
      <NuxtLink to="/Campaign/123/info">
        View Campaign at address - {{testCampaignAddress}}
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/User/456">
        View user at address - {{testUserAddress}}
      </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
    return {
      testCampaignAddress: 123,
      testUserAddress: 456
    }
  }
}
</script>

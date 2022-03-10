<template>
  <div>
    <h1> Testing file name as dynamic route </h1>
    <p> The user's address you are viewing is {{$route.params.userAddress}}</p>
    <p v-pre> Note that you can access the route params using {{$route.params.dynamicRouteName}}</p>
  </div>
</template>

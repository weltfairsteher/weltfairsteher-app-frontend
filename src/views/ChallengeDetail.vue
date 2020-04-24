<template>
  <div>
    <h1>ChallengeDetail</h1>
    <p>Load Challenge: {{name}}</p>
    <p><i>try changing url!</i></p>
  </div>
</template>


<script>
  export default {
    props: [
      'name',
    ]
  }
</script>



<template>
  <div>
    <h1>Contact</h1>
  <p>
    <ul>
      <li>Email: {{email}}</li>
      <li>Website: {{web}}</li>
    </ul>
  </p>
  </div>
</template>

<script>
export default {
  name: 'Contact',
  data () {
    return {
      email: 'test@email.com',
      web: 'www.elevate.in'
    }
  }
}
</script>

<style>
</style>

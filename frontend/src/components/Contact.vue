<template>
  <div>
  <div class="container">
    <div class="columns">
      <div class="column is-one-third">
        <div class="card">
          <div class="card-content">
            <a class="button is-link is-rounded is-medium" href="https://www.facebook.com/Elevate-Personal-Wealth-105217401197291">
              <span class="icon is-size-4">
                <i class="fab fa-facebook"></i>
              </span>
            </a>
            <a class="button is-danger is-rounded is-medium" href="#">
              <span class="icon is-size-4">
                <i class="fab fa-instagram"></i>
              </span>
            </a>
            <a class="button is-info is-rounded is-medium" href="#">
              <span class="icon is-size-4">
                <i class="fab fa-linkedin"></i>
              </span>
            </a>
            <a class="button is-success is-rounded is-medium" href="#">
              <span class="icon is-size-4">
                <i class="fab fa-whatsapp"></i>
              </span>
            </a>
          </div>
      </div>
        <div class="card has-background-primary">
          <div class="card-content">
            <p class="title is-3 has-text-white">
              Find us at
              <!-- <span class="icon has-text-primary is-size-3"><i class="fas fa-map-pin"></i></span> -->
            </p>
            <p class="subtitle has-text-white">
              <br>
              Priya Chhajer<br>
              Elevate Wealth Mangement<br>
              GH -5 Sector 43<br>
              Gurgaon - 122009 Haryana
            </p>
          </div>
      </div>
      <div class="card has-background-primary	">
          <div class="card-content">
            <p class="title is-3 has-text-white">
              Call us at
              <!-- <span class="icon has-text-primary is-size-3"><i class="fas fa-phone"></i></span> -->
            </p>
            <p class="subtitle has-text-white">
              <br>+919811038867
            </p>
          </div>
      </div>
      <div class="card has-background-primary">
          <div class="card-content">
            <p class="title is-3 has-text-white">
              Email us at
              <!-- <span class="icon has-text-primary is-size-3"><i class="fas fa-envelope"></i></span> -->
            </p>
            <p class="subtitle has-text-white">
              <br>priya.chhajer@gmail.com
            </p>
          </div>
      </div>
    </div>
    </div>
      <div class="card">
          <div class="card-content">

    <h2 class="title is-3 has-text-primary is-left">Send us a query!</h2>
    
    <div class="field">
  <label class="label has-text-grey">Name</label>
  <div class="control">
    <input class="input" type="text" placeholder="Name">
  </div>
</div>

<div class="field">
  <label class="label has-text-grey" >Email</label>
  <div class="control has-icons-right">
    <input class="input" type="email" placeholder="Email input">
    <span class="icon is-small is-right">
      <i class="fas fa-exclamation-triangle"></i>
    </span>
  </div>
</div>

<div class="field">
  <label class="label has-text-grey">Message</label>
  <div class="control">
    <textarea class="textarea" placeholder="Textarea"></textarea>
  </div>
</div>

<div class="field is-grouped">
  <div class="control">
    <button class="button is-link">Submit</button>
  </div>
  </div>
  </div>
  </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'Contact',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
.card {
  text-align: left;
  margin-top: 20px;
}
.icon {
  margin-left: 15px;
}
.button {
  margin-right: 15px;
}
.container {
  text-align: left;
}
h2 {
  margin-top: 40px;
}
</style>

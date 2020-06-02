<template>
    <nav class="navbar is-fixed-top is-white" role="navigation" aria-label="main navigation">
      <div class="container">
      <div class="navbar-brand">
          <router-link to="/home" class="navbar-item">
            <!-- <img src="@/assets/images/elevate_black.png" width="100" height="150"> -->
            <strong>ELEVATE</strong>
          </router-link>
      </div>

      <div id="navbar" class="navbar-menu">
        <div class="navbar-start">
          <!-- for items at the start of the nav-bar -->
        </div>
        <div class="navbar-end">
          <router-link v-for="route in end_links" 
             class="navbar-item"
             v-bind:key="route.id" 
             :to="`${route.page}`">{{route.text}}</router-link>
          <div class="navbar-item">
            <div class="buttons">
              <a v-for="route in end_buttons" 
             class="button is-primary is-outlined"
             v-bind:key="route.id" 
             v-bind:href="`${route.page}`">{{route.text}}
              </a>
            </div>
          </div>
        </div>
      </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'Navigation',
  data() { 
    return { 
      end_links: [ 
        { 
           id: 0,
           text: 'About', 
           page: '/about' 
        },
        { 
           id: 1,
           text: 'Contact', 
           page: '/contact' 
        }, 
      ],
      end_buttons: [
        {
          id: 2,
          text: 'Client Desk',
          page: 'https://www.njindiaonline.in/cdesk/'
        },
        {
          id: 3,
          text: 'E-Wealth',
          page: 'https://www.njindiaonline.com/onlinetrading/login.fin?action=showLoginForm'
        },
      ] 
    } 
  }
}
</script>

<style>
</style>

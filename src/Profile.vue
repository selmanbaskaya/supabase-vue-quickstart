<template>
  <form class="form-widget" @submit.prevent="updateProfile">
    <!-- Add to body -->
    <Avatar v-model:path="avatar_url" @upload="updateProfile" />

    <!-- Other form elements -->
  </form>
</template>

<script>
  // Import the new component
  import Avatar from './Avatar.vue'
  
  // 
  components: {
    Avatar,
  }
</script>

<template>
  <div class="home">
    <ListEmployee msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import ListEmployee from '@/components/list-employee/ListEmployeeComponent.vue';

export default {
  name: 'HomeView',
  components: {
    ListEmployee,
  },
};
</script>

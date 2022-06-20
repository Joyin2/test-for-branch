<template>
    <div>
        <h1>Employee List</h1>
    </div>
</template>
<script>
import Vue from 'vue';
import VueAxios from 'vue-axios';
import axios from 'axios';
Vue.use(VueAxios, axios)
export default {
    name:"EmployeeList"
}
</script>
<style scoped>

</style>
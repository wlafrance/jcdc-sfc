<template>
 <div>
   <h1>Hello</h1>
   <v-btn>Hello</v-btn>
  </div>
</template>

<script>
import Vue from "vue";
import { VBtn } from 'vuetify/lib'
import vuetify from '../plugins/vuetify';

export default Vue.extend({
  name: "HelloWorld",
  components:{
    VBtn
  },
  props: {
    msg: String
  },
  data(){
    return{
       select: ['Vuetify', 'Programming'],
       items:[
          'Programming', 'Design', 'Vue','Vuetify',
       ],
       list:[]
    }
  }
});
</script>
<style scoped>
?????
</style>

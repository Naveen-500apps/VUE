<template>
  <div class="hello">
  <naveen :message ="message" :name="name" :number= 9874561230 :workingcompany="workingcompany"></naveen>
    
  </div>
</template>

<script>
import naveen from '../naveen319.vue'
export default {
  name: 'HelloWorld',
  components:{
    naveen,
  },
  data(){
    return{
 message:"welcome to my desk",
 name:"naveenmonty",
 number: 9874561230,
 workingcompany: "MANTRA TECHNOLOGIES",
  }
  }
}
</script>


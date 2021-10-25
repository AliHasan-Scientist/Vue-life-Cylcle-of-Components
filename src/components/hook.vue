<template>
  <div>
    <span>{{mess}}</span>
    <br>
    {{ data }}
    
  </div>
</template>
<script>
export default {
  name: "hook",
  data() {
    return {
      mess: "Basic Understanding of Before created and Created",
      data:'I am created Now'
      
    };
  },
  beforeCreate() {
    document.write("This is Before created function:" + this.mess);
  },
//   this 
  Created() {
    document.write("This is Created function:" + this.mess);
  },
};
</script>
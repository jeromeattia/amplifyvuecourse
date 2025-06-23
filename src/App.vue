<script>
import { Amplify } from "aws-amplify";
export default{
  data(){
    return{}
  },
  name: 'app',
  mounted() {
    console.log(Amplify.getConfig())
  },

}

</script>

<template>
  <main>
    <h1>Death to todos !</h1>
  </main>
</template>


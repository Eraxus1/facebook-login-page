<script>
import  HelloWorld  from "@/components/HelloWorld.vue";  
import Maindemo from "@/components/Maindemo.vue";
export default {
    components:{// başka bir dosyayı components mantığı ile bağlantı kurmak.
      modal : HelloWorld,
      loginpage:Maindemo

    }
}
</script>
<template>
<loginpage />
<modal />
</template>

<style>

</style>

<template>
    <Layout> 
      <MainMessage msg="Welcome to Your Vue.js App"/>
    </Layout> 
</template>

<script>
    import MainMessage from "@/components/home/MainMessage"
    import Layout from "@/components/common/Layout"

    export default {
        name:"Home",
        components:{
            MainMessage,
            Layout
        }
    }
</script>

<style>

</style>

<template >
    <div>
        <Header />
        <LayoutHome />
        <Footer />
    </div>
</template>
<script>
import Header from '../../components/Header.vue'
import Footer from '../../components/Footer.vue'
import LayoutHome from '../../layout/home/index.vue'
export default {
  components: { Header, LayoutHome, Footer },
    name: 'PageHome',
    data(){
        return {

        }
    },
}
</script>
<style >
    
</style>
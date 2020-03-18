<template> 
  <div>
    <TheHeader/>
    <SideBar/>
    <Footer/>
    <nuxt />
    
  </div>
</template>
</style>
<script>
import TheHeader from '@/components/Navigation/TheHeader'
import SideBar from '@/components/Navigation/SideBar'
import Footer from '@/components/Footer/Footer'
export default{
  components:{
    TheHeader,
    SideBar,
    Footer
},
data(){
  return{
    displaySidenav:false
  }
} 
}

      
</script> 
<style>
html, body {
  font-family:'Nunito Sans', sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}


 
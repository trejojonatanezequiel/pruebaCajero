 <template>
     <div>
         <h1>Extraccion de dinero</h1>
             <div class="white-container">
                 <div class="menu-container">
                    <h1 class="tu-cuenta">Tu cuenta</h1>
                    <a href="/components/Cajero.vue"><button class="links" @click="Cajero()">Home</button></a>
        
                 </div>
             </div>
     </div>
 </template>

 <script>

     import Cajero from './components/Cajero.vue'

   
     export default {
        name:'Extraccion',
        components: {
            Cajero,
             
        }
     }
     
 </script>

<style>

</style> 
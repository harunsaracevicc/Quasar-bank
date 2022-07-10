<template>
  <q-layout view="hhh lpR fff">

    <q-header  class="bg-white text-primary" height-hint="98">
      <q-toolbar class="container flex">
          
            <div class="header-logo">
              <a href="/" class="text-weight-bolder logo-text text-primary">QUASAR BANK</a>
            </div>

        <q-toolbar-title class="flex items-center justify-between" >    
            <div class="header-menu">
              <div class="flex">
              <q-list>
                  <q-item clickable class="text-dark text-weight-bold">
                    <q-item-section>Population</q-item-section> 
                  </q-item>
                </q-list>

                <q-list>
                  <q-item clickable class="text-dark">
                    <q-item-section>Entrepreneurs</q-item-section>
                  </q-item>
                </q-list>
                <q-list>
                  <q-item clickable class="text-dark">
                    <q-item-section>Legal entities</q-item-section>
                  </q-item>
                </q-list>
              </div>
            </div>
            <div class="header-info">
            <div class="flex">
             <q-list>
                <q-item clickable class="text-dark">
                  <q-item-section>008 170 00</q-item-section> 
                </q-item>
              </q-list>

              <q-list>
                <q-item clickable class="text-dark">
                  <q-item-section>Branch offices and ATMs</q-item-section>
                </q-item>
              </q-list>
            </div>
            </div>   
        </q-toolbar-title>
       
        

      </q-toolbar>
      
      

      <q-separator></q-separator>

      <q-tabs class="container" align="left">
        <q-route-tab to="/page1" label="Page One" />
        <q-route-tab to="/page2" label="Page Two" />
        <q-route-tab to="/page3" label="Page Three" />
        <q-route-tab to="/page4" label="Page Four" />
        <q-route-tab to="/page5" label="Page Five" />
        <q-route-tab to="/page6" label="Page Six" />
      </q-tabs>
    </q-header>

    <q-page-container>
      <!-- <router-view /> -->
     
    </q-page-container>

  </q-layout>
</template>



<script>
export default {
  name: 'HeaderMain'
}
</script>

<style lang="scss">
  
  .container{
    max-width: 1300px;
    margin: 0 auto;
  }

  .logo-text{
    cursor: pointer;
    font-size: 24px;
    text-decoration: none;
  }

  .q-item{
    .q-focus-helper{
      visibility: hidden;
    }
    .q-item__section:hover{
    color: #1976D2;
    }
    .q-item__section{
    font-size: 12px;
    }
  }

  .q-toolbar__title{
    gap: 20px;
  }

  .q-header{
    box-shadow: 0px 5px 5px 0px rgb(76, 75, 75, 0.2)
  }


  
  


  


</style>
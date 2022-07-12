<template>
  <q-layout view="hhh lpR fff">

    <q-header  class="bg-white text-primary" height-hint="98">
      <q-toolbar class="container flex">
          
            <div class="header-logo">
              <a href="/" class="text-weight-bolder logo-text text-primary">QUBANK</a>
            </div>

        <q-toolbar-title class="flex items-center justify-between" >    
            <div class="header-menu q-pa-xs">
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
          </div>   git
        </q-toolbar-title>
       
        

      </q-toolbar>
      
      

      <q-separator></q-separator>
      <div class="nav-menu flex container content-center">
        
          <q-btn-dropdown menu-anchor="bottom left" menu-self="top left" color="primary" label="Accounts" class="q-btn-nav">
            <q-list >
              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section >
                  <q-item-label>Current account</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Foreign Currency Account</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Student Account</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Opening an account through viber</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Payment transactions</q-item-label>
                </q-item-section>
              </q-item>
            </q-list>
          </q-btn-dropdown>
       
          <q-btn-dropdown flat  menu-anchor="bottom left" menu-self="top left" color="primary" label="Cards" class="q-btn-nav">
            <q-list>
              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section>
                  <q-item-label>Debit card</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Credit cards</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Prepaid cards</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Our wednesday</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Report card loss</q-item-label>
                </q-item-section>
              </q-item>
            </q-list>
          </q-btn-dropdown>
    
          <q-btn-dropdown flat  menu-anchor="bottom left" menu-self="top left" color="primary" label="Loans" class="q-btn-nav">
            <q-list>
              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section>
                  <q-item-label>Cash loans </q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Mortgage loans</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>commodity loans</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Deposit loan</q-item-label>
                </q-item-section>
              </q-item>
            </q-list>
          </q-btn-dropdown>
    
          <q-btn-dropdown flat  menu-anchor="bottom left" menu-self="top left" color="primary" label="Savings" class="q-btn-nav">
            <q-list>
              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section>
                  <q-item-label>Savings accounts</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Term savings</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Free savings</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Children's savings account</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Free children-s savings</q-item-label>
                </q-item-section>
               
              </q-item>
            </q-list>
          </q-btn-dropdown>
  
          <q-btn-dropdown flat  menu-anchor="bottom left" menu-self="top left" color="primary" label="Online services" class="q-btn-nav">
            <q-list>
              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section>
                  <q-item-label>Mobile banking</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Internet banking</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Security</q-item-label>
                </q-item-section>
               
              </q-item>
            </q-list>
          </q-btn-dropdown>
  
          <q-btn-dropdown flat  menu-anchor="bottom left" menu-self="top left" color="primary" label="Other services" class="q-btn-nav">
            <q-list>
              <q-item clickable v-close-popup @click="onItemClick">
                <q-item-section>
                  <q-item-label>Moneygram</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Pika card loyalty program</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Western union</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Currency exchange</q-item-label>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Security safes</q-item-label>
                </q-item-section>
               
              </q-item>
            </q-list>
          </q-btn-dropdown>
        
      </div>
      


      
    </q-header>

    <q-page-container>
      <!-- <router-view /> -->
     
    </q-page-container>

  </q-layout>
</template>




<script>
export default {
  setup () {
    return {
      onItemClick () {
        console.log('Clicked on an Item')
      }
    }
  }
}
</script>


<style lang="scss">

.q-field--standard .q-field__control:before {
    border-bottom: 0 !important;
    transition: border-color 0.36s cubic-bezier(0.4, 0, 0.2, 1);
}
  
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
    box-shadow: 0px 1px 15px 0px rgb(76, 75, 75, 0.2)
  }

  .nav-menu{
    height: 44px !important;
  }

  .q-menu{
    max-width: 200px;
    text-transform: uppercase;
    margin-top: 8px !important;
    border-radius: 0 !important;
    

    .q-item{
      display: flex;
      flex-direction: column;
      gap:20px;
      margin-top: 10px;
      padding: 6px;
    }
    .q-list .q-item .q-item__section{
      margin-left: 8px;
    }
    .q-item__label{
      font-weight: 500;
      letter-spacing: 1px;
    }

  }

  
    .q-btn-nav.q-btn{
      font-size: 12px;
      color: black !important;
      background-color: transparent !important;

    }

    .q-btn-nav.q-btn:before{
      box-shadow: none;
    }

    .q-btn-nav.q-btn .q-focus-helper {
      display: none;
    }

    .q-btn .q-btn__content:hover{
      color: #1976D2;
    }


    
  


  


</style>
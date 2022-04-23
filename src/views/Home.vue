<template>
  <div class="full-wrapper">

    <div class="hero" style="min-height:100vh; display:flex;flex-flow:column;justify-content:center;padding-top:4rem;padding-bottom:4rem;">
      <div class="title" style=" margin:auto;text-align:center;font-size:7rem;margin-bottom:0rem;">
      <h1><b style="font-size:12rem;line-height:0.8;">THE</b><br><b style="font-size:6rem;line-height:0.8;">CEDAR</b><br><b style="font-size:6rem;line-height:0.8;">BEARD</b><br><b style="font-size:3.1rem;line-height:0.8;">COLLECTION</b></h1>
      </div>
      <div class="subtitle" style="margin:auto;margin-top:2rem;max-width:512px;padding-top:1rem;margin-bottom:0rem;">
      <h3 style="text-align:center;width:512px;margin:auto;">A collection of original pieces manifested by Greg Cedarbeard</h3>
      </div>
      <div class="cta" style="margin:auto;margin-top:4rem;"><div class="button" style="border-radius:0.25rem;border:2px solid white;padding:0.5rem 1rem;"><h3>MANIFEST</h3></div></div>
    
    </div>




    <div class="bio">

      <div class="title">
        <h1 style="text-align:center;">The Cedarbeard Lore</h1>
      </div>
      <div class="desc" style="padding-top:4rem;max-width:720px;margin:auto;">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

      </div>
      
    </div>


    <div class="row"></div>



    </div>
</template>

<script>
import { mapState, mapActions } from 'vuex';
export default {
  data() {
    return {
      form: {
        quantity: ''
      },
      modalLoginOpen: false,
      modalMakepotionOpen: false
    };
  },
 components: {
    
  },
};
</script>
<style scoped>
h2{font-size:1.5rem;}
p{max-width:calc(100vw - 4rem);
margin:auto;}
.parallax-card.front{
    width: max-content!important;
    height: fit-content!important;min-height:200px;}
.parallaxtoph1{text-align:center;color:white!important;font-size:4rem;}
.gladiators{width:30%;display:flex;flex-flow:wrap;
justify-content:center;}
.gladiators2{display:none;flex-flow:wrap;
justify-content:center;}
  .gladiators > img{transition:all 0.2s ease;margin:auto;max-width:100%;}
  .gladiators > img:hover{transform:scale(1.1);}  .gladiators2 > img{transition:all 0.2s ease;margin:auto;max-width:512px;}
  .gladiators2 > img:hover{transform:scale(1.1);}
.whitelist{text-align:center;}
.socialicon{width:64px;margin-left:1rem;margin-right:1rem;transition:all 0.2s ease;}
.socialicon:hover{transform:scale(1.1);}
.parallaxtop{font-size:4rem;padding-top:1rem;}  .nodesktop{display:none;}
  .row{height:100%;}

.joinbutton{padding: 1rem;
border-radius: 0.25rem;
color: black;transition:all 0.2s ease;background-color:gold;border:unset;font-size:1.5rem;box-shadow:0px 4px black,0px 4px 10px rgba(0,0,0,0.2);}
.joinbutton:hover{background-color:black;transform:scale(1.1);border:unset;font-size:1.5rem;box-shadow:0px 2px black,0px 2px 10px rgba(0,0,0,0.2);color:gold;}
.connectwallet{background-color:transparent;border:1px solid white;box-shadow:0px 2px black;color:white;margin-bottom:2rem;transition:all 0.2s ease;}
.connectwallet:hover{background-color:white;border:1px solid white;box-shadow:0px 2px black;color:black;}
@media screen and (max-width:600px) {.gladiators2{display:flex;flex-flow:wrap;
justify-content:center;}
  .nomobile{display:none;}
  .nodesktop{display:block;}h2{font-size:1rem;}
  h1{font-size:2rem!important;max-width:calc(100vw - 4rem);margin:auto;}
   .gladiators{display:none;flex-flow:row;justify-content:center;}
  .gladiators > img{margin:auto 2rem;max-height:128px;}  .gladiators2 > img{margin:auto 2rem;max-height:128px;}
  .row{flex-flow:column;}  .gladiators2{display:flex;flex-flow:row;}
.parallaxtop{transition:all 0.2s ease;padding-top:2rem;}
.parallaxtoph1{text-align:center!important;margin:auto;color:white!important;font-size:2rem!important;padding-top:40px;}

}.hasEffect {
  cursor: pointer;
}
</style>


<template>
  <div class="full-wrapper">
      <div class="header-wrapper" style="margin-top:4rem;padding:2rem;display:flex;flex-flow:row;justify-content:space-between;">

        <h3 style="letter-spacing:2px;font-size:48px;margin:auto;text-align:left;margin-left:2rem;">GEOMETRIC CURATED</h3>
        
        <div class="socials">
          <a href="">
            <img src="~/@/assets/twitter.svg" style="width:48px;height:48px;margin:1rem;" alt="">
          </a>

        </div>
      </div>

      <div class="display-wrapper" style="display:flex;flex-flow:wrap;margin-top:2rem;">
     <a href="https://opensea.io/collection/prismnft" target="_blank">
        <div class="artbox" style="">
          <div class="art" style="">
            <img src="https://lh3.googleusercontent.com/XlTCNr7I3fQO5V42WqMRjl8KCS3NDT_EN9wOSrAr2e4Mxe6JnfBJMbeIEm_cZbkuutzWFSuEMxqJBVKw1aqEa62LRjVH1OYgDfRbjpk=w358" style="width:100%;height:100%;background:#e1e1e1;border:1px solid #1111;" alt="">
          </div>
          <div class="artdesc" style="">
            <p style="margin:1rem;line-height:2rem;" >Prism NFT // 100 ITEM COLLECTION</p>
            <p style="transform:rotate(180deg);margin:1rem;line-height:2rem;" >ART COLLECTION BY SAWYER KOTOWSKI</p>

          </div>

        </div>
      </a>

     <a href="https://opensea.io/collection/lensesnft" target="_blank">

         <div class="artbox" style="">
          <div class="art" style="">
            <img src="https://lh3.googleusercontent.com/t2k1xWOIDN6rUCoJQBjpMFCcuHaTprF-UMiGUtLiysHM_rshTT6ULZ4LucSCi8jnBrlSWkozavib1EPREZ4sF8-CSF7iAAmN52Segw=w358" style="width:100%;height:100%;background:#e1e1e1;border:1px solid #1111;" alt="">
          </div>
          <div class="artdesc" style="">
            <p style="margin:1rem;line-height:2rem;" >Lenses NFT // 50 ITEM COLLECTION</p>
            <p style="transform:rotate(180deg);margin:1rem;line-height:2rem;" >ART COLLECTION BY SAWYER KOTOWSKI</p>

          </div>

        </div>
</a>
        

     <a href="https://opensea.io/collection/juniperantaresnft" target="_blank">

         <div class="artbox" style="">
          <div class="art" style="">
            <img src="https://lh3.googleusercontent.com/nHKrrxF-vt_ZA__1xk1SEBI3fAWVKR_JqSIVsLQtShNQMMjfZq15F4uSlZiK91siHFL3-nf7N6fC8dhlCbdvvYQw3yyduQ7SRWSYV90=w358" style="width:100%;height:100%;background:#e1e1e1;border:1px solid #1111;" alt="">
          </div>
          <div class="artdesc" style="">
            <p style="margin:1rem;line-height:2rem;" >Juniper Antares NFT // 22 ITEM COLLECTION</p>
            <p style="transform:rotate(180deg);margin:1rem;line-height:2rem;" >NAMESAKE MIXED MEDIA COLLECTION</p>

          </div>

        </div>
</a>
        

     <a href="https://opensea.io/collection/uapnft" target="_blank">

         <div class="artbox" style="">
          <div class="art" style="">
            <img src="https://lh3.googleusercontent.com/cj4qT5EqTtcEizkBVYwVtUuYTEnHpmWaojKV6FdWEexe_8G3oPpFRS8Nkui9yXMIH8wuvVDcm3STc-Y6YBS0Zi2dFnmUtOB5ad7fRw=w358" style="width:100%;height:100%;background:#e1e1e1;border:1px solid #1111;" alt="">
          </div>
          <div class="artdesc" style="">
            <p style="margin:1rem;line-height:2rem;" >UAP NFT // 22 ITEM COLLECTION</p>
            <p style="transform:rotate(180deg);margin:1rem;line-height:2rem;" >UNIDENTIFIED AERIAL PHENOMENA</p>

          </div>

        </div>

</a>
        

     <a href="https://opensea.io/collection/blackholesnft" target="_blank">

         <div class="artbox" style="">
          <div class="art" style="">
            <img src="https://lh3.googleusercontent.com/UtHNcQnO0KHJlCrcV1q3EDOz-iMV6gq6f4793vr7824keSGxGwzAxs2DZ9twmM9J5msMQh6jDmUpREsZ4OGizPseEfJhzbPhE9Ow=w358" style="width:100%;height:100%;background:#e1e1e1;border:1px solid #1111;" alt="">
          </div>
          <div class="artdesc" style="">
            <p style="margin:1rem;line-height:2rem;" >Black Holes NFT // 30 ITEM COLLECTION</p>
            <p style="transform:rotate(180deg);margin:1rem;line-height:2rem;" >ART COLLECTION BY SAWYER KOTOWSKI</p>

          </div>

        </div>
</a>

        
     <a href="https://opensea.io/collection/spectrumnft" target="_blank">


         <div class="artbox" style="">
          <div class="art" style="">
            <img src="https://lh3.googleusercontent.com/zCKoOCzf3iRAOBTL3w9E7dIQSMM_qYPmeCNHjGNJHqu6rZvtz2VeFS0dvf5zzeEZJm6h3-Ibs5l4eW3g72lVJ7cNbqxjE4wW089-0A=w358" style="width:100%;height:100%;background:#e1e1e1;border:1px solid #1111;" alt="">
          </div>
          <div class="artdesc" style="">
            <p style="margin:1rem;line-height:2rem;" >Spectrum NFT // 9 ITEM COLLECTION</p>
            <p style="transform:rotate(180deg);margin:1rem;line-height:2rem;" >35MM FILM ORIGINALS BY REBECCA REID </p>

          </div>

        </div>
</a>

        



    </div>

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


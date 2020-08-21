<template>
  <div id="app">
    
    <img
      src="https://scontent.fcnx3-1.fna.fbcdn.net/v/t1.15752-9/117811868_347454456283024_2149302450798741576_n.jpg?_nc_cat=109&_nc_sid=b96e70&_nc_eui2=AeGA4210XXGVEfT5ZEpPEtxuuwPYzkjM7IK7A9jOSMzsgmykah-Pcs747VIPAeQWE_tkd4MD4cM7P-YZUM2IHXn7&_nc_ohc=XqW2rtc3A64AX8Fj2Ba&_nc_ht=scontent.fcnx3-1.fna&oh=b2fc60abac478436f0354653118a553b&oe=5F64CAD0"
      class="rounded-circle"
      width="20%"
    />
    <p>
      <br />
    </p>
    <HelloWorld msg="NAPAPORN" />
    <br />
    <div class="row">
      <div class="col-4">
        <img
          src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/102886005_307245433609832_6611561215449872627_n.jpg?_nc_cat=105&_nc_sid=b96e70&_nc_eui2=AeGqbG4iH_Nq92MfCP-pBWAo6JKQeeHC8z7okpB54cLzPp1BnIC87DI9g21YnpmNZPcmJ5ZTwzq5cTmcGRg31Lik&_nc_ohc=bRboeSiBn9UAX-QRkma&_nc_oc=AQnZqbSQnCz3nSCj0_SJQ8t94GPirDS2DdP-lr024p3xEKOjNxFWXNZL3h4iNna8COT80K5lcO_lveM1GWL5GHJZ&_nc_ht=scontent.fcnx4-1.fna&oh=045ba0e9d1111844923a0aa3c25db0b8&oe=5F669A45"
          class="rounded-circle"
          width="50%"
        />
        <p>
          <br />
        </p>
        <Button />
      </div>
      <div class="col-4">
        <img
          src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.0-9/117742033_152388153157935_5473762905718481070_o.jpg?_nc_cat=101&_nc_sid=8bfeb9&_nc_eui2=AeEtenluXzBlzGpLvBHUG51xTJTigckX1CFMlOKByRfUIeh9G4lRTtghNtwfm6tE3i7BHE_ff00g1oaNwBgwdOZx&_nc_ohc=WElViYT-nfEAX_QLQa8&_nc_ht=scontent.fcnx4-1.fna&oh=75928085ed9742f15c1abc8b6d865645&oe=5F62F2FF"
          class="rounded-circle"
          width="50%"
        />
        <p>
          <br />
        </p>
        <Button />
      </div>
      <div class="col-4">
        <img
          src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/117772079_1701860536657632_8323661288183556807_n.jpg?_nc_cat=107&_nc_sid=b96e70&_nc_eui2=AeE4vi0-hJ2aKj3_zMTKgauF66IRDlLmP3nrohEOUuY_eYY6p2ktx7YCJJ6jYrfDBmm09qs1SuW_v1qouUhcQLrG&_nc_ohc=-Gch3wxP-7EAX-imIxA&_nc_ht=scontent.fcnx4-1.fna&oh=90803a3b04786ae977811149ab78ff42&oe=5F649916"
          class="rounded-circle"
          width="50%"
          
        />
        <p>
          <br />
        </p>
        <Button />
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Button from "./components/Button";

export default {
  name: "App",
  components: {
    HelloWorld,
    Button,
  },

};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
<div>
	<h1>Trade or View your Portfolio</h1>
	<p>You may Save &amp; Load your data</p>
	<p>Click on <v-icon>mdi-domain</v-icon> to begin a new day</p>
	<h2>Your Funds: {{ funds | dollarFormat }}</h2>
</div>
</template>

<script>
   export default {
      computed: {
         funds() {
            return this.$store.getters.funds;
         }
      },
      methods: {
      
      }
   }
</script>


<style>
p{
   color:black;
}
</style>
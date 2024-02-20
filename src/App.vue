<!-- html -->
<template>
 <landingPage></landingPage>
 <myProjects></myProjects>
 <languages></languages>
 <about></about>
 <closing></closing>
</template> 


<script>
// import components here 
import landingPage from './components/landingPage.vue'; 
import myProjects from  './components/myProjects.vue';
import languages from './components/languages.vue';
import about from './components/about.vue';
import closing from './components/closing.vue';


// javscript
export default {
  // appName
  name: 'App',

  components: {   // components used by the app 
    landingPage,
    myProjects,
    languages,
    about,
    closing
  },

  data(){         // data object to define variables 
    return{
      name: "moachuba"
    }
  },

  methods:{        // methods

  }
}
</script>

<style>

/* css */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>

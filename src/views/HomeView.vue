<script setup>
import Container from '../components/Container.vue';
import keyImage from '@/assets/key.svg'; 
import checkImage from '@/assets/check.svg'; 
import docImage from '@/assets/documentatie.svg'; 
import settingImage from '@/assets/setting_lv.svg'; 

</script>

<template>
  <main>
    <div class="text_div">
      <h1>Real Estate Care</h1>
      <h3>Real Estate Care, Uw huis, onze zorg sinds 1999</h3>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolorum iste ad cupiditate perferendis officia quod hic soluta in deleniti accusantium numquam, at modi. Repellendus amet voluptatibus quod quisquam dignissimos. Culpa!</p>
    </div>

    <Container title="Toegewezen" buttonText="Toegewezen" korteText="Toegewezen rapportages" :sectionimage="keyImage" link="/toegewezen"/>
    <Container title="Uitgevoerd" buttonText="Uitgevoerd" korteText="Uitgevoerde rapportages" :sectionimage="checkImage" link="/uitgevoerd"/>
    <Container title="Documentatie" buttonText="Documentatie" korteText="Kennisbase/documentatie" :sectionimage="docImage" link="/documentatie"/>
    <Container title="Instellingen" buttonText="Instellingen" korteText="Instellingen/beheer" :sectionimage="settingImage" link="/settings"/>
  </main>
</template>

<style scoped>


h1 {
  font-size: 1.1rem;
  flex-wrap: wrap;
  margin-block-end: -1rem;
  text-transform:uppercase;
  margin-block-start: 2rem;
}

h3 {
  color: #00a9a2;
  font-size: .8rem;
  font-weight: 100;

}
p {
  font-weight: 250;
  font-size: 1rem;
  margin-block-end: 3rem;
}


</style>
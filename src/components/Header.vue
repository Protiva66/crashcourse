<template>
  <header>
    <h1>{{ title }}</h1>
    <Button @click="onClick()" color="navy" text="Add task" />
  </header>
</template>

<script>
import Button from './Button'

export default {
  name: "Header",
  props: {
    title: String,
  },
  components: {
      Button 
  },
  methods:{
      onClick(){
          console.log('prdel');
      }
  }
};

</script>
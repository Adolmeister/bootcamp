<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br />
    <br />
    Siema!
    <br/>
    {{ licznik }}
    <br/>
    <button @click="increase">podbij</button>
    <br/>
    <button @click="decrease">zmniejsz</button>

  </main>
</template>

<script>
export default{
  data(){
    return{
      licznik: 0
    }
  },
  methods:{
    increase(){
      this.licznik++
    },
    decrease(){
      this.licznik--
    }
  }
}

</script>
<template>
  <div>
    <!-- <HeaderC :username="name"></HeaderC>
    <BodyC></BodyC>
    <BodyC></BodyC> -->
    <h1>カウントアップ</h1>
    <p>count: {{ count }}</p>
    <button @click="increment">+1</button>
  </div>
</template>

<script>
// import HeaderC from './components/HeaderComponent.vue'
// import BodyC from './components/BodyComponent.vue'

export default {
  // components: {
  //   HeaderC,
  //   BodyC
  // },
  data(){
    return {
      // name: "kiyokiyo"
      count: 0
    }
  },
  methods: {
        increment(){
            this.count += 1;
        }
    }
}
</script>

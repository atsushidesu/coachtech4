<template>
  <div id="app">
   <h1>名前は{{number.name}}</h1>
   <h1>年齢は{{number.age}}</h1>
   <h1>生まれは{{number.from}}</h1>
  </div>
</template>

<script>
export default {
  data(){
    return{
      number:{
        name: "荒屋敷惠美子",
        age: 70,
        from: "是川"
      }
    };
  }
};
</script>


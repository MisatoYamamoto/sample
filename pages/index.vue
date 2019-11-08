<template>
<div>
  <h1>お寿司 !! world </h1>

  <NLink to ="/about" >About Page </NLink>
  <br>
  <NLink to ="/second" >Second Page </NLink>
  <br>
  <input v-model="message">
   <img src = "https://dlove.jp/mezzomiki/wp-content/uploads/2018/08/happy-kuji-pixar-51.jpg">

</div>


</template>

<script>
  export default {
　data() {
　　return {
    message:"kkkkk",
};
}
};
</script>

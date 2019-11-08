<template>
<div>
  <h1>Hello   </h1>

  <NLink to ="/about" >About Page </NLink>
  <br>
  <NLink to ="/second" >Second Page </NLink>
  <br>
  <input v-model="message">
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

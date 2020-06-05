<template>
  <div>
    <b-nav>
      <b-nav-item active>Fancy Quiz</b-nav-item>
      <b-nav-item>counter:{{numcorrect}}/{{numTotal}}</b-nav-item>
    </b-nav>
  </div>
</template>
<script>
export default{
  props:[
    'numcorrect',
    'numTotal'
  ]
}
</script>

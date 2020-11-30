<template>
<div><p style="color: {{dataBackgroundColor}}">sss</div>
</template>

<script>
export default {
  name: "keyword-card",
  props: {
    dataBackgroundColor: {
      type: String,
      default: ""
    }
  }
};
</script>

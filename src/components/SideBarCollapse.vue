<template> 

</template>
<script>
export default {
  data() {
    return {
      clickable: true,
    };
  },
  methods: {
    handleSidebarToggle() {
      this.clickable = false;
    },
  },
};
</script>

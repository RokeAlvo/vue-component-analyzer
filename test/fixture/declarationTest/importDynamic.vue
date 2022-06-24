<template>
  <div />
</template>

<script>
  import nested from '../../components/nested.vue';
  import nested2 from '../../components/nested2.vue';

  const dynamicComponent = import('../../components/nested.vue');
  import parser from 'vue-eslint-parser';

  const CONST = {}

  export default {
    name: 'Dynamic import',
    components: {
      dynamicComponent,
    },
  };
</script>

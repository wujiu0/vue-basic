<template>
  <div>
    <h2>学校名字：{{ name }}</h2>
  </div>
</template>

<script>
const School = Vue.extend({
    name: 'School',
    data() {
        return {
            name: 'nuc',
        };
    },
});
export {School};
</script>
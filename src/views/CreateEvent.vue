<template>
    <SimpleForm />
</template>

<script>
import SimpleForm from '@/components/forms/SimpleForm.vue'
export default {
  name: 'CreateEvent',
  components: {
    SimpleForm, // register it as a child component
  },
}
</script>
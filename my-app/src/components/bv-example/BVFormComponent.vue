<script>
import { reactive } from 'vue'
export default {
  name: 'BVFormComponent',
  setup() {
    const formData = reactive({
      name: '',
      comments: '',
      performance: 50
    })

    const onSubmit = (event) => {
      event.preventDefault()

      console.log('/// Do something')
    }
    return { formData, onSubmit }
  }
}
</script>

<template>
  <b-form @submit="onSubmit">
    <b-form-group description="Personal Info">
      <label>Name</label>
      <b-form-input v-model="formData.name" placeholder="Your Name Here"> </b-form-input>
    </b-form-group>

    <b-form-group>
      <label> Comments </label>
      <b-form-textarea v-model="formData.comments"></b-form-textarea>
      <label>Performace Rating</label>
      <b-form-input type="range" v-model="formData.performance"></b-form-input>
    </b-form-group>
    <b-button variant="info" type="submit">Submit</b-button>
  </b-form>
</template>

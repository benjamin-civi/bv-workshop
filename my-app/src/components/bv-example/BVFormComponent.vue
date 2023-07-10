<script>
import {reactive} from "vue"
export default{
    name: 'BVFormComponent',
    setup(){
        const formData = reactive({
            name: '',
            comments: '',
            performace: 50,
        })

        return {formData}
    },
}
</script>

<template>
    <b-form>
    <b-form-group description="Personal Info">
    <label>Name</label>
    <b-form-input v-model="formData.name" placeholder="Your Name Here">
    </b-form-input>
    </b-form-group>
    
    <b-form-group>
    <label> Comments </label>
    <b-form-textarea v-model="formData.comments" ></b-form-textarea>
    <label>Performace Rating</label>
    <b-form-input type="range" v-model="formData.performace"></b-form-input>
    </b-form-group>
    </b-form>
</template>
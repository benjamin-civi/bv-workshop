<script>
import {ref} from "vue"
export default{
    name:'HelloWorldComponent',
    setup(){
        const msg=ref("Hello BootstrapVue World")

        return {msg}
    }
}

</script>
<template>
<b-card >
{{ msg }}
</b-card>
</template>
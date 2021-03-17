<template>
    <div class="mensaje">
        <p>{{mensaje}}</p>
        <Hijo></Hijo>
    </div>
</template>

<script>
import Hijo from './Hijo'

export default {
    data () {
        return {
            mensaje: 'Soy el padre'
        }
    },
    components: {
        Hijo
    }
}
</script>

<style scoped>

</style>
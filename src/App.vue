<template>
    <div id="app">
        <DraggableGroups/>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import DraggableGroups from './components/DraggableGroups.vue';

@Component({
    components: {
        DraggableGroups,
    },
})

export default class App extends Vue {
}

</script>

<style lang="scss">
    @import 'styles/normalize';
    @import 'styles/reset';

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;    
    }
</style>

<template>
    <DevineurVue 
    :titre="'vocabulary'"
    />
</template>

<script>
import DevineurVue from './Devineur.vue';
export default {
    name: 'VocabularyVue',
    components: {
        DevineurVue,
    },
};
</script>
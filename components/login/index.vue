<template>
    <h1>{{ say }}</h1>
</template>
<script>
import { getHi } from '~/assets/test';
export default {
    data() {
        return {
            say: null
        };
    },
    created() {
        this.say = getHi();
    }
};
</script>
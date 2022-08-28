<template>
    <div id="show-auth"/>
</template>

<script>
export default {
    mounted() {
        console.log('mounted');
        console.log(this.$auth0);
        this.$auth0.showLock("show-auth");
    }
};
</script>
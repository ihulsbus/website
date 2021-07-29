<template>
    <h1>Hi, Welcome</h1>
    <span>
        <p>Unfortunately there's nothing here. There should be, but I've not had the time to make awesome content for this site.</p>
        <p>In the mean time, take a look at my Github profile if you want.</p>
        <Button label="Github" icon="pi pi-github" @click="btnClick" />
    </span>
</template>

<script>
export default {
    name: 'MainPage',
    methods : {
        btnClick() {
            window.open("https://github.com/ihulsbus");
        }
    }
}
</script>

<style lang="scss" scoped>

</style>
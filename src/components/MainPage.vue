<template>
    <h1>Hi, Welcome</h1>
    <span>
        <p>Unfortunately there's nothing here. There should be, but I've not had the time to make awesome content for this site.</p>
        <p>In the mean time, take a look at my Github or LinkedIn profile if you want.</p>
        <Button style="margin-right: 0.5rem;" class="github" label="Github" icon="pi pi-github" @click="github" aria-label="Github"/>
        <Button class="linkedin" label="LinkedIn" icon="pi pi-linkedin" @click="linkedin" aria-label="LinkedIn"/>
    </span>
</template>

<script>
export default {
    name: 'MainPage',
    methods : {
        github() {
            window.open("https://github.com/ihulsbus");
        },
        linkedin() {
            window.open("https://linkedin.com/in/ianhulsbus");
        }
    }
}
</script>

<style>
.p-button {
        margin-right: 0.5rem;
    }
</style>
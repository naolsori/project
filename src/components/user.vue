<template>
<div class="user">
    <h1> {{data.name}} </h1>
    <h1> {{data.email}} </h1>
    <button v-on:click="getdata(data.name)"> add click </button>
</div>
</template>

<script>
export default {
    name: 'user',
    props: {
        data: Object,
        getdata: Function,
    },
   
}
</script>

<style>
.user {
    background-color: skyblue;
    border-bottom: 1px solid;
    padding: 10px;
    margin-bottom: 15px;
}
</style>

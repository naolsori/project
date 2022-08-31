<template>
<div class="user">
   <header><slot name="header">data is trasnfered</slot></header>
   <content><slot name="main">data is trasnfered</slot></content>
   <footer><slot name="footer">data is trasnfered</slot></footer>
</div>
</template>

<script>
export default {
    name: 'user',
}
</script>
<style>
    .user{
    border: 1px solid;
        width: 198px;
        border-color: skyblue;
        padding: 25px;
        margin: 33px;
    }
    </style>
    
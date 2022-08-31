<template>
<user>
    <template v-slot:header>
        <h1> peter </h1>
    </template>
    <template v-slot:main>
        <p> nahu</p>
    </template>
    <template v-slot:footer><button>Buy now</button></template>

</user>
<user>
    <template v-slot:header>
        <h1> peter </h1>
    </template>
    <template v-slot:main>
        <p> nahu</p>
    </template>
    <template v-slot:footer><button>Buy now</button></template>

</user>
</template>

<script>
import user from './user.vue'
export default {
    name: 'part',
    components: {
        user
    }
}
</script>


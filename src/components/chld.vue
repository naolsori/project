<template>
<ul>
    <li v-for="item in users" :key="item.name">
        <user :data="item" /></li>
</ul>
</template>

<script>
import user from './user.vue'
export default {
    name: 'chld',
    components: {
        user
    },

    data() {
        return {
            users: [{
                    name: "tom",
                    email: "tom@test.com"

                },
                {
                    name: "abr",
                    email: "abr@test.com"

                }
            ]
        }
    }
}
</script>

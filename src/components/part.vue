<template>
    <ul>
        <li v-for="item in users" :key="item.name">
            <user :data="item" :getdata="getdata" /></li>
    </ul>
    </template>
    
    <script>
    import user from './user.vue'
    export default {
        name: 'part',
        components: {
            user
        },
        methods: {
        getdata(name){
            alert(name)
        }
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
    
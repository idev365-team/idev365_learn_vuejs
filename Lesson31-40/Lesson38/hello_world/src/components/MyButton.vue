<template>
    <button v-on:click="sayHi">
       {{ title }}
    </button>
</template>

<script>
export default {
    name:"MyButton",
    props:{
        "msg":{
            type:String,
            default:"Who are you?",
        },
        "title":{
            type:String,
            default:"Button",
        }
    },
    methods:{
        sayHi:function(){
            alert("Hi,"+this.msg)
        }
    }
}
</script>

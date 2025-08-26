<template>
    <p>{{ msg }}</p>
    <p>{{ number + 1 }}</p>
    <p>姓名{{ obj.name }},年龄{{ obj.age }}岁</p>
</template>

<!-- <script>
    export default{
        data(){
            return{
                msg:'Hello Vue'
            }
        }
    }
</script> -->
<script setup>
    // 数据绑定
    const msg = 'hello vue'
    const number = 99
    const obj = {name:'小明',age:'19'}
</script>
<template>
    <div class="demo">
        <h2>学校名称：{{schoolName}}</h2>
        <h2>学校地址：{{addr}}</h2>
    </div>
</template>

<script>
export default {
    name:'School',
    //组件中data必须为函数式
    data(){
        return {
            schoolName:'学校名称',
            addr:'北京昌平'
        }
    },
    methods: {
        showName(){
            alert(this.schoolName)
        }
    },
}
</script>

<style>
    .demo{
        background-color: orange;
    }
</style>

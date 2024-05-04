<template>
    <div>
        <h2>学生姓名：{{studentName}}</h2>
        <h2>学生年龄{{age}}</h2>
    </div>
</template>

<script>
export default {
    name:'Student',
    data(){
        return {
            studentName:'赵六',
            age:20
        }
    },
    methods: {
        showName(){
            alert(this.studentName)
        }
    },
}
</script>

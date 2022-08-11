<template>
    <div>
        <School></School>
        <Student></Student>
    </div>
</template>

<script>
    //引入组件,后缀可有可无
    import School from './School'
    import Student from './Student'
    export default {
        name:'App',
        components:{
            School,
            Student
        }
    }
</script>
<script>
export default {
    data(){
        return{
            title : "Robert Redford",
            person:{
                id: 5,
                name : 'Robert',
                img : "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSuCPkX0-6NfVtfnQfaNrvh9DCLtPbR6-TbTQ&usqp=CAU",
            },
            msg: "Person who directed 'The Horse Whisperer'",
        } 
    },
};
</script>


<template>
    <h3>{{ title }}</h3>
    <div :id="person.id">    
        <h4>{{ person.name }}</h4>
        <img :src="person.img" :alt="person.name">
    </div>
    <h5>{{ msg }}</h5>
    <h5 v-html="msg"></h5>
</template> 


<style lang="css" scoped>
h3{
    color: rgb(11, 142, 230);
}
</style>
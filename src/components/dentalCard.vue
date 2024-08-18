<script>
export default {
  name: 'App',
  data (){
        return{
            data1: data,
            
        }
    },
    props: {
        nivti: {
            required: true,
            type: Object,
        }
    }
};
</script>

<template>
    <div>
        <div class="dentalCard">
            <h1>{{ nivti.name }}</h1>
            <h1>Hello</h1>
            
        </div>        
    </div>
</template>


<style scoped>
.dentalCard{
    height: 330px;
    width: 270px;
    background-color: red;
}
    
</style>
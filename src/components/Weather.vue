<template>
    <div class="header">
        <h1>thing </h1><br>
              
    </div>
</template>

<script>
export default {
    name: "Header",
    props:['title'],
}
</script>

<style scoped>
    .header{
        background: rgb(181, 199, 223);
        color: rgb(22, 21, 41);
        text-align: center;
        padding: 10px;
        margin: 0px;
    }

</style>
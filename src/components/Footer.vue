<template>
    <div class="header">
        <h6>Hannah Givens &copy; Dec 2020</h6>
        <p>Weather provided by: openweathermap.org</p>
    </div>
</template>

<script>
export default {
    name: "Header",
    // props:['title'],
}
</script>

<style scoped>
    .header{
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        background-color: black;
        color: white;
        text-align: center;
    }
    p{
        font-size: 10px;
    }
    h6{
        font-size: 12px;
    }

</style>
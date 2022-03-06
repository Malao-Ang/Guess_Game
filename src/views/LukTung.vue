<template>
    <body>
        <div class="TextStrat">
            <link href="https://cdn.jsdelivr.net/npm/daisyui@2.4.0/dist/full.css" rel="stylesheet" type="text/css" />
        <h1>Are You Ready ?!</h1>
        </div>
        <div class="piccan" id="pic">
            <img src="..\assets\images\Picture1.png" >
        </div>
        <div class="ask">
            <div class="grid">
                <router-link to="/LukTung1/song1">
                    <button class="btn btn-info">Yes</button>
                </router-link>

                <router-link to="/">
                    <button class="btn btn-error">No</button>
                </router-link>
            </div>
        </div>
    </body>
</template>
<script src="https://cdn.tailwindcss.com"></script>
<script>

export default {
    data:()=>({
        showImage: true,
    })

}
</script>

<style>
h1{
    color: rgb(0, 0, 0);
}
body {
    background-color: rgb(216, 189, 141);
}
.TextStrat{
    padding: auto auto auto;
    text-align: center;
    font-size: 100px;
}
.piccan img{
    display:block;
    margin: auto auto auto;
    width:30%;
    
}
.ask .grid{
    display: grid;
    grid-template-columns: auto auto ;
    gap: 10px;
    padding: 20px;
}
.ask button{
    width:100%;
}
</style>
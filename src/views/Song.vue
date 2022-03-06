<template>
<body>
    <div class="container">
        <div id="game" class="justify-center flex-column">
            <div id="hud">
                <div class="hud-item">
                    <p id="processText" class="hud-prefix">
                        Question
                    </p>
                    <div id="processBar" >
                        <div id="processBarfull">

                        </div>
                    </div>
                </div>
                <div class="hud-prefix">
                    <p class="hud-prefix">
                        Score
                    </p>
                    <h1 class="hud-main-text" id="score">
                        0
                    </h1>

            </div>
        </div>
        <div id="question">What the fuck</div>

        <div class="chioce-container">
            <div class="choice-prefix">A</div>
            <div class="choice-text" data-number="1">Choice 1</div>
        </div>

        <div class="chioce-container">
            <div class="choice-prefix">B</div>
            <div class="choice-text" data-number="2">Choice 2</div>
        </div>

        <div class="chioce-container">
            <div class="choice-prefix">C</div>
            <div class="choice-text" data-number="3">Choice 3</div>
        </div>

        <div class="chioce-container">
            <div class="choice-prefix">D</div>
            <div class="choice-text" data-number="4">Choice 4</div>
        </div>

    </div>
    </div>
</body>
</template>

<script>
export default {

}
</script>

<style>
.TextStrat{
    padding: auto auto auto;
    text-align: center;
    font-size: 100px;
}
.small{
    padding: auto auto auto;
    text-align: center;
    font-size: 60px;
}
.swap {
    display: block;
    width: 100%;
    height: 100%;
    padding:50px;
}
:root {
    background-color: rgb(216, 189, 141);
}
.grid-ans{
    display: grid;
    grid-template-columns: auto auto;
    gap: 50px;
    padding:20px 50px ;
}


</style>
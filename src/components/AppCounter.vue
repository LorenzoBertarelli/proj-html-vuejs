<script>
    export default {
        name: "AppCounter"
    }
</script>

<template>
    <div class="container d-flex">
        <div class="card mb-3">
        <div class="card-body">
            <h5 class="card-counter">1.926</h5>
            <p class="card-text">FINISHED SESSIONS</p>
        </div>
        </div>
        <div class="card mb-3">
        <div class="card-body">
            <h5 class="card-counter">100%</h5>
            <p class="card-text">SATISFACTION RATE</p>
        </div>
        </div>
        <div class="card mb-3">
        <div class="card-body">
            <h5 class="card-counter">3.092</h5>
            <p class="card-text">ENROLLED LEARNERS</p>
        </div>
        </div>
        <div class="card mb-3">
        <div class="card-body">
            <h5 class="card-counter">200</h5>
            <p class="card-text">ONLINE INSTRUCTORS</p>
        </div>
        </div>
        <div class="back-card"></div>
    </div>
</template>

<style lang="scss" scoped>
    .container{
        padding: 0;
        max-width: 1100px;
        width: 100%;
        margin: 0 auto;
        justify-content: space-between;
    }
    .card{
        background-color: white;
        margin-top: 50px;
        padding: 0px 30px;
        align-items: center;
        border: none;
        background-image: url(../assets/images/background-pattern-grid-line-06.png);
        .card-counter {
            color: #20ac97;
            display: flex;
            justify-content: center;
            font-size: 2rem;
        }
    }

    .back-card {
        margin-top: 55px;
        margin-bottom: 18px;
        width: 1px;
        background-image: url(../assets/images/background-pattern-grid-line-06.png);
    }

    .bg-primary{
        background-color: none;

    }
</style>
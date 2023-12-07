<template>
    <div>
        <section class="information">
            <div class="descrip_">
                <h2>Leading Edge Technology</h2>
                <p>Easy to use management tools, our fastest possible execution and spreads as low as 0.0.</p>
                <a href="">Quick Guide: CommuniTraders Web User Manual</a>
            </div>
            <div class="img_">
                <div></div>
            </div>
        </section>
    </div>
  </template>
  
  <script setup>
  
  </script>
  
<style scoped>
.information {
    display: flex;
    justify-content: center;
    gap: 150px;
    padding: 100px;
    background: #F2F2F2;
    align-items: center;
}

.information .descrip_ {
    width: 50%;
    max-width: 576px;
    display: flex;
    flex-direction: column;
    gap: 30px;
}

.information .descrip_ h2 {
    font-size: 30px;
    color: #363636;
    font-weight: 900;
    line-height: 45px;
}

.information .descrip_ p {
    font-size: 25px;
    font-weight: 400;
    color: #363636;
    line-height: 36px;
}

.information .descrip_ a {
    font-size: 25px;
    font-weight: 400;
    color: #363636;
    line-height: 36px;
    font-size: 18px;
    text-decoration: underline;
}

.information .img_ {
    width: 50%;
    max-width: 576px;
}

.information .img_ div {
    width: 100%;
    padding-top: 89%;
    background-repeat: no-repeat;
    background-position: center;
    background-image: url(../assets/images/computers.png);
    background-size: contain;
}

@media (max-width: 991px) {
    .information .descrip_ h2 {
        font-size: 26px;
        line-height: 28px;
    }
    .information .descrip_ p {
        font-size: 20px;
        font-weight: 400;
    }
    .information {
        padding: 50px 75px;
        gap: 25px;
    }
}

@media (max-width: 767px) {
    .information {
        flex-direction: column-reverse;
    }
    .information .descrip_ {
        width: 100%;
    }
    .information .descrip_ h2 {
        text-align: center;
    }
    .information .descrip_ p {
        text-align: center;
    }
    .information .img_ {
        width: 100%;
        max-width: 375px;
    }
    .information {
        padding: 50px 35px;
    }
}
</style>
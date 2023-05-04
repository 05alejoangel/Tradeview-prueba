<template>
    <div>
        <section class="information">
            <div class="descrip_">
                <h2>Leading Edge Technology</h2>
                <p>Easy to use management tools, our fastest possible execution and spreads as low as 0.0.</p>
            </div>
            <div class="img_">
                <div style="background-image: url(images/computers.png);"></div>
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

    gap: 50px;

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
}

.information .descrip_ p {

    font-size: 25px;

    font-weight: 400;
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
}
  </style>
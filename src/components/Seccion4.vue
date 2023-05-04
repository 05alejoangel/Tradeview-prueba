<template>
    <div>
        <section class="sec-links">
            <div class="title">
                <h2>Try CommuniTraders Now!</h2>
            </div>
            <div class="links">
                <div class="btn_">
                    <p>Free Download for Tradeview Users </p>
                    <a class="bttn" href="#">Contact your Broker</a>
                </div>
                <div class="btn_">
                    <p>Don’t have a Tradeview Account yet?</p>
                    <a class="bttn-dark" href="#">Get a Free Demo</a>
                </div>
            </div>
        </section>
    </div>
  </template>
  
  <script setup>
  
  </script>
  
  <style scoped>
    /* ===================================
        SECCION LINKS
    =================================== */
    .sec-links {
        padding: 80px;
        background: #181F29;
        display: flex;
        flex-direction: column;
        gap: 50px;
    }

    .sec-links .title h2 {
        color: white;
        text-align: center;
        font-size: 30px;
    }

    .sec-links .links::before {
        width: 0.5px;
        content: "";
        position: absolute;
        left: 50%;
        transform: translateX(-50%);
        height: 135%;
        background: white;
        opacity: 0.4;
    }

    .sec-links .links {
        width: 100%;
        display: flex;
        justify-content: center;
        position: relative;
        gap: 100px;
    }
  </style>
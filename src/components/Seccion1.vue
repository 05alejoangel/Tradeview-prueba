<template>
    <div>
      <section class="banner">
            <div class="content">
                <div class="img_">
                    <div style="background-image: url(images/banner.jpg);"></div>
                </div>
                <div class="descript">
                    <div class="img_">
                        <div style="background-image: url(images/title.png);"></div>
                    </div>
                    <div class="cont">
                        <p>Tradeview’s <strong>CommuniTraders</strong> software lets our partners provide value-added copy trading to their clients.</p>
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
                </div>
            </div>
        </section>
    </div>
  </template>
  
  <script setup>
  
  </script>
  
  <style scoped>
    /* ======================================
        BANNER
========================================= */

.banner {
    margin-top: -216px;
}

.banner .content {
    display: flex;
}

.banner .content .img_ {
    display: flex;
    width: 44%;
}

.banner .content .img_ div {
    width: 100%;
    padding-top: 128%;
    background-repeat: no-repeat;
    background-position: center center;
}

.banner .descript {
    width: 56%;
    background: rgb(24, 31, 41);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 100px;
    gap: 65px;
}

.banner .descript .img_ {
    max-width: 493px;
    width: 100%;
}

.banner .descript .img_ div {
    width: 100%;
    padding-top: 33%;
    background-repeat: no-repeat;
    background-position: center center;
}

.banner .descript .cont {
    position: relative;
}

.banner .descript .cont::before {
    top: -16px;
    height: 1px;
    position: absolute;
    content: "";
    width: 100%;
    background: white;
    opacity: 0.7;
}

.banner .descript .cont p {
    font-size: 32px;
    text-align: center;
    color: white;
    max-width: 660px;
    width: 100%;
    font-weight: 200;
}

.banner .links {
    width: 100%;
    display: flex;
    justify-content: space-evenly;
    position: relative;
}

.banner .links::before {
    width: 0.5px;
    content: "";
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    height: 135%;
    background: white;
    opacity: 0.4;
}

.links .btn_ {
    display: flex;
    flex-direction: column;
    gap: 20px;
    align-items: center;
}

.links .btn_ p {
    color: white;
    font-weight: 300;
    text-align: center;
}

.links .btn_ a {
    z-index: 2;
    font-size: 18px;
    display: inline-block;
    text-align: center;
    width: 100%;
    max-width: 221px;
    letter-spacing: -0.3px;
    font-weight: 400;
    padding: 11px 18px;
    border-radius: 2px;
    position: relative;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 2px 10px, rgba(0, 0, 0, 0) 0px 3px 6px;
}

.links .btn_ a:hover {
    border-color: rgb(255, 0, 0);
}

.links .btn_ a.bttn-dark:hover {
    border-color: white;
}

.dark {
    background: rgb(36, 37, 42);
}

.flex {
    min-height: 50vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

a.bttn {
    color: white;
    text-decoration: none;
    transition: all 0.3s ease 0s;
}

a.bttn:hover {
    color: rgb(255, 255, 255);
}

a.bttn:focus {
    color: rgb(255, 255, 255);
}

a.bttn-dark {
    color: white;
    text-decoration: none;
    transition: all 0.3s ease 0s;
    border: 1px solid rgb(255, 0, 0);
}

a.bttn-dark:hover {
    color: rgb(255, 255, 255);
}

a.bttn-dark:focus {
    color: rgb(255, 255, 255);
}

.bttn {
    font-size: 18px;
    display: inline-block;
    text-align: center;
    width: fit-content;
    font-weight: 400;
    padding: 11px 18px;
    border: 1px solid white;
    border-radius: 2px;
    position: relative;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 2px 10px, rgba(0, 0, 0, 0) 0px 3px 6px;
}

.bttn::before {
    transition: all 0.5s ease 0s;
    position: absolute;
    inset: 0px 50%;
    opacity: 0;
    content: "";
    background-color: rgb(255, 0, 0);
    z-index: -2;
}

.bttn:hover::before {
    transition: all 0.5s ease 0s;
    left: 0px;
    right: 0px;
    opacity: 1;
}

.bttn:focus::before {
    transition: all 0.5s ease 0s;
    left: 0px;
    right: 0px;
    opacity: 1;
}

.bttn-dark::before {
    transition: all 0.5s ease 0s;
    position: absolute;
    inset: 0px;
    opacity: 1;
    content: "";
    background-color: rgb(255, 0, 0);
    z-index: -1;
}

.bttn-dark:hover::before {
    transition: all 0.5s ease 0s;
    left: 50%;
    right: 50%;
    opacity: 0;
}

.bttn-dark:focus::before {
    transition: all 0.5s ease 0s;
    left: 0px;
    right: 0px;
    opacity: 1;
}

.card {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 100px;
    gap: 25px;
}

.card .item {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 10px;
    max-width: 521px;
    padding: 25px;
    box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 13px 8px;
    height: 260px;
}

.card img {
    width: 50px;
}

.card h2 {
    font-size: 18px;
    color: rgb(255, 0, 0);
}

.card p {
    font-size: 18px;
    color: rgb(54, 54, 54);
    font-weight: 300;
}
  </style>
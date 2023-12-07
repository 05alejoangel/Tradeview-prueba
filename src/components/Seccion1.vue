<template>
    <section class="banner">
        <div class="content">
            <div class="img_">
                <div></div>
            </div>
            <div class="descript">
                <div class="img_">
                    <div></div>
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
  </template>
  
  <script setup>
  
  </script>
  
  <style scoped>
    /* ======================================
        BANNER
========================================= */

.banner {
    position: sticky;
    top: 0px;
    z-index: -1;
    margin-top: -60px;
}


.banner .content {
    display: flex;
}

.banner .content .img_ {
    display: flex;
    width: 44%;
}

.banner .content .img_ div {
    background-image: url(/src/assets/images/banner.jpg);
    width: 100%;
    padding-top: 129%;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: contain;
}

.banner .descript {
    width: 56%;
    background: rgb(24, 31, 41);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 153px 100px;
    gap: 85px;
}

.banner .descript .img_ {
    max-width: 415px;
    width: 100%;
}

.banner .descript .img_ div {
    width: 100%;
    padding-top: 33%;
    background-repeat: no-repeat;
    background-position: center center;
    background-image: url('../assets/images/title.png');
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
    gap: 30px;
    align-items: center;
}

.links .btn_ p {
    color: white;
    font-weight: 300;
    text-align: center;
    font-size: 18px;
}
.links .btn_ a {
    z-index: 2;
    font-size: 19px;
    display: inline-block;
    text-align: center;
    width: 100%;
    max-width: 238px;
    letter-spacing: .3px;
    font-weight: 400;
    padding: 13px 19px;
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

@media (max-width: 1500px) {
    .banner {
        margin-top: 0px;
    }
    .banner .content .img_ {
        display: flex;
        width: 50%;
    }
    .banner .descript .img_ div {
        width: 100%;
        padding-top: 27%;
    }
    .banner .descript{
        width: 56%;
        background: rgb(24, 31, 41);
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        padding: 210px 100px;
        gap: 50px;
    }
}

@media (max-width: 1350px) {
    .banner .descript {
        padding: 35px;
    }
    .banner .descript{
        padding: 85px 50px;
    }
}

@media (max-width: 1200px) {
    .banner .descript .img_ div {
        padding-top: 20%;
    }
    .banner .descript .cont p {
        font-size: 23px;
    }
    .banner .links {
        justify-content: space-between;
    }
    .banner .links::before {
        left: 49.6%;
    }
    .links .btn_ {
        padding: 0 25px;
    }
    .links .btn_ a {
        font-size: 16px;
        padding: 11px 15px;
    }
}

@media (max-width: 991px) {
    .banner {
        margin-top: -47px;
    }
    .banner .content .img_ {
        display: flex;
        width: 56%;
    }
    .banner .descript {
        gap: 15px;
        width: 59%;
        padding: 76px 35px 35px;
    }
    .banner .links {
        flex-direction: column;
        gap: 15px;
        align-items: center;
    }
    .links .btn_ {
        padding: 0;
        gap: 8px;
        max-width: 315px;
        width: 100%;
    }
    .banner .links::before {
        display: none;
    }
    .links .btn_ a {
        font-size: 15px;
        padding: 8px 13px;
        max-width: 100%;
    }
    .banner .descript .cont p {
        font-size: 20px;
        line-height: 24px;
    }
    .banner .descript .img_ div {
        padding-top: 37%;
    }
    .banner .descript .cont::before {
        top: -7px;
    }
    .banner .descript {
        gap: 27px;
    }
    .links .btn_ p {
        font-size: 14px;
    }
}

@media (max-width: 767px) {
    .banner .content {
        display: flex;
        flex-direction: column;
    }
    .banner .content .img_ {
        display: flex;
        width: 100%;
    }

    .banner .descript {
        width: 100%;
    }
    .banner .descript .img_ div {
        padding-top: 16%;
    }
    .banner .descript {
        width: 100%;
        padding: 70px;
        gap: 40px;
    }
    .banner .descript .cont::before {
        top: -17px;
    }
    .links .btn_ {
        padding: 0;
        gap: 8px;
        width: 100%;
        max-width: 315px;
        gap: 20px;
    }
    .banner .links {
        flex-direction: column;
        gap: 32px;
    }
    .banner .descript {
        margin-top: -95px;
    }
    .banner {
        margin-top: -242px;
        position: relative;
    }
    .banner .content .img_ {
        display: flex;
        width: 100%;
    }
}

@media (max-width: 580px) {
    .banner {
        margin-top: -180px;
        position: relative;
    }
}

@media (max-width: 425px) {
    .banner .descript {
        padding: 50px 25px;
    }
    .banner .descript .img_ div {
        padding-top: 20%;
    }
    .banner .descript {
        margin-top: -40px;
    }
    .banner{
        margin-top: -122px;
        position: relative;
    }
}

  </style>
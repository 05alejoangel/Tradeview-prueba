<template>
    <div>
      <section class="card">
            <div class="item">
                <img src="images/icon-1.svg" alt="">
                <h2>Ideal for Beginner Clients</h2>
                <p>Increase trading volumes as new traders gain comfort by following successful traders in forex markets and beyond into stocks, options, commodities, and more…</p>
            </div>
            <div class="item">
                <img src="images/icon-3.svg" alt="">
                <h2>Low Barriers to Entry</h2>
                <p>CommuniTraders software is free and clients can start with just a $100 minimum investment.</p>
            </div>
            <div class="item">
                <img src="images/icon-2.svg" alt="">
                <h2>Simple Interface</h2>
                <p>A simple GUI provides needed features and tools but isn’t bogged down by non-core features. This allows clients to get setup quickly and start trading.</p>
            </div>
            <div class="item">
                <img src="images/icon-4.svg" alt="">
                <h2>No Long-Term Commitments</h2>
                <p>Clients can easily signup to start, change signal providers, or stop the service. There is no long-term lockup.</p>
            </div>
            <div class="item">
                <img src="images/icon-5.svg" alt=""> 
                <h2>Funds Safety</h2>
                <p>CommuniTraders benefits from the same strong regulation and banking partners standalone Tradeview clients enjoy along with transparency and negative balance protection.</p>
            </div>
            <div class="item">
                <img src="images/icon-6.svg" alt="">
                <h2>Tradeview Runs CommuniTrader</h2>
                <p>You will experience the Tradeview service you know and love, no gimmicks or hidden fees, excellent live customer support, and your dedicated account manager.  </p>
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
<template>
    <div>
      <section class="card">
            <div class="item">
                <img src="@/assets/images/icon-1.svg" alt="">
                <h2>Ideal for Beginner Clients</h2>
                <p>Increase trading volumes as new traders gain comfort by following successful traders in forex markets and beyond into stocks, options, commodities, and more…</p>
            </div>
            <div class="item">
                <img src="@/assets/images/icon-3.svg" alt="">
                <h2>Low Barriers to Entry</h2>
                <p>CommuniTraders software is free and clients can start with just a $100 minimum investment.</p>
            </div>
            <div class="item">
                <img src="@/assets/images/icon-2.svg" alt="">
                <h2>Simple Interface</h2>
                <p>A simple GUI provides needed features and tools but isn’t bogged down by non-core features. This allows clients to get setup quickly and start trading.</p>
            </div>
            <div class="item">
                <img src="@/assets/images/icon-4.svg" alt="">
                <h2>No Long-Term Commitments</h2>
                <p>Clients can easily signup to start, change signal providers, or stop the service. There is no long-term lockup.</p>
            </div>
            <div class="item">
                <img src="@/assets/images/icon-5.svg" alt=""> 
                <h2>Funds Safety</h2>
                <p>CommuniTraders benefits from the same strong regulation and banking partners standalone Tradeview clients enjoy along with transparency and negative balance protection.</p>
            </div>
            <div class="item">
                <img src="@/assets/images/icon-6.svg" alt="">
                <h2>Tradeview Runs CommuniTrader</h2>
                <p>You will experience the Tradeview service you know and love, no gimmicks or hidden fees, excellent live customer support, and your dedicated account manager.  </p>
            </div> 
        </section>
    </div>
  </template>
  
  <script setup>
  
  </script>
  
  <style scoped>
.card {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 100px;
    gap: 35px;
    background: white;
}

.card .item {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 520px;
    padding: 30px;
    box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 13px 8px;
    height: 260px;
}

.card img {
    width: 50px;
}

.card h2[data-v-faf3b655] {
    font-size: 18px;
    color: rgb(255, 0, 0);
    font-weight: 700;
    margin-bottom: 3px;
}

.card p {
    font-size: 18px;
    color: rgb(50 50 50);
    font-weight: 300;
}

@media (max-width: 1300px) {
    .card .item {
        max-width: 440px;
    }
}

@media (max-width: 1150px) {
    .card .item {
        max-width: 380px;
    }
}

@media (max-width: 991px) {
    .card .item {
        max-width: 100%;
    }
}

@media (max-width: 767px) {
    .card {
        padding: 75px;
    }
    .card .item {
        min-height: 260px;
        height: auto;
    }
}

@media (max-width: 500px) {
    .card {
        padding: 75px 0;
    }
    .card .item {
        max-width: 345px;
    }
}

@media (max-width: 425px) {
    .card {
        padding: 50px 0;
    }
    .card {
        padding: 50px 20px;
    }
}
  </style>
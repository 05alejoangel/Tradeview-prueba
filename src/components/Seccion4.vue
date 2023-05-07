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
    .sec-links {

        padding: 80px;

        background: #181F29;

        display: flex;

        flex-direction: column;

        gap: 50px;
}

.sec-links .title {

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

@media (max-width: 767px) {
    .sec-links {
        padding: 50px 35px;
    }
    .sec-links .links {
        flex-direction: column;
        gap: 25px;
        align-items: center;
    }
    .sec-links .links::before {
        opacity: 0;
    }
    .links .btn_ {
        max-width: 315px;
    }
}

@media (max-width: 500px) {
    .sec-links .title h2 {
        font-size: 28px;
    }
    .sec-links {
        gap: 35px;
    }
}
  </style>
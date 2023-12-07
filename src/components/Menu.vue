<template>
    <div>
      <div class="btn_movil">
          <a class="nav-logo" href="#" >
              <img src="@/assets/images/Logo.svg" alt="">
          </a>
          <button @click="toggleClass" class="btn-toggle"><div></div><div></div><div></div></button>
      </div>
      <div class="back" :class="{ 'my-class': isToggled }"></div>
      <header class="nav-movil" :class="{ 'my-class': isToggled }">
          <nav>
              <div class="links" ref="myElement">
                  <a class="nav-logo" href="#" >
                      <img src="@/assets/images/Logo.svg" alt="">
                  </a>
                  <div class="cont-links cont-move" >
                      <a href="#" >FOREX</a>
                      <a href="#" >STOCKS</a>
                      <a href="#" >FUTURES</a>
                      <a href="#" >TradeGATEHub</a>
                  </div>
              </div>
              <div class="login cont-move" >
                  <ul class="nav-ul">
                      <li class="nav-li">
                          <a href="#" data-toggle="sub-menu" class="nav-link">Log in
                              <img src="@/assets/images/arrow.svg" alt="">
                          </a>
                          <ul class="sub-ul">
                              <li class="nav-li">
                                  <a href="#" class="nav-link">Project 1</a>
                              </li>
                              <li class="nav-li">
                                  <a href="#" class="nav-link">Project 2</a>
                              </li>
                              <li class="nav-li">
                                  <a href="#" class="nav-link">Project 3</a>
                              </li>
                          </ul>
                      </li>
                      <li class="nav-li">
                          <a href="#" class="nav-link">Contact Us</a>
                      </li>
                      <li class="nav-li">
                          <a href="#" data-toggle="sub-menu" class="nav-link">English
                              <img src="@/assets/images/world-icon.svg" alt="">
                              <img src="@/assets/images/arrow.svg" alt="">
                          </a>
                          <ul class="sub-ul">
                              <li class="nav-li">
                              <a href="#" class="nav-link">French</a>
                              </li>
                              <li class="nav-li">
                              <a href="#" class="nav-link">Spanish</a>
                              </li>
                          </ul>
                      </li>
                  </ul>
              </div>
          </nav>
          <nav class="nav-container" >
              <ul class="nav-ul" >
                  <li  class="nav-li">
                      <a href="#" class="nav-link ">Markets</a>
                  </li>
                  <li  class="nav-li">
                      <a href="#" data-toggle="sub-menu" class="nav-link ">Company
                          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="24" height="24" viewBox="0 0 24 24">
                          <path fill="#FFFFFF" d="M8.12 9.29L12 13.17l3.88-3.88a.996.996 0 1 1 1.41 1.41l-4.59 4.59a.996.996 0 0 1-1.41 0L6.7 10.7a.996.996 0 0 1 0-1.41c.39-.38 1.03-.39 1.42 0z"></path>
                          </svg>
                      </a>
                      <ul class="sub-ul">
                          <li class="nav-li">
                              <a href="#" class="nav-link ">Company 1</a>
                          </li>
                          <li class="nav-li">
                              <a href="#" class="nav-link ">Company 2</a>
                          </li>
                          <li class="nav-li">
                              <a href="#" class="nav-link ">Company 3</a>
                          </li>
                      </ul>
                  </li>
                  <li class="nav-li">
                      <a href="#" class="nav-link ">Accounts</a>
                  </li>
                  <li class="nav-li">
                      <a href="#" data-toggle="sub-menu" class="nav-link ">Platforms
                          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="24" height="24" viewBox="0 0 24 24">
                          <path fill="#FFFFFF" d="M8.12 9.29L12 13.17l3.88-3.88a.996.996 0 1 1 1.41 1.41l-4.59 4.59a.996.996 0 0 1-1.41 0L6.7 10.7a.996.996 0 0 1 0-1.41c.39-.38 1.03-.39 1.42 0z"></path>
                          </svg>
                      </a>
                      <ul class="sub-ul">
                          <li class="nav-li">
                          <a href="#" class="nav-link ">Plataforms 1</a>
                          </li>
                          <li class="nav-li">
                          <a href="#" class="nav-link ">Plataforms 2</a>
                          </li>
                          <li class="nav-li">
                          <a href="#" class="nav-link ">Plataforms 3</a>
                          </li>
                      </ul>
                  </li>
                  <li class="nav-li">
                      <a href="#" class="nav-link ">Pricing</a>
                  </li>
                  <li class="nav-li">
                      <a href="#" class="nav-link ">Introducing Brokers</a>
                  </li>
                  <li class="nav-li">
                      <a href="#" class="nav-link ">Education</a>
                  </li>
                  <li class="nav-li">
                      <a href="#" data-toggle="sub-menu" class="nav-link">Support
                          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="24" height="24" viewBox="0 0 24 24">
                          <path fill="#FFFFFF" d="M8.12 9.29L12 13.17l3.88-3.88a.996.996 0 1 1 1.41 1.41l-4.59 4.59a.996.996 0 0 1-1.41 0L6.7 10.7a.996.996 0 0 1 0-1.41c.39-.38 1.03-.39 1.42 0z"></path>
                          </svg>
                      </a>
                      <ul class="sub-ul">
                          <li class="nav-li">
                          <a href="#" class="nav-link">Support 1</a>
                          </li>
                          <li class="nav-li">
                          <a href="#" class="nav-link">Support 2</a>
                          </li>
                          <li class="nav-li">
                          <a href="#" class="nav-link">Support 3</a>
                          </li>
                      </ul>
                  </li>
              </ul>
          </nav>
      </header>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        isToggled: false
      }
    },
    mounted () {
      // window.addEventListener('resize', () => {
      //     if (window.innerWidth > 991) {
      //     const elementoAMover = document.querySelector('.cont-move');
      //     const contenedorOrigen = document.querySelector('.links');
      //     const contenedorDestino = document.querySelector('.nav-container');
      //     contenedorDestino.appendChild(elementoAMover);
      //     }
      // });
    },
    methods: {
      toggleClass () {
        this.isToggled = !this.isToggled;
        // Obtén el cuerpo del documento
        const body = document.body;
  
        // Toggle de la clase 'mi-clase' en el cuerpo
        body.classList.toggle('overflow-body');
      }
    }
  }
  </script>
  
  <style scoped>
  header {
      background: linear-gradient(rgb(24, 31, 41) 0%, rgb(24, 31, 41) 54%, rgba(24, 31, 41, 0) 100%);
      width: 100%;
      display: flex;
      justify-content: center;
      padding: 30px 50px 57px;
      flex-direction: column;
      gap: 25px;
      z-index: 1000;
      position: fixed;
      top: 0;
  }
  
  nav:nth-child(1) {
      display: flex;
      justify-content: space-between;
      align-items: center;
  }
  
  .links {
      display: flex;
      align-items: center;
      justify-content: space-between;
      width: 100%;
      gap: 50px;
      max-width: 59%;
  }
  
  .btn-toggle {
      display: none;
  }
  
  .cont-links {
      display: flex;
      gap: 50px;
      font-size: 16px;
      letter-spacing: 2px;
  }
  
  .cont-links a {
      color: white;
      font-weight: 700;
      letter-spacing: 5px;
      transition: color 0.5s;
      font-size: 16px;
  }
  
  .cont-links a:last-child {
      letter-spacing: 2px;
  }
  
  .cont-links a:hover {
      color: red;
  }
  
  .login {
      display: flex;
      padding-right: 85px;
  }
  
  .login .nav-ul {
      gap: 35px;
      position: relative;
  }
  
  .login .nav-ul a {
      font-weight: 100;
      font-size: 16px;
      position: relative;
      letter-spacing: 0.3px;
  }
  
  .login .nav-ul li:nth-child(1) a {
      font-weight: 300;
  }
  
  .login .nav-ul li:nth-child(3) a {
      margin-left: 5px;
  }
  
  .login .nav-ul li:first-child a::before {
      content: "";
      width: 1px;
      height: 21px;
      background: white;
      position: absolute;
      right: -20px;
      opacity: 0.5;
  }
  
  
  .login .nav-ul li:last-child a img:first-child {
      width: 16px;
  }
  
  .nav-container {
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: space-between;
  }
  
  .nav-logo {
      display: inline-flex;
      align-items: center;
  }
  
  .nav-logo svg {
      width: 60px;
      height: 60px;
      padding: 10px;
  }
  
  .nav-logo img {
      max-width: 365px;
  }
  
  .logo-text {
      color: rgb(255, 255, 255);
      font-size: 2rem;
      font-weight: 600;
  }
  
  .hamberger-btn {
      cursor: pointer;
      background-color: rgb(52, 70, 93);
      border-radius: 5px;
      width: 40px;
      height: 40px;
      margin: 10px;
      text-align: center;
      vertical-align: middle;
      transition: all 0.3s linear 0s;
  }
  
  .hamberger-btn svg {
      transition: all 0.3s linear 0s;
      margin: 2px 0px;
      width: 90%;
      height: 90%;
  }
  
  .hamberger-btn svg.rotate {
      transform: rotateY(180deg);
  }
  
  .hamberger-btn:hover {
      box-shadow: rgb(255, 255, 255) 0px 0px 10px;
  }
  
  .hamberger-btn:hover > svg {
      animation: 0.3s ease 0s 1 normal forwards running hambergerBtnRotate;
  }
  
  .nav-ul {
      display: flex;
      align-items: center;
      width: 100%;
      max-width: 1305px;
      justify-content: space-between;
  }
  
  .nav-li {
      height: 100%;
  }
  
  .nav-link {
      padding: 22px 0;
      font-size: 18px;
  }
  
  .nav-link, .nav-link svg {
      color: rgb(255, 255, 255);
      font-weight: 300;
      transition: all 0.3s ease-in-out 0s;
      display: flex;
      align-items: center;
      gap: 2px;
      font-size: 18px;
      letter-spacing: 0.3px;
  }
  
  .nav-link:hover {
      color: white;
  }
  
  .nav-link svg {
      height: 18.2px;
      vertical-align: middle;
  }
  
  .nav-link img {
      width: 6px;
      margin-left: 7px;
  }
  
  .sub-ul {
      opacity: 0;
      visibility: hidden;
      transform: translateY(10px);
      transition: all 0.3s linear 0s;
      position: absolute;
      top: 100%;
      background-color: rgb(40, 50, 60);
      width: 100%;
      max-width: 150px;
  }
  
  .sub-ul .nav-li a {
      display: block;
      padding: 15px 30px;
      transition: all 0.7s ease 0s;
  }
  
  .sub-ul .nav-li a::before {
      display: none;
  }
  
  .sub-ul .nav-li a:hover {
      background-color: rgb(52, 70, 93);
  }
  
  .back {
      display: none;
  }
  
  
  
  
  
  @media (min-width: 992px) {
      .login .nav-li:hover > .sub-ul {
          transform: translateY(0px);
      }
      .nav-li:hover > .sub-ul {
          opacity: 1;
          visibility: visible;
          transform: translateY(-58px);
      }
  
      .nav-li:hover > .nav-link {
          color: white;
      }
      .nav-li:hover > .nav-link svg {
          transform: rotate(180deg);
      }
      .nav-link:hover > svg {
          color: rgb(236, 195, 11);
          transform: rotate(180deg);
      }
  }
  
  @media (max-width: 1500px) {
      header[data-v-e065371e] {
          gap: 30px;
      }
      .login {
          padding-right: 0;
      }
  
      .nav-logo img {
          max-width: 309px;
      }
      .links {
          gap: 30px;
      }
      .cont-links {
          gap: 20px;
      }
  }
  
  @media (max-width: 1350px) {
      header {
          padding: 15px 30px 57px;
      }
      .nav-link, .nav-link svg {
          font-size: 16px;
          padding: 0px 0;
      }
      .cont-links a {
          font-size: 16px;
      }
      .nav-logo img {
          max-width: 250px;
      }
  }
  
  @media (max-width: 1150px) {
      .cont-links {
          display: flex;
          gap: 15px;
      }
      .login .nav-ul {
          gap: 20px;
      }
      .login .nav-ul li:first-child a::before {
          right: -10px;
      }
      .cont-links a {
          font-size: 16px;
          letter-spacing: 1px;
      }
      .links {
          gap: 25px;
      }
  }
  
  @media (max-width: 991px) {
      .nav-movil {
          background: rgb(24, 31, 41);
          gap: 40px;
          display: flex;
          position: fixed;
          top: 0;
          bottom: 0;
          justify-content: flex-start;
          padding: 46px;
          right: 0;
          max-width: 320px;
          width: 100%;
          transform: translateX(250%);
          transition: transform 0.5s;
          overflow-y: auto;
          flex-direction: column;
          overflow-y: scroll;
      }
      header.my-class {
          transform: translateX(0%);
      }
      .back {
          position: fixed;
          top: 0;
          right: 0;
          width: 100%;
          height: 100%;
          background: #00000087;
          display: flex;
          transform: translateX(250%);
          transition: transform 0.5s;
      }
      .back.my-class {
          transform: translateX(0%);
      }
      .login .nav-ul li:first-child a[data-v-e065371e]::before {
          display: none;
      }
      .nav-ul, .login .nav-ul, .cont-links {
          flex-direction: column;
          gap: 15px;
          align-items: flex-start;
          width: 100%;
      }
      .login {
          width: 100%;
      }
      .btn-toggle {
          display: block;
          font-size: 0;
          z-index: 1;
      }
  
      .links {
          width: 100%;
      }
  
      .btn_movil[data-v-e065371e] {
          display: flex;
          justify-content: space-between;
          align-items: center;
          background: linear-gradient(rgb(24,31,41) 0%,rgb(24,31,41) 46%,rgba(24,31,41,0) 100%);
          padding: 15px 35px 35px;
      }
  
      .btn-toggle {
          font-size: 0;
          background: transparent;
          border: none;
          display: flex;
          flex-direction: column;
          gap: 5px;
          position: absolute;
          right: 35px;
          z-index: 10000;
      }
  
      .btn-toggle div {
          display: flex;
          width: 25px;
          height: 2px;
          background: white;
      }
  
      .sub-ul {
          opacity: 0;
          visibility: hidden;
          transform: translateY(10px);
          transition: all 0.3s linear 0s;
          position: relative;
          top: 0;
          background-color: rgb(40, 50, 60);
          width: 100%;
          max-width: 100%;
          transform: translateY(0px);
          height: 0;
          margin-top: 0;
      }
      .sub-ul .nav-li a {
          padding: 10px 18px;
      }
  
      .nav-li a:focus ~ .sub-ul {
          margin-top: 10px;
          opacity: 1;
          visibility: visible;
          transform: translateY(0px);
          height: fit-content;
      }
  
      .nav-li {
          height: auto;
          width: 100%;
      }
      .links {
          gap: 25px;
          width: 100%;
      }
      header .nav-logo {
          display: none;
      }
      nav {
          gap: 35px;
          flex-direction: column-reverse;
      }
      .nav-container {
          justify-content: flex-end;
      }
      .links  {
          display: flex;
          align-items: center;
          justify-content: space-between;
          width: 100%;
          gap: 50px;
          max-width: 100%;
      }
  }
  @media (max-width: 425px){
          .nav-logo img {
              max-width: 204px;
          }
          .btn_movil   {
              padding: 25px 22px 35px;
          }
      }
  </style>
  
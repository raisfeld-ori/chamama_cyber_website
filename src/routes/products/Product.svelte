<script>
  export let name = "";
  export let url;
  export let text = "";
  export let image;
   
  export let name2 = "";
  export let url2;
  export let text2 = "";
  export let image2;

  export let name3 = "";
  export let url3;
  export let text3 = "";
  export let image3;



 </script>
 
 <a href={url}>
  <div class="div2 grid-layout">
     <img class="image" src={image} alt=""/>
     <div>
         <h2 class="texthead2"><span>{name}</span></h2>
         <p class="text"><span>{text}</span></p>
     </div>
  </div>
 </a>
 
 <a href={url2}>
  <div class="div2 grid-layout">
     <img class="image" src={image2} alt=""/>
     <div>
         <h2 class="texthead2"><span>{name2}</span></h2>
         <p class="text"><span>{text2}</span></p>
     </div>
  </div>
 </a>

 <a href={url3}>
  <div class="div2 grid-layout">
     <img class="image2" src={image3} alt=""/>
     <div>
         <h2 class="texthead2"><span>{name3}</span></h2>
         <p class="text"><span>{text3}</span></p>
     </div>
  </div>
 </a>


 <style>
  :root{--scroll: scroll;}
 
  .text {
     position: static;
     display: inline-block;
     color: rgb(0, 162, 255);
     margin: 0;
     padding-left: 10px;
     padding-right: 20px;
     font-size: 0.7em;
     user-select: text;
     margin-top: 2svh;
     white-space: pre-wrap;
     transform: scale(0.94);
  animation: scale 3s forwards cubic-bezier(0.5, 1, 0.89, 1);
  }
  @keyframes scale {
    100% {
      transform: scale(1);
    }
  }

  span {
    display: inline-block;
    opacity: 0;
    filter: blur(4px);
  }

  span:nth-child(1) {
    animation: fade-in 0.8s 0.1s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(2) {
    animation: fade-in 0.8s 0.2s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(3) {
    animation: fade-in 0.8s 0.3s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(4) {
    animation: fade-in 0.8s 0.4s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(5) {
    animation: fade-in 0.8s 0.5s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(6) {
    animation: fade-in 0.8s 0.6s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(7) {
    animation: fade-in 0.8s 0.7s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(8) {
    animation: fade-in 0.8s 0.8s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(9) {
    animation: fade-in 0.8s 0.9s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(10) {
    animation: fade-in 0.8s 1s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(11) {
    animation: fade-in 0.8s 1.1s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(12) {
    animation: fade-in 0.8s 1.2s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(13) {
    animation: fade-in 0.8s 1.3s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(14) {
    animation: fade-in 0.8s 1.4s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(15) {
    animation: fade-in 0.8s 1.5s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(16) {
    animation: fade-in 0.8s 1.6s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(17) {
    animation: fade-in 0.8s 1.7s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  span:nth-child(18) {
    animation: fade-in 0.8s 1.8s forwards cubic-bezier(0.11, 0, 0.5, 0);
  }

  @keyframes fade-in {
    100% {
      opacity: 1;
      filter: blur(0);
    }
  }
    

  .texthead2{
       position: static;
       color: rgb(0, 123, 223);
       clear: both;
       font-size: 1.2em;
       display: block;
       margin: auto;
       transform: scale(0.94);
       animation: scale 3s forwards cubic-bezier(0.5, 1, 0.89, 1);
  }
  @keyframes scale {
    100% {
      transform: scale(1);
    }
  }
  
  .image {
     position: static;
     width: calc(22vh + 25svw + 0px);
     border-radius: 10%;
     margin-left: 1vw;  
     transform: scale(0.80);
    animation: scale 3s forwards cubic-bezier(0.5, 1, 0.89, 1);
  }
  @keyframes scale {
    100% {
      transform: scale(1);
    }
  }
  
 
  .grid-layout {
     display: grid;
     grid-template-columns: 1fr 1fr;
  }
 
  @media screen and (max-width: 600px) {
     .grid-layout {
       grid-template-columns: 1fr;
     }
     .image {
      margin-left: 12svw;
     }
     .image2 {
      margin-left: 12svw;
     }
     .text{
      font-size: 0.8em;
     }
     :root{--scroll: scroll;}
  }
  
  .image2 {
    position: static;
     width: calc(19vh + 25svw + 0px);
     border-radius: 10%;
     margin-left: 1vw; 
  }
 </style>
<script>
    import Product from './Product.svelte';
    import ai from '$lib/images/ai.png';
    import compiler from '$lib/images/wierdcompiler.png';
    import calculator from '$lib/images/calculator.png';

    import { onMount } from 'svelte';


    let scroll_allowed = false;
    onMount(() => {
      scroll_allowed = true;
    })
    
</script>
<svelte:head>
	<title>עמוד תוצרים</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
</svelte:head>

<h1 class="texthead">תוצרים של מגמת ההייטק</h1>
<div>
<Product name="raisfeld encrypter"/>
<Product image={compiler} text="raisfeld encrypter is a free, open source app for encrypting any file, of any size, into your computer. it uses AES (advanced encryption standard) to encrypt the files into a hidden place in your computer."/>
</div>
<div>
    <a href="https://raisfeld.netlify.app">
<button class="button-77">..עוד מידע</button>
</a>
</div>

<div>
<Product name2="AI Model (Hackathon)"/>
<Product image2={ai} text2="מודל בינה מלכויתית שנוצר במהלך יום לימודים מיוחד בבית ספר של 24 שעות כדי לתמוך באנשים מפונים לאחר שעזבו את ביתם בגלל ה7 באוקטובר"/>
</div>
<div style="padding-top: 4svh;">
  <a href="https://www.chamama.org/newsletter">
    <button class="button-77">...עוד מידע</button>
    </a>
    </div>
<div>
<Product name="raisfeld encrypter"/>
<Product image={compiler} text="raisfeld encrypter is a free, open source app for encrypting any file, of any size, into your computer. it uses AES (advanced encryption standard) to encrypt the files into a hidden place in your computer."/>
</div>
<div>
    <a href="https://raisfeld.netlify.app">
<button class="button-77">..עוד מידע</button>
</a>
</div>

<div>
<Product name="Calculator Ariel.Cal"/>
<Product image={calculator} text=" מחשבון בסיסי שנוצר בעזרת השפת תכנות פייתון כדי למדוד את היכולות של התלמיד בשפת התכנות ולצבור ניסיון הכנת אפליקציות"/>
</div>
<div>
    <a href="d">
<button class="button-77">..עוד מידע</button>
</a>
</div>

<div>
  <a href="https://www.chamama.org/newsletter">
  <p class="textinfo">לעוד מידע על פרוייקטים שעושים בבית הספר נא ללחוץ כאן</p>
</a>
</div>

{#if scroll_allowed}
  <style>:root{--scroll: visible;}</style>
{/if}
<style>

.texthead {
  position: relative;
  font-size: 2em;
  letter-spacing: 4px;
  overflow: hidden;
  background: linear-gradient(90deg, #0556ed, #009dff, #0062ff);
  background-repeat: no-repeat;
  background-size: 80%;
  animation: animate 5s linear infinite;
  -webkit-background-clip: text;
  background-clip: text;  -webkit-text-fill-color: rgba(255, 255, 255, 0);
}

@keyframes animate {
  0% {
    background-position: -500%;
  }
  100% {
    background-position: 500%;
  }
}

    .button-77 {
        align-items: center;
        appearance: none;
        background-clip: padding-box;
        background-color: initial;
        background-image: none;
        border-style: none;
        box-sizing: border-box;
        color: #fff;
        cursor: pointer;
        display: inline-block;
        flex-direction: row;
        flex-shrink: 0;
        font-family: Eina01,sans-serif;
        font-size: 16px;
        font-weight: 800;
        justify-content: center;
        line-height: 24px;
        margin: 0;
        min-height: 64px;
        outline: none;
        overflow: visible;
        padding: 19px 26px;
        pointer-events: auto;
        position: relative;
        text-align: center;
        text-decoration: none;
        text-transform: none;
        user-select: none;
        -webkit-user-select: none;
        touch-action: manipulation;
        vertical-align: middle;
        width: auto;
        word-break: keep-all;
        z-index: 0;
}

@media (min-width: 1098px   ) {
  .button-77 {padding: 19px 52px;}
  .texthead{margin-top: 0;padding-top: 0;}
}

.button-77:before,
.button-77:after {
  border-radius: 30px;
}

.button-77:before {
  background-color: rgba(19, 111, 249, 0.32);
  content: "";
  display: block;
  height: 100%;
  left: 0;
  position: absolute;
  top: 0;
  width: 100%;
  z-index: -2;
}

.button-77:after {
  background-color: initial;
  background-image: linear-gradient(92.83deg, #26a8ff 0, #137ef9 100%);
  bottom: 4px;
  content: "";
  display: block;
  left: 4px;
  position: absolute;
  right: 4px;
  top: 4px;
  transition: all 100ms ease-out;
  z-index: -1;
}

.button-77:hover:not(:disabled):after {
  bottom: 0;
  left: 0;
  right: 0;
  top: 0;
  transition-timing-function: ease-in;
}

.button-77:active:not(:disabled) {
  color: #ccc;
}

.button-77:active:not(:disabled):after {
  background-image: linear-gradient(0deg, rgba(0, 0, 0, .2), rgba(0, 0, 0, .2)), linear-gradient(92.83deg, #ff7426 0, #f93a13 100%);
  bottom: 4px;
  left: 4px;
  right: 4px;
  top: 4px;
}

.button-77:disabled {
  cursor: default;
  opacity: .24;
}

.textinfo {
     position: static;
     display: inline-block;
     color: rgb(0, 162, 255);
     margin: 0;
     padding-left: 10px;
     padding-right: 20px;
     font-size: 0.7em;
     user-select: text;
     margin-top: 5svh;
     margin-bottom: 2svh;
     white-space: pre-wrap;}

     .textinfo:hover {
      color: #0062ff;
      text-decoration: underline;
      scale: 1.052;
     }
</style>

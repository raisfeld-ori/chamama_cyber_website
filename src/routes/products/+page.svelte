<script>
    import Product from './Product.svelte';
    import ai from '$lib/images/ai.png';
    import compiler from '$lib/images/wierdcompiler.png';
</script>

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
<Product name2="AI Model (Hakaton)"/>
<Product image2={ai} text2="AI Model made for the [example] association in the purpose of supporting their association website."/>
</div>
<div style="padding-top: 4svh;">
    <button class="button-77">Not Defined</button>
    </div>

    <h1 class="texthead">.עוד מידע</h1>

<style>
  :root{--scroll: scroll;}



.texthead{
   position: static;
   color: rgb(0, 123, 223);
   margin-top: 10svh;
   padding-top: 1svh;
   clear: both;
   font-size: 1.6em;
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
</style>

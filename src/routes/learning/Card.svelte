<script>
    export let image = [];
    export let text = [];
    export let header = [];
    let current = 0;
    let final = false;
    let start = true;

    function update(){
      if (current == 0){start = true;} else {start = false;}
      if (current == text.length - 1) {final = true;} else {final = false;}
    }
    function next(){if (current < text.length - 1){current += 1;update();}}
    function previous(){if (current > 0){current -= 1;update();}}
    
</script>


<div class="card">
    <p class="texthead">{header[current]}</p>
    <img class="image" src={image[current]} alt="projects">
    <p class="text">{text[current]}</p>
</div>


<div class="button-container">
    <button on:click={next} style={final ? 'display: none;' : ''} class="button-77">המשך</button>
    <button on:click={previous} style={start ? 'display: none;' : ''} class="button-77">חזרה</button>
</div>
<style>
  :root{--scroll: scroll;}
.text {
   position: static;
   display: inline-block;
   color: rgb(0, 162, 255);
   margin: 0;
   padding-left: 10px;
   font-size: 0.7em;
   user-select: text;
   margin-top: 2svh;
   white-space: pre-wrap;
}
.texthead{
   position: static;
   color: rgb(0, 123, 223);
   margin-top: 10svh;
   padding-top: 1svh;
   clear: both;
}
.image {
   position: static;
   width: calc(20vh + 20svw + 10px);
   border-radius: 10%;
   margin-left: 4svw;
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

@media (min-width: 778px) {
  .button-77 {padding: 19px 52px;}
  .image{float:left;}
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
  overflow: hidden;
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
  overflow: hidden;
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
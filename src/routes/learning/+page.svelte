<script>
    import projects from '$lib/images/projects.jpg';``




  </script>
  
  <div class="test">
    <img class="image" src={projects} alt="projects">
    <p class="texthead">?איך אנחנו לומדים</p>
    <p class="text">בית ספר החממה זה בית ספר ללמידה אישית</p><br>
    <p class="text">לכן במגמה שלנו אנחנו נעזרים בקורסים אונליין ומנטורים כדי ללמוד</p><br>
    <p class="text">על מנת להתקדם בלמידה שאנחנו התלמדים רוצים להתקדם בה</p><br>
    <p class="text">כול תלמדים במגמה בוחר לבד מה הם רוצים ללמוד</p><br>
    <p class="text">!אם זה בניית אתרים, סייבר, הכנת משחקים ועוד</p><br>
    <p class="text">כול חודש/חודשיים אנחנו מציגים פרוייקט שמראה מה למדנו בתקופה</p><br>
    <p class="text">בעזרת החומר שאנחנו לומדים כול תקופה אנחנו מציגים את היכולות שלנו</p><br>
    <p class="text2">!רוצים לשמוע עוד? לחצו על הפתור למטה</p><br>
  </div>

  <div class="button-container">
    <a href="https://www.chamama.org/why-how-what" class="button-77">!לחץ כאן</a>
   </div>
  
  <style>
  .text{
   color: rgb(0, 162, 255);
   margin: 0; 
   padding-left: 20px; /* Adjust as needed */
   font-size: 0.6em; /* Adjust as needed */
   line-height: 0.3em;

  }
  .texthead{
    color: rgb(0, 123, 223);
    margin-top: 10svh;
    padding-top: 1svh;
  }
  .image {
    float: left;
    width: 50%;
    border-radius: 10%;
    height: auto;
    margin-left: 4svh;
    
  }
  .text2{
    color: rgb(0, 134, 223);
    margin: 0; 
    padding-left: 20px; /* Adjust as needed */
    font-size: 0.8em; /* Adjust as needed */
    line-height: 0.3em;
  }
  .button-container {
    display: flex;
    justify-content: center;
    align-items: center;
    
  }


/* CSS */
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

@media (min-width: 768px) {
  .button-77 {
    padding: 19px 52px;
  }
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
.test {
}
  </style>
  
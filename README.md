# calc
<input id="num1"/>
  <p>+</p>
   <input id="num2"/>
  <button onclick="func()">дорівнює...</button>

 <p id="result"></p>

 <script>
    function func(){
     var num1 = Number(document.getElementById("num1").value);
    var num2 = Number(document.getElementById("num2").value);
   var result = num1 + num2;
        
     document.getElementById("result").innerHTML = result;
          }
          </script>

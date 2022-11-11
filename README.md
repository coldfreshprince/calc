<input id="num1"/>

<div id="operator_btns">
  <button id="plus" class="operator">+</button>
  <button id="minus" class="operator">-</button>
  <button id="times" class="operator">x</button>
  <button id="divide" class="operator">:</button>
</div>

<input id="num2"/>

<button onclick="func()">равняется...</button>

<p id="result"></p>


<script>
  function func(){
    var num1 = Number(document.getElementById("num1").value);
    var num2 = Number(document.getElementById("num2").value);
    result = ???

    document.getElementById("result").innerHTML = result;
    }
</script>

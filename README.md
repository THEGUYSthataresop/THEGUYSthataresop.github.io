# ImmuneLion318 quote generator

<button onclick="generate()">Ggenerate</button>

<p id="quote"></p>

<script>
  function generate(){
    array = ["A","B","C","D","E","F"]
    var chosen = array[Math.floor(Math.random()*array.length)];
  
    document.getElementById("quote").innerHTML = chosen
  }
</script>

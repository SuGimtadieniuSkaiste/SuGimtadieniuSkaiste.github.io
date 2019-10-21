Input validator

<input id="zodis" oninput="onInput()">
<p id="rezultatas"></p>

<script>
function onInput() {
  var x, text;
  x = document.getElementById("zodis").value;

  if (x == 'Maksas') {
    document.getElementById("rezultatas").innerHTML = "<form " +
      "action=\"https://sugimtadieniuskaiste.github.io/0/15284.html\"> "+
      "<input type=\"submit\" " +
        "value=\"Kitas\" /> " +
      "</form>";
  }
}
</script>

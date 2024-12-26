---
{"dg-publish":true,"permalink":"/test/","noteIcon":"","created":"2024-12-26T14:46:37.548+00:00","updated":"2024-12-26T15:12:04.816+00:00"}
---


<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>W3.CSS</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>

<div class="w3-container">
  <h2>Active Tabs</h2>
  <p>To highlight the current tab/page the user is on, add a color class, and use JavaScript to update the active link.</p>

  <div class="w3-bar w3-black">
    <button class="w3-bar-item w3-button tablink w3-red" onclick="openCity(event,'Purpose & Use')">Purpose & Use</button>
    <button class="w3-bar-item w3-button tablink" onclick="openCity(event,'Useful Tip - Daggers')">Useful Tip - Daggers</button>
    <button class="w3-bar-item w3-button tablink" onclick="openCity(event,'Problems')">Problems</button>
  </div>
  
  <div id="Purpose & Use" class="w3-container w3-border city">
    <h3>Purpose & Use</h3>
    <p>This is a read-only version of the Ashen Campaign Vault, designed to make it easier to find, read, and share campaign information without having to set up Obsidian. Although not built for theorising, you can find a list of our current **[[Other Information/Theories & Unanswered Questions\|THEORIES & UNANSWERED QUESTIONS HERE]]**.</p>
  </div>

  <div id="Useful Tip - Daggers" class="w3-container w3-border city" style="display:none">
    <h3>Useful Tip - Daggers</h3>
    <p>† denotes that this character is dead.<br><br>‡ denotes that the circumstances around this character's death are strange or unusual.<br><br>We have made a point of never officially putting daggers on people unless we are outright told by James or in an official text.</p>
    </div>

  <div id="Problems" class="w3-container w3-border city" style="display:none">
    <h3>Problems</h3>
    <p> DM [[The Party/Other Party Members/Meta/Sam Gallon\|Sam Gallon]] if there are any problems.<br><br>As always, you should talk to [[The Party/Other Party Members/Meta/James Absolom\|James Absolom]] if you have any ideas or thoughts relating to the campaign.<br><br>**NEVER** keep secrets from the DM this is a collaborative storytelling game, and it only works well if the storyteller knows what's happening. Who knows, they might even be able to make it happen better than you expected.</p>
  </div>
</div>
<script>
function openCity(evt, cityName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("city");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-red", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " w3-red";
}
</script>
</body>
</html>


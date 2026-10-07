Hi, I'm Amit. 

[aprakash2@imsa.edu](mailto:aprakash2@imsa.edu)

<div align="center">
  <div id="haa-gate">
    <strong>Protected section</strong><br />
    <label for="haa-password">Password:</label>
    <input id="haa-password" type="password" style="font: inherit;" />
    <button onclick="unlockHAA()" style="font: inherit;">Enter</button>
    <p id="haa-error" style="display:none;">Incorrect password.</p>
  </div>
  <div id="haa-content" style="display:none;">
    <a href="/horowitz-andreesen-related-topics">Horowitz-Andreesen related topics here</a>
  </div>
</div>

<script>
  function unlockHAA() {
    const value = document.getElementById("haa-password").value;
    if (value === "$HAAREVIEWER$") {
      document.getElementById("haa-gate").style.display = "none";
      document.getElementById("haa-content").style.display = "block";
      document.getElementById("haa-error").style.display = "none";
    } else {
      document.getElementById("haa-error").style.display = "block";
    }
  }
</script>


> “Don't watch the mouth, watch the hands.”

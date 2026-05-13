# Photographic-Memory-Kingston-1
<input id="answer">
button onclick="check()">Submit</button>

<script>
function check() {
const correct = "SHADOW";
if (document.getElementByID("answer").value.toUppercase() === correct) {
alert("Correct! Next Clue: ...");
} else {
alert("Try again.");
}
}
</script>
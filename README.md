# rivalz_v2
</pre>

<button onclick="copyToClipboard()">Copy to Clipboard</button>

<script>
function copyToClipboard() {
  // Get the text from the code snippet
  var text = document.getElementById('codeSnippet').innerText;

  // Create a temporary text area to copy from
  var tempTextArea = document.createElement("textarea");
  tempTextArea.value = text;
  document.body.appendChild(tempTextArea);

  // Select the text and copy it to clipboard
  tempTextArea.select();
  document.execCommand("copy");

  // Remove the temporary text area
  document.body.removeChild(tempTextArea);

  // Alert user that the text has been copied
  alert("Code copied to clipboard!");
}
</script>

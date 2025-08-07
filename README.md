BitCapCha, is a CAPCHA i made when i was bored with ChatGPT,
I use it for some of my projects and today i decided to make it public.
BitCapCha is a privacy respecting CAPCHA unlike ReCapcha with minimal tracking as 
possible. and has minimal code if you want to add it use this 
html code: "<iframe 
  src="https://abdullahhmoodlol.github.io/BitCapCha/" 
  width="320" 
  height="100" 
  style="border: none;" 
  sandbox="allow-scripts"
></iframe>" i doubt anybody will but ok. and for listening to verification use this js code: "<script>
  window.addEventListener("message", function(event) {

if (event.origin !== "https://abdullahhmoodlol.github.io/BitCapCha/") return;

  if (event.data && event.data.bitcapcha === true) {
      console.log("✅ BitCapCha passed!");
      // Example: Enable form submit
      document.querySelector("#submitButton").disabled = false;
    }
  });
</script>"

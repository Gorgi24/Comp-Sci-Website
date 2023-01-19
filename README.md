# Comp-Sci-Website
Website about my Computer Science Portfolio
<!DOCTYPE html>
<!-- saved from url=(0042)file:///H:/Chrome%20Downloads/index-1.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <title>Georgi's Website</title>
  </head>
  <body bgcolor="#2c4e31">
      <a href="intex.html">Home</a>
    <a href="portfolio.html">Portfolio</a>
    <a href="aboutme.html">About Me</a>
    <h1>This is Georgi Andreev's Home Page!</h1>
    <script>
var x = document.getElementById("demo");
function getLocation() {
  if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(showPosition);
  } else {
    x.innerHTML = "Geolocation is not supported by this browser.";
  }
}

function showPosition(position) {
  x.innerHTML = "Latitude: " + position.coords.latitude +
  "<br>Longitude: " + position.coords.longitude;
}
</script>
  

</body></html>

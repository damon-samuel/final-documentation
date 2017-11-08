<html>
<head>
<meta charset="UTF-8">
<title>jQuery Mobile Web App</title>
<meta name="viewport" content="width=device-width,initial-scale=1" />
<link rel="stylesheet" href="themes/colorama1.min.css" />
	<link rel="stylesheet" href="themes/jquery.mobile.icons.min.css" />
	<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile.structure-1.4.5.min.css" />
	<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
	<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
<script>
$(document).ready(function(){
    $("button").click(function(){
        $("#div1").fadeIn();
        $("#div2").fadeIn("slow");
        $("#div3").fadeIn(3000);
    });
});
</script>

</head>
<body>
<div data-role="panel" id="myPanel">
<h2>Panel Header</h2>
<ul data-role="listview" data-theme="b">
  <li><a href="#cars">Favorite Cars</a></li>
  <li><a href="#NBA player">NBA Player</a></li>
  <li><a href="#Movie">Movie</a></li>
  <li><a href="#Foods">Foods</a></li>
  <li><a href="#Gaming System">Gaming System</a></li>
  <li><a href="#Cereal">Cereal</a></li>
</ul>
<p>You can close this panel by clicking outside of it, pressing the Esc key, or by swiping.</p>
</div>
<div id="page" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="b">
	  <div class="logo"><img src="http://s3-us-west-1.amazonaws.com/westcoastcustoms-www/gallery/delor-i-am/IMG_1348.jpg" width="300" height="75" alt=""/></div>
  </div>

  <div data-role="header">
    <h1>Foot's Favorite Things</h1>
    <a href="#myPanel" class="ui-btn ui-btn-inline">Open Panel</a><a href="#myPanel" class="ui-btn ui-btn-inline">Open Panel</a>
  </div>

  <div data-role="content">
    <ul data-role="listview" data-theme="c" data-filter="true">
      <a href="#" class="ui-btn ui-shadow ui-corner-all ui-icon-check ui-btn-icon-notext ui-btn-inline">Check</a>
      <div class="ui-nodisc-icon ui-alt-icon"><!-- Classes added to the wrapper -->
      <li><a href="#grid">Grid</a></li>
      <li><a href="#form">Form</a><li>
</div>
		</ul>
  </div>
    <div data-role="footer" data-theme="b">
      <h4>damonsamuel@sotd.us &copy; 2017</h4>
    </div>
</div>
<div id="cars" data-role="page" data-theme="c" data-add-back-btn="true">
	<div data-role="header" data-theme="d" data-add-back-btn="true">
	  <h1>Favorite Cars</h1>
	</div>
	<div data-role="content">
	  <h3>Fun Facts of the Delorean</h3>
	  <p> Without a doubt, one of Back to the Future's unsung heroes is the DeLorean time machine. Built over the course of nearly thirty years and using his entire family fortune in order to fulfill his vision of the "Flux Capacitor", Doc Brown selected the DeLorean DMC-12 as his vehicle of choice for traveling through time.</p>

		<p>Read more at http://www.backtothefuture.com/delorean#iWBfIj3me3dgIF1v.99 </p>
	</div>
	<div data-role="footer" data-theme="d">
	  <h4>damonsamuel@sotd.us &copy; 2017</h4>
	</div>
</div>
<div id="NBA player" data-role="page" data-theme="a" data-add-back-btn="true">
	<div data-role="header" data-theme="a" data-add-back-btn="true">
		<h1>NBA Player</h1>
	</div>
	<div data-role="content">
	  <h3>LeBron James</h3>
	  <p> The G.O.A.T. Don't @ me </p>
	</div>
	<div data-role="footer" data-theme="a">
		<h4>damonsamuel@sotd.us &copy; 2017</h4>
	</div>
</div>
<div id="Movie" data-role="page" data-theme="a" data-add-back-btn="true">
	<div data-role="header" data-theme="a" data-add-back-btn="true">
		<h1>Movie</h1>
	</div>
	<div data-role="content">
	  <h3>Four Brothers</h3>
	  <p> A movie about Four adopted brothers who stop at nothing to figure out who killed their mother. </p>
	<div data-role="footer" data-theme="a" >
	  <h4>damonsamuel@sotd.us &copy; 2017</h4>
	</div>
</div>
</div>

<div id="Foods" data-role="page" data-theme="c" data-add-back-btn="true">
	<div data-role="header" data-theme="d" data-add-back-btn="true">
		<h1>Foods</h1>
	</div>
  <div data-role="content">
	  <h3>Pizza</h3>
		<p>Prefer Dominoes. </p>
	  <h3>Tacos</h3>
		<p> Mi Tierra is delicious!</p>
	<div data-role="footer" data-theme="c">
		<h4>damonsamuel@sotd.us &copy; 2017</h4>
	</div>
	</div>
</div>

<div id="Gaming System" data-role="page" data-theme="c" data-add-back-btn="true">
	<div data-role="header" data-theme="d" data-add-back-btn="true">
		<h1>Gaming System</h1>
	</div>
  <div data-role="content">
	  <h3>Xbox One</h3>
	  <p> The Xbox One has great graphics and multiplayer online capabilities. </p>
		<fieldset data-role="controlgroup">
    <legend>Select your favorite:</legend>
        <input type="radio" name="radio-choice-1" id="radio-choice-1" value="choice-1" checked="checked">
        <label for="radio-choice-1">Xbox One</label>
        <input type="radio" name="radio-choice-1" id="radio-choice-2" value="choice-2">
        <label for="radio-choice-2">Playstation 4</label>
        <input type="radio" name="radio-choice-1" id="radio-choice-3" value="choice-3">
        <label for="radio-choice-3">Nintendo Switch</label>
        <input type="radio" name="radio-choice-1" id="radio-choice-4" value="choice-4">
        <label for="radio-choice-4">PC</label>
</fieldset>
	<div data-role="footer" data-theme="b">
		<h4>damonsamuel@sotd.us &copy; 2017</h4>
	</div>
</div>
</div>

<div id="Cereal" data-role="page" data-theme="b" data-add-back-btn="true">
  <div data-role="header" data-theme="b" data-add-back-btn="true">
    <h1>Cereal</h1>
	</div>
  <div data-role="content">Content</div>
	<fieldset data-role="controlgroup">
    <legend>Select favorite:</legend>
    <input type="checkbox" name="checkbox-1a" id="checkbox-1a" checked="">
    <label for="checkbox-1a">Cinnamon Toast Crunch</label>
    <input type="checkbox" name="checkbox-2a" id="checkbox-2a">
    <label for="checkbox-2a">Raisin Bran Crunch</label>
    <input type="checkbox" name="checkbox-3a" id="checkbox-3a">
    <label for="checkbox-3a">Fruity Pebbles</label>
    <input type="checkbox" name="checkbox-4a" id="checkbox-4a">
    <label for="checkbox-4a">Frosted Flakes</label>
</fieldset>
<div data-role="footer" data-theme="b">
	<h4>damonsamuel@sotd.us &copy; 2017</h4>
</div>
</div>

<div data-role="page" id="grid" data-theme="c" data-add-back-btn="true">
<div data-role="header" data-theme="c" data-add-back-btn="true">
<h1>Grid</h1>
</div>
<div data-role="content">
<div class="ui-grid-d">
<div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:60px">Cars</div></div>
<div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:60px">Food</div></div>
<div class="ui-block-c"><div class="ui-bar ui-bar-a" style="height:60px">Gaming System</div></div>
<div class="ui-block-d"><div class="ui-bar ui-bar-a" style="height:60px">Cereal</div></div>
<div class="ui-block-e"><div class="ui-bar ui-bar-a" style="height:60px">Movies</div></div>
</div><!-- /grid-d -->

</div>
</div>
</div>

<div data-role="page" id="form" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="b" data-add-back-btn="true">
		<h1>Form</h1>
	</div>
	<div data-role="content">Content</div>
</p>
<ul data-role="listview" data-theme="c" data-filter="true">
  <form action="form.php" method="post">
    <label for="fname">First name:</label>

    <input type="text" name="fname" id="fname" data-clear-btn="true">
    <label for="lname">Last name:</label>
    	<input type="text" name="lname" id="lname" data-clear-btn="true">
    	<label for="state">State:</label>
    	<input type="text" name="state" id="state" data-clear-btn="true">
    	<label for="favorite food">Favorite Food:</label>
    	<input type="text" name="favorite food" id="favorite food" data-clear-btn="true">
    	<label for="favorite movie">Favorite movie:</label>
    	<input type="text" name="favorite movie" id="favorite movie" data-clear-btn="true">
    <input type="reset" value="Reset Button">

    <input type="submit" value="Submit Button">

<textarea class="localstorage" placeholder="This will be saved with localStorage." autofocus></textarea>
<button class="clear">Clear localStorage</button>
<button class="empty">Empty localStorage</button>
</div>
		</form>
	<div data-role="footer"data-theme="c">
		<h4>damonsamuel@sotd.us &copy; 2017</h4>
	</div>
</div>
</div>

<script>
(function() {
var rasm = document.querySelector('.localstorage');
function supportsLocalStorage() {
return typeof(Storage)!== 'undefined';
}
if (!supportsLocalStorage()) {
rasm.value = 'Your browser does not support localStorage.';
} else {
try {
setInterval(function() {
localStorage.setItem('autosave', rasm.value);
}, 1000);
} catch (e) {
if (e == QUOTA_EXCEEDED_ERR) {
alert('Quota exceeded!');
}
}
if (localStorage.getItem('autosave')) {
rasm.value = localStorage.getItem('autosave');
}
document.querySelector('.clear').onclick = function() {
rasm.value = '';
localStorage.removeItem('autosave');
};
document.querySelector('.empty').onclick = function() {
rasm.value = '';
localStorage.clear();
};
}
})();
</script>

</div>
</body>
</html>

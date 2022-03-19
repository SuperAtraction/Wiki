# Le Wiki Officiel de SuperAtraction

<button onClick="Menu()">Menu</button>

<div id="temp"></div>
<div id="L"></div>
<script src="https://superatraction.github.io/JQuery/external/jquery/jquery.js"></script>
<script src="https://superatraction.github.io/JQuery/jquery-ui.js"></script>
<script type="text/javascript">
	$("#temp").load("dialog.txt");
$( "#temp" ).dialog({
autoOpen: false,
      show: {
        effect: "blind",
        duration: 1000
      },
      hide: {
        effect: "explode",
        duration: 1000
      },
          modal: true,
            buttons: {
      }
});
	
  $("#L").load("LWiki.txt");
  
function Menu() {
      $( "#temp" ).dialog("open");
}
	
	
</script>

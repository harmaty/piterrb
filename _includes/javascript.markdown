<script src="http://www.google.com/jsapi"></script>
<script>
google.load("jquery", "1");
</script>
<script src="/javascript/corner.js"></script>
<script src="/javascript/jquery.juitter.js"></script>
<script src="/javascript/system.js"></script>
<script src="/javascript/jquery.lavalamp.min.js" type="text/javascript" charset="utf-8"></script>
<script src="/javascript/jquery.easing.min.js" type="text/javascript" charset="utf-8"></script>

<script type="text/javascript" charset="utf-8">
$(document).ready(function(){
	$('#roundme').corner("15px");
	$('#footer').corner("15px bottom");
	SyntaxHighlighter.all();			
	$(function() { $(".lavaLamp").lavaLamp({ fx: "backout", speed: 700 })});
});
</script>

<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-5336691-8']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>

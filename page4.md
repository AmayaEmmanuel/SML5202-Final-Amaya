<h1>Vocabulary Games</h1>
<p>I believe learning is a lot more effective when you are having fun so here are some vocabulary games to help with your memorization and overall learning</p>


<h2><em>Words of the Days:)</em></h2>
<dl id="quote"></dl>
<!--<script src="script.js"></script>-->
<p><button onclick="loadQuote()">See another word</button></p>
<hr />

<script>
var idioms = [ 
'Lunes', 
'Martes', 
'Miércoles',    
'Jueves',
'Viernes',
'Sábado'
];

var examples = [
'Translation: <i> Monday.</i>', 
'Translation: <i> Tuesday.</i>', 
'Translation: <i> Wednesday.</i>',
'Translation: <i> Thursday.</i>',
'Translation: <i> Friday.</i>',
'Translation: <i> Saturday.</i>'

];

var quoteNo;
var idiomNo;
function loadQuote() {
    idiomNo = Math.floor(Math.random() * (idioms.length));
    if(idiomNo !== quoteNo) {
    //alert(quotes[quoteNo]);
    	document.getElementById("quote").innerHTML = "<dt>" + idioms[idiomNo] + "</dt>" + "<dd>" + examples[idiomNo] + "</dd>";
   	quoteNo = idiomNo;
    	return quoteNo;
    	}
    	else {
    	loadQuote();
    	}
	}
loadQuote();
</script>

<iframe src="https://amayazemmanuel.h5p.com/content/1291217370654367327/embed" width="1088" height="637" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://amayazemmanuel.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<iframe src="https://amayazemmanuel.h5p.com/content/1291194507686359497/embed" width="1088" height="637" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://amayazemmanuel.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

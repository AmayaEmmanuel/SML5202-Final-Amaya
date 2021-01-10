<h1>Vocabulary Games</h1>
<p>I believe learning is a lot more effective when you are having fun so here are some vocabulary games to help with your memorization and overall learning</p>

<h3>Word for Today</h3>
<p id="quote"></p>
<script>
var idioms = [ 
'Lunes', 
'Martes', 
'Miércoles',    
'Jueves',
'Viernes',
'Sábado'
'Domingo', 
'Enero', 
'Febrero ',    
'Marzo',
'Abril',
'Mayo '
'Junio', 
'Julio', 
'Agosto',    
'Septiembre',
'Octubre ',
'Noviembre '
'Diciembre', 
];

var examples = [
'Example: <i> Monday.</i>', 
'Example: <i> Tuesday.</i>', 
'Example: <i> Wednesday.</i>',
'Example: <i> Thursday.</i>',
'Example: <i> Friday.</i>',
'Example: <i> Saturday.</i>'
'Example: <i> Sunday.</i>', 
'Example: <i> January.</i>', 
'Example: <i> February.</i>',
'Example: <i>March.</i>',
'Example: <i> April.</i>',
'Example: <i> May.</i>'
'Example: <i> June.</i>', 
'Example: <i> July.</i>', 
'Example: <i> August.</i>',
'Example: <i>J September.</i>',
'Example: <i> October.</i>',
'Example: <i> November.</i>'
'Example: <i> December.</i>'
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


<iframe src="https://amayazemmanuel.h5p.com/content/1291194507686359497/embed" width="1088" height="637" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://amayazemmanuel.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

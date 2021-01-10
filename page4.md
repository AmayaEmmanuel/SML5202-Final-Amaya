<h1>Vocabulary Games</h1>
<p>I believe learning is a lot more effective when you are having fun so here are some vocabulary games to help with your memorization and overall learning</p>

<iframe src="https://amayazemmanuel.h5p.com/content/1291194507686359497/embed" width="1088" height="637" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://amayazemmanuel.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<h3>Word for Today</h3>
<p id="quote"></p>
<script>
var idioms = [ 
'Lunes = Monday.', 
'Martes = Tuesday.', 
'Miércoles = Wednesday.',    
'Jueves = Thursday.',
'Viernes = Friday.',
'Sábado = Saturday.'
'Domingo = Sunday.', 
'Enero = January.', 
'Febrero = February.',    
'Marzo = March.',
'Abril = April.',
'Mayo = May.'
'Junio = June.', 
'Julio = July.', 
'Agosto = August.',    
'Septiembre = September.',
'Octubre = October.',
'Noviembre = November.'
'Diciembre = December.', 
];

var examples = [
'Example: <i>Lunes = Monday.</i>', 
'Example: <i>Martes = Tuesday.</i>', 
'Example: <i>Miércoles = Wednesday.</i>',
'Example: <i>Jueves = Thursday.</i>',
'Example: <i>Viernes = Friday.</i>',
'Example: <i>Sábado = Saturday.</i>'
'Example: <i>Domingo = Sunday.</i>', 
'Example: <i>Enero = January.</i>', 
'Example: <i>Febrero = February.</i>',
'Example: <i>Marzo = March.</i>',
'Example: <i>Abril = April.</i>',
'Example: <i>Mayo = May.</i>'
'Example: <i>Junio = June.</i>', 
'Example: <i>Julio = July.</i>', 
'Example: <i>Agosto = August.</i>',
'Example: <i>JSeptiembre = September.</i>',
'Example: <i>Octubre = October.</i>',
'Example: <i>Noviembre = November.</i>'
'Example: <i>Diciembre = December.</i>'
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

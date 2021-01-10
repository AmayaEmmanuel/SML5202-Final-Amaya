<h1>Vocabulary Games</h1>
<p>I believe learning is a lot more effective when you are having fun so here are some vocabulary games to help with your memorization and overall learning</p>

<iframe src="https://amayazemmanuel.h5p.com/content/1291194507686359497/embed" width="1088" height="637" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://amayazemmanuel.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<p id="quote"></p>



<script>
var idioms = [ 
'comer = to eat.', 
'Tickled pink = to be extremely pleased.', 
'Caught red-handed = to catch someone in the act of doing something.',    
'White lie = a small lie that is told to be polite or avoid hurting someone’s feelings.',
'Feel blue = Be depressed or sad. The use of blue to mean “sad” dates from the late 1300s.',
'See red = Become very angry suddenly.'
];

var examples = [
'Example: <i>como una manzaña.</i>', 
'Example: <i>Your grandma was tickled pink that you called on her birthday!</i>', 
'Example: <i>He was caught red-handed while stealing those biscuits.</i>',
'Example: <i>I didn’t like her dress, but I told a white lie because I didn’t want to offend her.</i>',
'Example: <i>I was really feeling blue after she told me she was leaving.</i>',
'Example: <i>The thought of Piers with Nicole made her see red.</i>'

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

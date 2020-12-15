<h1>Page 5</h1>
<p>write your content in this file as you would normally</p>

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

<h1>Vocabulary Games</h1>
<p>I believe learning is a lot more effective when you are having fun so here are some vocabulary games to help with your memorization and overall learning!</p>


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
<iframe src="https://h5p.org/h5p/embed/1089046" width="1090" height="845" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

<iframe src="https://h5p.org/h5p/embed/1089045" width="1090" height="792" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

<h3><em>Below is a recording of all the numbers in Spanish from 0-100. After each number pause the audio and practise the pronunciation. This will help you a LOT!</em></h3>
<iframe src="https://h5p.org/h5p/embed/1089047" width="1090" height="87" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

<h4> Sources </h4>
<p>

Cloudconvert.com. 2021. M4A To MP3 | Cloudconvert. [online] Available at: <https://cloudconvert.com/m4a-to-mp3> [Accessed 8 January 2021].

Ict4lt.org. 2021. Warschauer: Computer-Assisted Language Learning. [online] Available at: <http://www.ict4lt.org/en/warschauer.htm> [Accessed 8 January 2021].

Www2.nkfust.edu.tw. 2021. Intro To CALL. [online] Available at: <http://www2.nkfust.edu.tw/~emchen/CALL/unit1.htm#types> [Accessed 8 January 2021].

W3schools.com. 2021. HTML Images. [online] Available at: <https://www.w3schools.com/html/html_images.asp> [Accessed 8 January 2021].

W3schools.com. 2021. Tryit Editor V3.6. [online] Available at: <https://www.w3schools.com/html/tryit.asp?filename=tryhtml_script_html> [Accessed 8 January 2021].
</p>

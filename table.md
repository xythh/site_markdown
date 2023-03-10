title: Pitch table
description: table of different pitch patterns
layout: table.html
---

<form id="bloatbox" style="display: block;">
	<input type="text" id="narrow" placeholder="Filter concepts">
	<span class="option_container"><input type="checkbox" checked id="verbs" value="0"> <span class="option_caption" >Verbs</span></span>
	<span class="option_container"><input type="checkbox" checked id="nouns" value="0"> <span class="option_caption" >Nouns</span></span>
	<span class="option_container"><input type="checkbox" checked id="adjectives" value="0"> <span class="option_caption" >adjectives</span></span>
</form>


<p>Data source: <a href="NotOrange">NotOrange Notes</a>. Colors show what category each Pattern belongs to.<br><span id="js_hint" style="display: inline;"> Hint: Type <code>"と"</code> in the search box below to find all と entries. Middle click to view the section in the document.</span></p>

{{[pitchTable}}
# Standard csv format  use " if you want to enclose a , eg. ","
# to make the table column multiline use <br>
# entryname,category,htmlreference,description
さ,verbs,entries/1.html,accented words will be ⠀さ{1} <br> heiban words will be さ⠀{0}
症,nouns,entries/nouns.html,しょう{0}
め,adjectives,entries/adjectives,め will go め⠀{0} wow
{{]pitchTable}}


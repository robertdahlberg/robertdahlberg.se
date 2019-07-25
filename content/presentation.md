+++
title = "Presentation"
description = "about this site"
date = "2017-09-29"
slug = ""
type = "nav"
+++

<div class="row">
<div class="col-sm">
Jag heter Robert Dahlberg, är <p id="p1" style="display: contents;"></p> år gammal och arbetar just nu som full-stack webdeveloper hos Studentmedia.
Här har jag huvudansvaret över nyutvecklingen, vidareutvecklingen och andra tekniska frågor. Språken som jag sitter med just idag är .Net C#, SQL, olika javascript, Angular, Node, mongoDB och hugo. 
<p></p>                  
Under min utbildning har jag fått utmärkta programmeringskunskaper inom C#, .Net och webbutveckling.
Vi har även läst SQL och Windows Azure. Jag har även fått testat på mina kunskaper under två stycken
praktikperioder som en del av utbildningen och där även fått erfarenhet att jobba med Agil utveckling och Scrum.
</div>

<div class="col-sm">
Jag arbetar också just nu som ishockeydomare och som statistikoperatör i SHL. Det är ett tufft arbete då spelare
och ledare kräver att jag är en bra matchledare och presterar på topp. 
<p></p>
Det krävs också ett mentalt lugn och en bra fysisk status.
Som statistikoperatör jobbar jag under Örebro hockeys hemmamatcher i sekretariatet. Där sköter jag kommunikationen
med domarna och ser till att speaker, matchklockan och utvisningsbås får rätt information.
Som person är jag van att jobba i grupp men även ensam med eget helhetsansvar. Jag är mycket engagerad
och har hög arbetsmoral. 
</div>


<div class="col-sm">
Andra ser mig som en nyfiken person med intresse för att hitta nya saker
att lära mig. Jag är van att jobba under stress då jag under mitt domaryrke ofta sätts under pressade
situationer som tvingar mig att ta snabba beslut.
<p></p>
Jag är inte rädd att ta mig an nya utmaningar då jag vet att det kommer utveckla mig som systemutvecklare
och människa.
Tack för att ni tagit er tid att läsa detta. Jag ser fram emot att få berätta mer om mig själv vid ett
personligt möte med er. 
<p></p>
Med vänlig hälsning
<p></p>
Robert Dahlberg
</div>
</div>

<script>
    function calculate_age(dob) { 
    var diff_ms = Date.now() - dob.getTime();
    var age_dt = new Date(diff_ms); 
  
    return Math.abs(age_dt.getUTCFullYear() - 1970);
}
document.getElementById("p1").innerHTML = calculate_age(new Date(1991, 8, 21));
</script>
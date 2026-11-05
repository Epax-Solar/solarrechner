Einbindung

<div id="pv-rechner"></div>
<script defer
  src="https://cdn.jsdelivr.net/gh/epaxalexn/solarrechner@main/rechner.js"
  data-name="Sonnenwerk GmbH"
  data-phone="+49 89 123456"
  data-email="anfrage@sonnenwerk.de"
  data-color="#1F6B4A"
  data-max-width="800px">
</script>

data-name, data-phone, data-email und data-color trägt der Installateur ein.
data-font-color ist optional. Ohne Angabe ist die Schrift auf den farbigen Buttons weiß. Mit black wird sie schwarz, zum Beispiel bei Gelb oder Orange.
data-max-width ist optional. Ohne Angabe bleibt der Rechner bei 640px. Erlaubt sind 240 bis 4000 Pixel, als Zahl oder mit px.
Telefon oder E-Mail weglassen, dann fehlt der passende Button. Die eingetragene Nummer und Adresse stehen zusätzlich als Text unter den Buttons.
data-logo ist optional und eine http- oder https-Adresse.
Die Rechnung steht in rechner.js. Ein Push auf main gilt für alle Installateure.
Das Skript mit defer einbinden. Es blockiert dann den Rest der Seite nicht beim Laden.

<h1>Algebraic expressions</h1>
Mick Bos en Youri de Vor
<h2> Uitleg code</h2>

<h3>Call tree</h2>
main
<h3>Totaal uitleg</h3>
Door de <b>main</b> code te runnen, trainen wij het neurale netwerk met de testset, en testen het neurale netwerk met een validatieset

<h2>Resultaten</h2>
Wij hebben een aantal beslissingen gemaakt als het gaat om ons neurale netwerk. Zo hebben wij gekozen voor twee hidden layers. Na meerdere keren testen zijn we tot de conclusie gekomen dat twee layers, eentje met 456 neuronen en een met 128 neuronen. Dit was voor ons de beste oplossing uit meerdere testen die we gedaan hebben met verschillende nummers. De output layer is natuurlijk 10 omdat dit het aantal verschillende outputs zijn.  
Na testen met verschillende breakout nummers, hebben we gekozen voor een breakout van 0.1. Dit doen we zodat het neurale netwerk niet alleen werkt met de testdata, maar ook met meerdere datapunten. 
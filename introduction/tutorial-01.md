<h3>Ein einfacher Ablauf in BPMN</h3>

Beginnen wir unser BPMN-Tutorial mit einem recht einfachen Prozessdiagramm:

<h4>Diagramm </h4> <b>Prozess "Hunger stillen"</b>
<img src="./images/tutorial-01.png"> </img>
<h4>Ergänzende Beschreibung ohne weitere Detaillierung</h4>
<li>
1 Hunger festgestellt 
</li><li>
2 Lebensmittel einkaufen
 </li><li>
3 Mahlzeit zubereiten
 </li><li>
4 Mahlzeit zubereitet
 </li><li>
5 Mahlzeit essen
 </li><li>
6 Hunger gestillt
</li><p></p>

Dieses Diagramm zeigt einen einfachen Prozess, der dadurch ausgelöst wird, dass jemand hungrig ist. 
Das Ergebnis ist, dass jemand Lebensmittel einkaufen und eine Mahlzeit zubereiten muss. 
Danach isst die Person die Mahlzeit und hat ihren Hunger gestillt.

<b>Bewährte Praxis: Benennungskonventionen</b>
 
 Bei der Benennung von <b>Aufgaben</b> versuchen wir, uns an das objektorientierte Designprinzip zu halten und das Muster <b>[Objekt] + [Verb]</b> zu verwenden. Wir würden z. B. sagen: "Bitte Lebensmittel einkaufen", nicht: "Kümmern Sie sich zuerst um den Einkauf von Lebensmitteln".
 <p></p>
<b>Ereignisse</b> beziehen sich auf etwas, das unabhängig vom Prozess bereits geschehen ist (wenn es sich um fangende Ereignisse handelt) oder als Ergebnis des Prozesses (wenn es sich um werfende Ereignisse handelt). </p>

<p>Aus diesem Grund verwenden wir <b>[Objekt] + [Verb im Passiv]</b>, wir schreiben also <em>"Hunger bemerkt"</em>. </p>
<p>BPMN verlangt nicht, dass Sie Start- und Endereignisse für einen Prozess modellieren - Sie können sie weglassen - aber wenn Sie ein Startereignis modellieren, müssen Sie ein Endereignis für jeden Pfad modellieren. </p>
<p>Das Gleiche gilt für Endereignisse, für die Startereignisse erforderlich sind. Wir erstellen unsere Modelle immer mit Start- und Endereignissen, und zwar aus zwei Gründen: Erstens lässt sich auf diese Weise der Prozessauslöser bestimmen, und zweitens können Sie den Endstatus jedes Pfadendes beschreiben. Nur bei Sub-Prozessen verzichten wir manchmal auf diese Praxis. Dazu später mehr.</p>
<p>
 <p><b>Nummerierung</b></p>
<p>Es hat sich bewährt eine Nummerierung einzuführen, wenn es darum geht die Aufgaben und Ereignisse noch detailierter zu bschreiben. Diese Nummerierung kann dann in einem getrennten Dokument tabellarisch zur weiteren Beschreibung herangezogen werden.
 </p>
FAQ: Ist es zwingend erforderlich, BPMN-Diagramme horizontal zu zeichnen? Was ist, wenn ich sie lieber vertikal zeichne?
Sie können Ihre Diagramme immer von oben nach unten statt von links nach rechts zeichnen - der BPMN 2.0-Standard verbietet das nicht. Wir empfehlen es jedoch nicht: Es ist sehr unüblich, und die Erfahrung hat gezeigt, dass die Menschen den Prozessfluss besser verstehen, wenn er auf dieselbe Weise beschrieben wird wie ein geschriebener Text (von links nach rechts, zumindest in der westlichen Welt).
 </p>
 
 <h3>Verwendete Symbole</h3>
 Startereignis <b>[Nr] + [Objekt] + [Verb im Passiv]</b> <img src="./images/start-event.png"> </img>
 Aufgabe <b>[Nr]  + [Objekt] + [Verb]</b><img src="./images/task.png">  </img>
 Zwischenereignis <b>[Nr] + [Objekt] + [Verb im Passiv]</b> <img src="./images/intermediate-event.png"> </img>
 Endereignis <b>[Nr] + [Objekt] + [Verb im Passiv]</b> <img src="./images/end-event.png"> </img>
 Verbindung <img src="./images/sequence-flow.png"> </img>
 


<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Norderney – Nachhaltigkeit interaktiv</title>

<style>
body{font-family: Arial, Helvetica, sans-serif;margin:0;background:#f2f6f7;line-height:1.6;}
header{background:#1f7a8c;color:white;padding:20px;text-align:center;}
section{background:white;margin:20px;padding:20px;border-radius:10px;box-shadow:0 2px 6px rgba(0,0,0,0.15);} 
h2{color:#1f7a8c;}
details{margin-top:10px;padding:10px;background:#eef6f8;border-radius:6px;}
textarea{width:100%;height:90px;margin-top:10px;border-radius:6px;border:1px solid #ccc;padding:8px;}
button{background:#1f7a8c;color:white;border:none;padding:10px 15px;border-radius:6px;cursor:pointer;}
button:hover{background:#155d6a;}
.result{font-weight:bold;margin-top:10px;font-size:1.1em;}
a{color:#1f7a8c;}
/* Sektionen */
.section { display:none; padding:20px; }
.section.active { display:block; }
/* Navbar */
.navbar button { margin:5px; padding:8px 12px; cursor:pointer; }
/* Speichern-Button fixiert */
#saveBtn {
    position: fixed;
    top: 10px;
    right: 10px;
    padding: 10px 15px;
    background: #0b6efd;
    color: white;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    z-index: 1000;
}
#saveBtn:hover {
    background: #084aad;
}
</style>
</head>

<body>

<!-- ===== Header ===== -->
<header>
<h1>Norderney und Nachhaltigkeit</h1>
<p>Lesen – Verstehen – Reflektieren – Anwenden</p>
<p>Ein Lernmodul zu Ökologie, Ökonomie und Gesellschaft</p>
</header>

<!-- ===== SPEICHERN-BUTTON ===== -->
<button id="saveBtn" onclick="savePage()">Seite lokal speichern</button>

<!-- ===== Navigation ===== -->
<div class="navbar" style="position:sticky;top:0;background:#ffffff;padding:10px;z-index:1500;border-bottom:1px solid #ddd;">
    <button onclick="showSection('Klima')">Klima</button>
    <button onclick="showSection('Ökologie')">Ökologie</button>
    <button onclick="showSection('Ökonomie')">Ökonomie</button>
    <button onclick="showSection('Soziales')">Soziales</button>
    <button onclick="showSection('Aufgaben')">Aufgaben</button>
    <button onclick="showSection('Wahlaufgaben')">Wahlaufgaben</button>
    <button onclick="showSection('Quiz')">Quiz</button>
</div>

<!-- ===== Inhalt ===== -->
<section>
<h2>Arbeitsauftrag</h2>
<ol>
<li>Öffne die Texte Schritt für Schritt (leicht → mittel → schwer).</li>
<li>Notiere wichtige Stichpunkte in die Felder.</li>
<li>Nutze bei Bedarf die Quellen zur eigenen Recherche.</li>
<li>Bearbeite die Pflichtaufgaben und schreibe deine Lösungen in die Felder.</li>
<li>Bearbeite eine der Wahlaufgaben und schreibe deine Lösung in das Feld.</li>
<li>Bearbeite am Ende das Quiz.</li>
</ol>
</section>

<section>
<h2>Hinweise</h2>
<ol>
<li>Erarbeite dir dein Wissen schrittweise.</li>
<li>Nutze die eingearbeiteten Lehrbuchseiten als Wissensquellen.</li>
<li>Navigiere dich durch die Themen mit den Button oben.</li>
<li>Speichere die Datei lokal auf deinem iPad mit allen Eintragungen mittels Button oben rechts.</li>
</ol>
</section>

<!-- ===== Bildbereich mit Thumbnail & Öffnung in neuem Tab ===== -->
<section style="margin-top:60px; padding:20px; background:#f4f6f8; border-radius:12px;">
    <h2>Lehrbuchseite – Tourismusregion Küste</h2>
    <p>Klicke auf das Vorschaubild, um es in einem neuen Tab groß zu öffnen.</p>
    
    <a href="Tourismusregion_Kueste.png" target="_blank">
        <img src="Tourismusregion_Kueste.png" 
             alt="Tourismusregion Küste" 
             style="width:220px; cursor:pointer; border-radius:8px; box-shadow:0 4px 12px rgba(0,0,0,0.2);">
    </a>
</section>


<section id="Klima" class="section">
<h2>Klima</h2>

<details>
<summary>Grundwissen</summary>
<p>Norderney liegt in der Nordsee und wird stark vom Meer beeinflusst. Das Wasser speichert Wärme und sorgt dafür, dass die Winter milder und die Sommer kühler sind als im Binnenland. Häufig weht Wind, weil sich Luftdruckunterschiede über dem offenen Meer schnell ausgleichen. Die Luft enthält viel Salz und Feuchtigkeit, was das Klima besonders macht. Viele Menschen empfinden dieses sogenannte Reizklima als gesund, weshalb die Insel schon früh ein Kurort wurde.</p>
</details>

<details>
<summary>Erweitertes Wissen</summary>
<p>Das Seeklima beeinflusst nicht nur das Wetter, sondern auch Landschaft, Pflanzen und menschliche Nutzung. Durch den ständigen Wind trocknen Böden schneller aus, gleichzeitig wird aber auch ständig neuer Sand bewegt. Niederschläge verteilen sich relativ gleichmäßig über das Jahr, extreme Hitze oder strenger Frost treten selten auf. Diese ausgeglichenen Bedingungen machen die Insel zu einem beliebten Urlaubsziel. Gleichzeitig müssen Gebäude und Infrastruktur so gebaut werden, dass sie Wind und Salz dauerhaft standhalten.</p>
</details>

<details>
<summary>Expertenwissen</summary>
<p>Im Zusammenhang mit dem Klimawandel stehen Nordseeinseln vor besonderen Herausforderungen. Der Meeresspiegel steigt langfristig an, während Sturmfluten intensiver werden können. Nachhaltiger Küstenschutz setzt deshalb nicht nur auf Deiche, sondern auch auf natürliche Prozesse wie den Erhalt von Dünen. Wissenschaftler sprechen von „weichem Küstenschutz“, der Naturkräfte nutzt statt sie vollständig zu kontrollieren. Dadurch sollen ökologische Stabilität, Sicherheit der Bewohner und touristische Nutzung miteinander vereinbart werden.</p>
</details>

<strong>Deine Stichpunkte:</strong>
<textarea></textarea>

<details>
<summary>Quellen zur Vertiefung</summary>
<ul>
<li><a href="https://www.umweltbundesamt.de" target="_blank">Umweltbundesamt – Klimawandel</a></li>
<li><a href="https://www.nationalpark-wattenmeer.de" target="_blank">Nationalpark Wattenmeer</a></li>
<li><a href="https://www.dwd.de" target="_blank">Deutscher Wetterdienst</a></li>
</ul>
</details>
</section>

<section id="Ökologie" class="section">
<h2>Ökologie</h2>

<details>
<summary>Grundwissen</summary>
<p>Die Landschaft ist von Dünen, Strand und Salzwiesen geprägt. Dort wachsen spezialisierte Pflanzen wie Strandhafer, die mit wenig Süßwasser und viel Salz auskommen. Diese Pflanzen haben lange Wurzeln und halten den Sand fest. Dadurch verhindern sie, dass Wind den Sand wegweht. Ohne diese Vegetation würde sich die Insel viel schneller verändern.</p>
</details>

<details>
<summary>Erweitertes Wissen</summary>
<p>Das Wattenmeer gehört zu den artenreichsten Lebensräumen Europas. Viele Zugvögel nutzen es als Rastplatz auf ihren langen Wanderungen. Zahlreiche Kleintiere leben im Watt und bilden die Grundlage einer komplexen Nahrungskette. Weil dieses Ökosystem empfindlich ist, müssen Besucher auf markierten Wegen bleiben. Nachhaltiger Naturschutz bedeutet hier, Nutzung und Schutz gleichzeitig zu ermöglichen.</p>
</details>

<details>
<summary>Expertenwissen</summary>
<p>Die Dünenbildung ist ein dynamischer Prozess aus Wind, Sandtransport und Vegetation. Eingriffe des Menschen können dieses Gleichgewicht schnell stören. Deshalb arbeiten Naturschutz, Tourismus und Forschung eng zusammen, um Besucher zu lenken und sensible Bereiche zu schützen. Maßnahmen wie Stege oder gekennzeichnete Wege verbinden Umweltbildung mit Schutz der Biodiversität. Nachhaltigkeit zeigt sich hier als langfristiges Management eines empfindlichen Naturraums.</p>
</details>

<strong>Deine Stichpunkte:</strong>
<textarea></textarea>

<details>
<summary>Quellen zur Vertiefung</summary>
<ul>
<li><a href="https://www.wwf.de/themen-projekte/meere-kuesten/wattenmeer" target="_blank">WWF Wattenmeer</a></li>
<li><a href="https://www.bfn.de" target="_blank">Bundesamt für Naturschutz</a></li>
<li><a href="https://www.unesco.de" target="_blank">UNESCO-Weltnaturerbe Wattenmeer</a></li>
</ul>
</details>
</section>

<section id="Ökonomie" class="section">
<h2>Wirtschaft</h2>

<details>
<summary>Grundwissen</summary>
<p>Die Wirtschaft wird fast vollständig vom Tourismus getragen. Viele Menschen arbeiten in Hotels, Gastronomie oder im Verkehrswesen. Dadurch ist die Insel stark von Besucherzahlen abhängig. Eine gute Saison sichert Einkommen und Arbeitsplätze. Schwächere Jahre wirken sich sofort auf die Bevölkerung aus.</p>
</details>

<details>
<summary>Erweitertes Wissen</summary>
<p>Tourismus bringt jedoch auch Belastungen für Umwelt und Infrastruktur. Energieverbrauch, Abfall und Flächenbedarf steigen mit der Zahl der Gäste. Deshalb setzen viele Betriebe auf nachhaltige Konzepte wie regionale Produkte oder Müllvermeidung. Auch der Verkehr wird bewusst reduziert, etwa durch Fahrradnutzung. Ziel ist es, wirtschaftlichen Erfolg mit Umweltverträglichkeit zu verbinden.</p>
</details>

<details>
<summary>Expertenwissen</summary>
<p>Nachhaltiger Tourismus beschreibt die Balance zwischen ökonomischer Stabilität, ökologischer Tragfähigkeit und sozialer Verantwortung. Strategien kombinieren Besucherlenkung, Klimaschutz und regionale Wertschöpfung. Digitalisierung hilft dabei, Ressourcen effizienter zu nutzen. Politische Entscheidungen müssen sicherstellen, dass wirtschaftlicher Nutzen nicht auf Kosten zukünftiger Generationen entsteht. Norderney dient daher als Beispiel für nachhaltige Entwicklung in sensiblen Regionen.</p>
</details>

<strong>Deine Stichpunkte:</strong>
<textarea></textarea>

<details>
<summary>Quellen zur Vertiefung</summary>
<ul>
<li><a href="https://www.destatis.de" target="_blank">Statistisches Bundesamt – Tourismusdaten</a></li>
<li><a href="https://www.niedersachsen.de" target="_blank">Land Niedersachsen</a></li>
<li><a href="https://www.dwif.de" target="_blank">Deutsches Wirtschaftswissenschaftliches Institut für Fremdenverkehr</a></li>
</ul>
</details>
</section>

<section id="Soziales" class="section">
<h2>Gesellschaft, Kultur und Geschichte</h2>

<details>
<summary>Grundwissen</summary>
<p>Norderney war ursprünglich ein Fischerdorf und entwickelte sich später zu einem bekannten Nordseeheilbad. Viele historische Gebäude erinnern an diese Zeit. Tourismus ist daher eng mit der Geschichte der Insel verbunden. Tradition und moderne Nutzung existieren nebeneinander. Die Insel ist sowohl Lebensraum als auch Urlaubsziel.</p>
</details>

<details>
<summary>Erweitertes Wissen</summary>
<p>Das Leben auf einer Insel stellt besondere Anforderungen an die Gemeinschaft. Wohnraum ist begrenzt und viele Arbeitsplätze sind saisonabhängig. Gleichzeitig profitieren Kulturangebote und Infrastruktur von den Gästen. Nachhaltigkeit bedeutet, ein Gleichgewicht zwischen Bewohnern und Besuchern zu finden. Nur so bleibt die Insel langfristig lebenswert.</p>
</details>

<details>
<summary>Expertenwissen</summary>
<p>Soziale Nachhaltigkeit umfasst gerechte Arbeitsbedingungen, bezahlbaren Wohnraum und den Erhalt regionaler Identität. Inselgemeinden müssen verhindern, dass sie zu reinen Urlaubsorten ohne stabile Bevölkerung werden. Bürgerbeteiligung und langfristige Planung spielen deshalb eine wichtige Rolle. Wissenschaftlich spricht man von nachhaltiger Regionalentwicklung. Dabei werden Umwelt, Wirtschaft und Gesellschaft gemeinsam gedacht.</p>
</details>

<strong>Deine Stichpunkte:</strong>
<textarea></textarea>

<details>
<summary>Quellen zur Vertiefung</summary>
<ul>
<li><a href="https://www.norderney.de" target="_blank">Offizielle Seite der Insel</a></li>
<li><a href="https://www.ndr.de" target="_blank">NDR Berichte zur Nordsee</a></li>
<li><a href="https://www.bpb.de" target="_blank">Bundeszentrale für politische Bildung</a></li>
</ul>
</details>
</section>

<!-- Pflichtaufträge, Wahlaufgaben und Quiz bleiben unverändert -->

<section id="Aufgaben" class="section">

<h2>Pflichtauftrag</h2>
<p>Bearbeite alle Aufgaben:</p>
<p><strong>1. Beschreibe das Klima der Insel.</strong></p>
<textarea></textarea>
<p><strong>2. Erkläre die Bedeutung der Dünen.</strong></p>
<textarea></textarea>
<p><strong>3. Zeige Chancen und Probleme des Tourismus.</strong></p>
<textarea></textarea>
<p><strong>4. Was bedeutet Nachhaltigkeit für die Bewohner?</strong></p>
<textarea></textarea>
</section>

<section id="Wahlaufgaben" class="section">

<h2>Wahlaufgaben (eine auswählen)</h2>
<p><strong>A. Vergleiche Norderney mit eurem Wohnort.</strong></p>
<textarea></textarea>
<p><strong>B. Formuliere Regeln für nachhaltige Touristen.</strong></p>
<textarea></textarea>
<p><strong>C. Beschreibe die Insel im Jahr 2050.</strong></p>
<textarea></textarea>
</section>

<section id="Quiz" class="section">

<h2>Quiz</h2>
<form id="quizForm">
<p>1. Was ist typisch für Seeklima?</p>
<label><input type="radio" name="q1" value="1"> Milde Winter, kühle Sommer</label><br>
<label><input type="radio" name="q1" value="0"> Extreme Hitze</label>
<p>2. Welche Pflanze schützt Dünen?</p>
<label><input type="radio" name="q2" value="1"> Strandhafer</label><br>
<label><input type="radio" name="q2" value="0"> Tulpen</label>
<p>3. Wichtigster Wirtschaftszweig?</p>
<label><input type="radio" name="q3" value="1"> Tourismus</label><br>
<label><input type="radio" name="q3" value="0"> Bergbau</label>
<p>4. Warum sind Dünen wichtig?</p>
<label><input type="radio" name="q4" value="1"> Küstenschutz</label><br>
<label><input type="radio" name="q4" value="0"> Dekoration</label>
<p>5. Was bedroht Inseln langfristig?</p>
<label><input type="radio" name="q5" value="1"> Meeresspiegelanstieg</label><br>
<label><input type="radio" name="q5" value="0"> Schneestürme</label>
<p>6. Was ist nachhaltiger Verkehr?</p>
<label><input type="radio" name="q6" value="1"> Fahrradnutzung</label><br>
<label><input type="radio" name="q6" value="0"> Mehr Autos</label>
<p>7. Warum ist das Wattenmeer wichtig?</p>
<label><input type="radio" name="q7" value="1"> Lebensraum vieler Arten</label><br>
<label><input type="radio" name="q7" value="0"> Ohne Bedeutung</label>
<p>8. Nachhaltigkeit verbindet…</p>
<label><input type="radio" name="q8" value="1"> Umwelt, Wirtschaft, Gesellschaft</label><br>
<label><input type="radio" name="q8" value="0"> Nur Wirtschaft</label>
<p>9. Warum Besucher lenken?</p>
<label><input type="radio" name="q9" value="1"> Schutz empfindlicher Natur</label><br>
<label><input type="radio" name="q9" value="0"> Zufall</label>
<p>10. Ziel nachhaltiger Entwicklung?</p>
<label><input type="radio" name="q10" value="1"> Zukunft sichern</label><br>
<label><input type="radio" name="q10" value="0"> Kurzfristiger Nutzen</label>
<br><br>
<button type="button" onclick="checkQuiz()">Auswerten</button>
</form>
<p class="result" id="result"></p>
</section>

<!-- Restliche Sektionen (Klima, Ökologie, Ökonomie, Soziales, Aufgaben, Wahlaufgaben, Quiz) bleiben unverändert -->
<!-- ... (Hier kommen die bereits vorhandenen Sektionen aus deinem Code) ... -->

<script>
// ===============================
// QUIZ-AUSWERTUNG
// ===============================
function checkQuiz() {
    let score = 0;
    for (let i = 1; i <= 10; i++) {
        const q = document.querySelector('input[name="q' + i + '"]:checked');
        if (q && q.value === "1") score++;
    }
    document.getElementById("result").textContent =
        "Du hast " + score + " von 10 Fragen richtig beantwortet.";
}

// ===============================
// SEITE MIT NOTIZEN SPEICHERN
// ===============================
function savePage() {
    // Inhalte aller Textareas in das HTML übernehmen
    const textareas = document.querySelectorAll('textarea');
    textareas.forEach(area => area.innerHTML = area.value);

    // Gesamte HTML-Datei erfassen
    const content = document.documentElement.outerHTML;

    // Blob erzeugen
    const blob = new Blob([content], { type: 'text/html' });
    const a = document.createElement('a');
    a.href = URL.createObjectURL(blob);
    a.download = 'Nachhaltigkeit_Norderney_Unterricht.html';

    // Download starten
    document.body.appendChild(a);
    a.click();
    document.body.removeChild(a);
    URL.revokeObjectURL(a.href);

    // Safari-Hinweis
    const isSafari = /^((?!chrome|android).)*safari/i.test(navigator.userAgent);
    if (isSafari) {
        alert(
            "Hinweis für Safari-Nutzer:\n" +
            "Die Datei wurde im Download-Ordner gespeichert.\n" +
            "Bitte verschiebe sie manuell an den gewünschten Ort und überschreibe ggf. die alte Datei."
        );
    }
}
// ===============================
// SEKTIONEN-NAVIGATION
// ===============================
function showSection(id) {
    document.querySelectorAll('.section').forEach(function(sec) {
        sec.classList.remove('active');
    });
    const el = document.getElementById(id);
    if (el) el.classList.add('active');
}

// ===============================
// STARTZUSTAND BEIM LADEN
// ===============================
window.onload = function () {
    // Erste Sektion automatisch anzeigen
    const first = document.querySelector('.section');
    if (first) first.classList.add('active');
};
</script>

</body>
</html>

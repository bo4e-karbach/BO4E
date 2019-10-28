<p>Das BO Tarifinfo liefert die Merkmale, die einen Endkundentarif identifizierbar machen.
    Dieses BO dient als Basis für weitere BOs mit erweiterten Anwendungsmöglichkeiten.
</p>
<table>
    <thead>
    <tr>
        <th>Fachliches Attribut</th>
        <th>Bemerkung / Beispiel</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td><strong>Tarifinfo</strong></td>
        <td>
            abgeleitet von <a href="https://www.bo4e.de/dokumentation/geschaeftsobjekte/bo-geschaftsobjekt">BO Geschaeftsobjekt</a>
        </td>
    </tr>
    <tr>
        <td>bezeichnung</td>
        <td>Name des Tarifs</td>
    </tr>
    <tr>
        <td>anbietername</td>
        <td>Der Name des Marktpartners, der den Tarif anbietet</td>
    </tr>
    <tr>
        <td>sparte</td>
        <td>Strom oder Gas, etc.. Siehe <a href="https://www.bo4e.de/dokumentation/enumerations/enum-sparte">ENUM Sparte</a></td>
    </tr>
    <tr>
        <td>kundentyp<a href="https://hh-atlassian.enet.local/confluence/display/BO/ENUM+KundenTyp"></a></td>
        <td>Kundentyp für den der Tarif gilt, z.B. Privatkunde. Siehe <a href="https://www.bo4e.de/dokumentation/enumerations/enum-kundentyp">ENUM Kundentyp</a></td>
    </tr>
    <tr>
        <td>tarifart</td>
        <td>Die Art des Tarifes, z.B. Eintarif oder Mehrtarif. Siehe <a href="https://www.bo4e.de/dokumentation/enumerations/enum-tarifart">ENUM Tarifart</a></td>
    </tr>
    <tr>
        <td>tariftyp</td>
        <td>Hinweis auf den Tariftyp, z.B. Grundversorgung oder Sondertarif. Siehe <a href="https://www.bo4e.de/dokumentation/enumerations/enum-tariftyp">ENUM Tariftyp</a></td>
    </tr>
    <tr>
        <td>tarifmerkmal</td>
        <td>Weiteres Merkmal des Tarifs, z.B. Festpreis oder Vorkasse. Siehe <a href="https://www.bo4e.de/dokumentation/enumerations/enum-tarifmodell">ENUM Tarifmerkmal</a>
        </td>
    </tr>
    <tr>
        <td>website</td>
        <td>Internetseite auf dem der Tarif zu finden ist.</td>
    </tr>
    <tr>
        <td>anbieter</td>
        <td>Link zum Marktteilnehmer (Lieferant), der diesen Tarif anbietet. Details siehe <a href="https://www.bo4e.de/dokumentation/geschaeftsobjekte/bo-marktteilnehmer">BO Marktteilnehmer</a></td>
    </tr>
    <tr>
        <td>zeitlicheGueltigkeit</td>
        <td>Angabe, in welchem Zeitraum der Tarif gültig ist. Details siehe <a href="https://www.bo4e.de/dokumentation/komponenten/com-zeitraum">COM Zeitraum</a></td>
    </tr>
    <tr>
        <td>energiemix</td>
        <td>Der Energiemix, der für diesen Tarif gilt. Siehe <a href="https://www.bo4e.de/dokumentation/komponenten/com-energiemix">COM Energiemix</a></td>
    </tr>
    <tr>
        <td>vertragskonditionen</td>
        <td>Mindestlaufzeiten und Kündigungsfristen zusammengefasst. Details siehe <a href="https://www.bo4e.de/dokumentation/komponenten/com-vertragskonditionen">COM Vertragskonditionen</a></td>
    </tr>
    </tbody>
</table>

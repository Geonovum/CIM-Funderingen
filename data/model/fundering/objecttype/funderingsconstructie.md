<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">
<h2>Funderingsconstructie</h2>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een constructie die de belastingen van één of meer panden of delen ervan overdraagt aan de ondergrond, van één funderingstype is en als één samenhangend geheel is gerealiseerd.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/funderingsconstructie">https://definities.geostandaarden.nl/fundering/begrip/funderingsconstructie</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsconstructie.generalisatie-Constructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_nen3610_domein_semantisch_model_objecttype_constructie">Constructie (NEN 3610:2022 - Basismodel geo-informatie)</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_attribuutsoort_oorspronkelijke_technische_levensduur">oorspronkelijke technische levensduur</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Decimal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_attribuutsoort_aanlegniveau">aanlegniveau</a>
</td>
<td>
Niveau van de onderkant van het funderingselement t.o.v. een referentieniveau.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Decimal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_attribuutsoort_aanleghoogte">aanleghoogte</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Decimal</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht Relatiesoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_relatiesoort_draagt">draagt</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand">Pand</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_relatiesoort_draagt_panden_van">draagt panden van</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingseenheid">Funderingseenheid</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_relatiesoort_is_gekoppeld_aan">is gekoppeld aan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_attribuutsoort_oorspronkelijke_technische_levensduur">
<h6>oorspronkelijke technische levensduur</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsconstructie.oorspronkelijke%20technische%20levensduur</td>
</tr>
<tr>
<th>Naam</th>
<td>oorspronkelijke technische levensduur</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_attribuutsoort_aanlegniveau">
<h6>aanlegniveau</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsconstructie.aanlegniveau</td>
</tr>
<tr>
<th>Naam</th>
<td>aanlegniveau</td>
</tr>
<tr>
<th>Definitie</th>
<td>Niveau van de onderkant van het funderingselement t.o.v. een referentieniveau.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/aanlegniveau">https://definities.geostandaarden.nl/fundering/begrip/aanlegniveau</a></td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_attribuutsoort_aanleghoogte">
<h6>aanleghoogte</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsconstructie.aanleghoogte</td>
</tr>
<tr>
<th>Naam</th>
<td>aanleghoogte</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section class="notoc">
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_relatiesoort_draagt">
<h6>draagt</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsconstructie.draagt</td>
</tr>
<tr>
<th>Naam</th>
<td>draagt</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1..*</td>
</tr>
<tr>
<th>Kardinaliteit relatie bron</th>
<td>1..*</td>
</tr>
<tr>
<th>Unidirectioneel</th>
<td>Ja</td>
</tr>
<tr>
<th>Aggregatietype</th>
<td>Geen</td>
</tr>
<tr>
<th>Bron</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand">Pand</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_relatiesoort_draagt_panden_van">
<h6>draagt panden van</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsconstructie.draagt%20panden%20van</td>
</tr>
<tr>
<th>Naam</th>
<td>draagt panden van</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Kardinaliteit relatie bron</th>
<td>1</td>
</tr>
<tr>
<th>Unidirectioneel</th>
<td>Ja</td>
</tr>
<tr>
<th>Aggregatietype</th>
<td>Geen</td>
</tr>
<tr>
<th>Bron</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingseenheid">Funderingseenheid</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie_relatiesoort_is_gekoppeld_aan">
<h6>is gekoppeld aan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsconstructie.is%20gekoppeld%20aan</td>
</tr>
<tr>
<th>Naam</th>
<td>is gekoppeld aan</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>0..*</td>
</tr>
<tr>
<th>Kardinaliteit relatie bron</th>
<td>0..*</td>
</tr>
<tr>
<th>Unidirectioneel</th>
<td>Ja</td>
</tr>
<tr>
<th>Aggregatietype</th>
<td>Geen</td>
</tr>
<tr>
<th>Bron</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie">
<h3>Diepe funderingsconstructie</h3>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Diepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Diepe funderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Fundering in diepere lagen, ontleent draagkracht aan wrijving langs de schacht en weerstand van de paalpunt</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/diepe_fundering">https://definities.geostandaarden.nl/fundering/begrip/diepe_fundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Diepe%20funderingsconstructie.generalisatie-Funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie">Diepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie_attribuutsoort_diepte_paalvoet">diepte paalvoet</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Decimal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie_attribuutsoort_aantal_palen">aantal palen</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie_attribuutsoort_diepte_paalkop">diepte paalkop</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Decimal</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie_attribuutsoort_diepte_paalvoet">
<h6>diepte paalvoet</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Diepe%20funderingsconstructie.diepte%20paalvoet</td>
</tr>
<tr>
<th>Naam</th>
<td>diepte paalvoet</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie_attribuutsoort_aantal_palen">
<h6>aantal palen</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Diepe%20funderingsconstructie.aantal%20palen</td>
</tr>
<tr>
<th>Naam</th>
<td>aantal palen</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie_attribuutsoort_diepte_paalkop">
<h6>diepte paalkop</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Diepe%20funderingsconstructie.diepte%20paalkop</td>
</tr>
<tr>
<th>Naam</th>
<td>diepte paalkop</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie">
<h4>Houten paalfunderingsconstructie</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Houten paalfunderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Houten funderingspalen zijn in de woningbouw gebruikt tot ongeveer 1970. Houten palen zijn gevoelig voor aantasting onder meer door een te lage grondwaterstand.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/houten_paalfundering">https://definities.geostandaarden.nl/fundering/begrip/houten_paalfundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie.generalisatie-Diepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie">Houten paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie">Diepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_attribuutsoort_bovenkant_funderingshout">bovenkant funderingshout</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Decimal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_attribuutsoort_aanleghoogte_funderingshout">aanleghoogte funderingshout</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Decimal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_attribuutsoort_houttype">houttype</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_houttype">Houttype</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_attribuutsoort_bovenkant_funderingshout">
<h6>bovenkant funderingshout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie.bovenkant%20funderingshout</td>
</tr>
<tr>
<th>Naam</th>
<td>bovenkant funderingshout</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_attribuutsoort_aanleghoogte_funderingshout">
<h6>aanleghoogte funderingshout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie.aanleghoogte%20funderingshout</td>
</tr>
<tr>
<th>Naam</th>
<td>aanleghoogte funderingshout</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_attribuutsoort_houttype">
<h6>houttype</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie.houttype</td>
</tr>
<tr>
<th>Naam</th>
<td>houttype</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie">
<h5>Amsterdamse paalfunderingsconstructie</h5>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Amsterdamse%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Amsterdamse paalfunderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een Amsterdamse fundering is een type houten paalfundering bestaande uit een gemetselde muur met versnijdingen, waaronder langshout en kespen. Onder een kesp staan steeds twee houten palen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/amsterdamse_paalfundering">https://definities.geostandaarden.nl/fundering/begrip/amsterdamse_paalfundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Amsterdamse%20paalfunderingsconstructie.generalisatie-Houten%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie">Amsterdamse paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie">Houten paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_kesp">materiaal kesp</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_schuifhout">materiaal schuifhout</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_langshout">materiaal langshout</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_kesp">
<h6>materiaal kesp</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Amsterdamse%20paalfunderingsconstructie.materiaal%20kesp</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaal kesp</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_schuifhout">
<h6>materiaal schuifhout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Amsterdamse%20paalfunderingsconstructie.materiaal%20schuifhout</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaal schuifhout</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_langshout">
<h6>materiaal langshout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Amsterdamse%20paalfunderingsconstructie.materiaal%20langshout</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaal langshout</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie">
<h5>Rotterdamse paalfunderingsconstructie</h5>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Rotterdamse%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Rotterdamse paalfunderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>
Een Rotterdamse fundering is een type houten paalfundering bestaande uit een gemetselde muur, gewoonlijk zonder versnijdingen, waaronder langshout bestaande uit een plaat (hier ook wel kesp genoemd) met in het midden daarop een balkje (schuifhout) en een enkele rij houten palen er onder.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/rotterdamse_paalfundering">https://definities.geostandaarden.nl/fundering/begrip/rotterdamse_paalfundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Rotterdamse%20paalfunderingsconstructie.generalisatie-Houten%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie">Rotterdamse paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie">Houten paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_schuifhout">materiaal schuifhout</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_langshout">materiaal langshout</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_kesp">materiaal kesp</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_materiaal">Materiaal</a>
</td>
<td>
0...1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_schuifhout">
<h6>materiaal schuifhout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Rotterdamse%20paalfunderingsconstructie.materiaal%20schuifhout</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaal schuifhout</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_langshout">
<h6>materiaal langshout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Rotterdamse%20paalfunderingsconstructie.materiaal%20langshout</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaal langshout</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie_attribuutsoort_materiaal_kesp">
<h6>materiaal kesp</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Rotterdamse%20paalfunderingsconstructie.materiaal%20kesp</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaal kesp</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>0...1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonkop">
<h5>Houten paalfunderingsconstructie met betonkop</h5>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie%20met%20betonkop</td>
</tr>
<tr>
<th>Naam</th>
<td>Houten paalfunderingsconstructie met betonkop</td>
</tr>
<tr>
<th>Definitie</th>
<td>Bij houten paalfunderingen kan de overgang tussen paal en funderingsbalk kwetsbaar zijn, vooral als deze zich rond de grondwaterlijn bevindt. Zodra het hout afwisselend nat en droog wordt, kan rotting optreden. Om dit te voorkomen, werd vanaf het einde van de 19e eeuw, soms een betonnen kop op de houten paal aangebracht. Deze betonkop fungeert als een beschermende laag. De houten paal blijft hierbij onder water, terwijl de betonkop de bovenzijde van het hout afsluit tegen zuurstof en vochtwisselingen. Deze methode werd tot halverwege de 20e eeuw veel toegepast bij nieuwbouw op houten palen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/houten_paalfundering_met_betonkop">https://definities.geostandaarden.nl/fundering/begrip/houten_paalfundering_met_betonkop</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie%20met%20betonkop.generalisatie-Houten%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonkop">Houten paalfunderingsconstructie met betonkop</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie">Houten paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonkop_attribuutsoort_betontype">betontype</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_betontype">Betontype</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonkop_attribuutsoort_betontype">
<h6>betontype</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie%20met%20betonkop.betontype</td>
</tr>
<tr>
<th>Naam</th>
<td>betontype</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonoplanger">
<h5>Houten paalfunderingsconstructie met betonoplanger</h5>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie%20met%20betonoplanger</td>
</tr>
<tr>
<th>Naam</th>
<td>Houten paalfunderingsconstructie met betonoplanger</td>
</tr>
<tr>
<th>Definitie</th>
<td>Bij een houten paal met betonoplanger steekt het funderingshout 5 tot 10 cm in de betonoplanger. Betonoplangers zijn gebruikt in de periode 1930 – 1970. In eerste instantie ging het om metselwerk te besparen. Later zijn langere betonoplangers gebruikt waardoor het hoogste funderingshout dieper in het grondwater kwam te staan.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/houten_paalfundering_met_betonoplanger">https://definities.geostandaarden.nl/fundering/begrip/houten_paalfundering_met_betonoplanger</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie%20met%20betonoplanger.generalisatie-Houten%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonoplanger">Houten paalfunderingsconstructie met betonoplanger</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie">Houten paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonoplanger_attribuutsoort_betontype">betontype</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_betontype">Betontype</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonoplanger_attribuutsoort_betontype">
<h6>betontype</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houten%20paalfunderingsconstructie%20met%20betonoplanger.betontype</td>
</tr>
<tr>
<th>Naam</th>
<td>betontype</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

</section>
</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_betonnen_paalfunderingsconstructie">
<h4>Betonnen paalfunderingsconstructie</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Betonnen%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Betonnen paalfunderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Vanaf 1970 zijn in de woningbouw betonnen palen gebruikt. Funderingsproblemen bij betonpalen komen relatief weinig voor, maar als deze er zijn heeft dat meestal te maken met een tekort aan draagvermogen veroorzaakt door constructieve problemen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/betonnen_paalfundering">https://definities.geostandaarden.nl/fundering/begrip/betonnen_paalfundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Betonnen%20paalfunderingsconstructie.generalisatie-Diepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_betonnen_paalfunderingsconstructie">Betonnen paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie">Diepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_betonnen_paalfunderingsconstructie_attribuutsoort_betontype">betontype</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_betontype">Betontype</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_betonnen_paalfunderingsconstructie_attribuutsoort_betontype">
<h6>betontype</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Betonnen%20paalfunderingsconstructie.betontype</td>
</tr>
<tr>
<th>Naam</th>
<td>betontype</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_staalbuizen_paalfunderingsconstructie">
<h4>Staalbuizen paalfunderingsconstructie</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Staalbuizen%20paalfunderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Staalbuizen paalfunderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Stalen buispalen worden gebruikt om bij gebleken funderingsproblemen  een nieuwe fundering onder een bestaande woning aan te brengen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/staalbuizen_paalfundering">https://definities.geostandaarden.nl/fundering/begrip/staalbuizen_paalfundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Staalbuizen%20paalfunderingsconstructie.generalisatie-Diepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_staalbuizen_paalfunderingsconstructie">Staalbuizen paalfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_diepe_funderingsconstructie">Diepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

</section>
</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie">
<h3>Ondiepe funderingsconstructie</h3>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Ondiepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Ondiepe funderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Ondiepe fundering is de wijze van funderen waarbij de krachten uit een fundatieblok of -sloof direct worden overgedragen op de draagkrachtige ondergrond.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/ondiepe_fundering">https://definities.geostandaarden.nl/fundering/begrip/ondiepe_fundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Ondiepe%20funderingsconstructie.generalisatie-Funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie">Ondiepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie_attribuutsoort_betontype">betontype</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_betontype">Betontype</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie_attribuutsoort_afmeting_ondiepe_funderingsconstructie">afmeting ondiepe funderingsconstructie</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Object"> GM_Object</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie_attribuutsoort_betontype">
<h6>betontype</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Ondiepe%20funderingsconstructie.betontype</td>
</tr>
<tr>
<th>Naam</th>
<td>betontype</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie_attribuutsoort_afmeting_ondiepe_funderingsconstructie">
<h6>afmeting ondiepe funderingsconstructie</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Ondiepe%20funderingsconstructie.afmeting%20ondiepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>afmeting ondiepe funderingsconstructie</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering_op_funderingsconstructie">
<h4>Fundering op funderingsconstructie</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Fundering%20op%20funderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Fundering op funderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een slietenfundering is een historische funderingswijze waarbij dunne houten stammetjes (slieten) dicht tegen elkaar verticaal in een zachte of drassige grond werden geslagen om de draagkracht te vergroten</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/fundering_op_slieten">https://definities.geostandaarden.nl/fundering/begrip/fundering_op_slieten</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Fundering%20op%20funderingsconstructie.generalisatie-Ondiepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering_op_funderingsconstructie">Fundering op funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie">Ondiepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_strokenfunderingsconstructie">
<h4>Strokenfunderingsconstructie</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Strokenfunderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Strokenfunderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een strokenfundering is een fundering op staal in de vorm van strookvormige elementen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/strokenfundering">https://definities.geostandaarden.nl/fundering/begrip/strokenfundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Strokenfunderingsconstructie.generalisatie-Ondiepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_strokenfunderingsconstructie">Strokenfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie">Ondiepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_strokenfunderingsconstructie_attribuutsoort_vorstrand">vorstrand</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_strokenfunderingsconstructie_attribuutsoort_vorstrand">
<h6>vorstrand</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Strokenfunderingsconstructie.vorstrand</td>
</tr>
<tr>
<th>Naam</th>
<td>vorstrand</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_plaatfunderingsconstructie">
<h4>Plaatfunderingsconstructie</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Plaatfunderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Plaatfunderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een plaatfundering bestaat uit een doorlopende gewapende betonplaat onder het gehele gebouw, waardoor het gewicht gelijkmatig over de ondergrond wordt verdeeld. Dit type kan geschikt zijn voor zowel lichte als zwaardere gebouwen, mits de bodem voldoende draagkracht heeft. Op matig draagkrachtige grond kan het een alternatief zijn voor strokenfunderingen. Voor zeer slappe grond is echter meestal een paalfundering nodig.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/Plaatfundering">https://definities.geostandaarden.nl/fundering/begrip/Plaatfundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Plaatfunderingsconstructie.generalisatie-Ondiepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_plaatfunderingsconstructie">Plaatfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie">Ondiepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_plaatfunderingsconstructie_attribuutsoort_vorstrand">vorstrand</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Boolean</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_plaatfunderingsconstructie_attribuutsoort_vorstrand">
<h6>vorstrand</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Plaatfunderingsconstructie.vorstrand</td>
</tr>
<tr>
<th>Naam</th>
<td>vorstrand</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_poerenfunderingsconstructie">
<h4>Poerenfunderingsconstructie</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Poerenfunderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Poerenfunderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>Het gebruik van betonnen blokken als fundering.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/poerenfundering">https://definities.geostandaarden.nl/fundering/begrip/poerenfundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Poerenfunderingsconstructie.generalisatie-Ondiepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_poerenfunderingsconstructie">Poerenfunderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie">Ondiepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_getrapte_funderingsconstructie">
<h4>Getrapte funderingsconstructie</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Getrapte%20funderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Getrapte funderingsconstructie</td>
</tr>
<tr>
<th>Definitie</th>
<td>De getrapte of gemetselde fundering is een traditionele vorm van funderen op staal, vaak bestaande uit een verbrede voet van baksteen of natuursteen, gemetseld in kalk- of cementmortel. Dit type fundering werd veel toegepast bij oude boerderijen en andere gebouwen van vóór de twintigste eeuw. In ons werk komen we deze nog vaak tegen bij renovaties of verbouwingen, bijvoorbeeld wanneer een boerderij wordt omgebouwd tot woonhuis. Door inklinking van de grond of uitspoeling kan verzakking bij dit type fundering relatief vaak voorkomen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/getrapte_fundering">https://definities.geostandaarden.nl/fundering/begrip/getrapte_fundering</a></td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Getrapte%20funderingsconstructie.generalisatie-Ondiepe%20funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_getrapte_funderingsconstructie">Getrapte funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_ondiepe_funderingsconstructie">Ondiepe funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

</section>
</section>
</section>

## Fundering {#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20A:Fundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Fundering</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/fundering">https://definities.geostandaarden.nl/fundering/begrip/fundering</a></td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20A:Fundering.generalisatie-Constructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering">Fundering</a>
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
<h3>Overzicht attribuutsoorten</h3>    
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_attribuutsoort_oorspronkelijke_technische_levensduur">oorspronkelijke technische levensduur</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_attribuutsoort_aanlegniveau">aanlegniveau</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_attribuutsoort_aanleghoogte">aanleghoogte</a>
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
<h3>Overzicht Relatiesoorten</h3>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_relatiesoort_draagt">draagt</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_pand">Pand</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_relatiesoort_draagt_panden_van">draagtPandenVan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_funderingseenheid">Funderingseenheid</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details attribuutsoorten</h3>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_attribuutsoort_oorspronkelijke_technische_levensduur">
<h4>oorspronkelijke technische levensduur</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20A:Fundering.oorspronkelijke%20technische%20levensduur</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_attribuutsoort_aanlegniveau">
<h4>aanlegniveau</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20A:Fundering.aanlegniveau</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_attribuutsoort_aanleghoogte">
<h4>aanleghoogte</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20A:Fundering.aanleghoogte</td>
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
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_relatiesoort_draagt">
<h4>draagt</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20A:Fundering.draagt</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering">Fundering</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_pand">Pand</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering_relatiesoort_draagt_panden_van">
<h4>draagtPandenVan</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20A:Fundering.draagtPandenVan</td>
</tr>
<tr>
<th>Naam</th>
<td>draagtPandenVan</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_fundering">Fundering</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_a_objecttype_funderingseenheid">Funderingseenheid</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

![Funderingstype](data/model/cim-fundering-a/objecttype/fundering.funderingstype.png "Funderingstype")

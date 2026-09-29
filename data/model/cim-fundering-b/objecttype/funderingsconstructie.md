<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">
<h2>Funderingsconstructie</h2>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Funderingsconstructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingsconstructie</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Funderingsconstructie.generalisatie-Constructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">Funderingsconstructie</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_attribuutsoort_oorspronkelijke_technische_levensduur">oorspronkelijke technische levensduur</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_attribuutsoort_aanlegniveau">aanlegniveau</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_attribuutsoort_aanleghoogte">aanleghoogte</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_relatiesoort_draagt">draagt</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_pand">Pand</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_relatiesoort_draagt_panden_van">draagtPandenVan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingseenheid">Funderingseenheid</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_relatiesoort_is_gekoppeld_aan">isGekoppeldAan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_attribuutsoort_oorspronkelijke_technische_levensduur">
<h6>oorspronkelijke technische levensduur</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Funderingsconstructie.oorspronkelijke%20technische%20levensduur</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_attribuutsoort_aanlegniveau">
<h6>aanlegniveau</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Funderingsconstructie.aanlegniveau</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_attribuutsoort_aanleghoogte">
<h6>aanleghoogte</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Funderingsconstructie.aanleghoogte</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_relatiesoort_draagt">
<h6>draagt</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Funderingsconstructie.draagt</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_pand">Pand</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_relatiesoort_draagt_panden_van">
<h6>draagtPandenVan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Funderingsconstructie.draagtPandenVan</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingseenheid">Funderingseenheid</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie_relatiesoort_is_gekoppeld_aan">
<h6>isGekoppeldAan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Funderingsconstructie.isGekoppeldAan</td>
</tr>
<tr>
<th>Naam</th>
<td>isGekoppeldAan</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_diepe_fundering">
<h3>Diepe Fundering</h3>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Diepe%20Fundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Diepe Fundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Diepe%20Fundering.generalisatie-Funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_diepe_fundering">Diepe Fundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">Funderingsconstructie</a>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering">
<h4>Paalfundering</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Paalfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Paalfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Paalfundering.generalisatie-Diepe%20Fundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering">Paalfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_diepe_fundering">Diepe Fundering</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering_attribuutsoort_aantal_palen">aantalPalen</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering_attribuutsoort_materiaal_paal">materiaalPaal</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_enumeratie_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering_attribuutsoort_diepte_paalkop">dieptePaalkop</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering_attribuutsoort_diepte_paalvoet">dieptePaalvoet</a>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering_attribuutsoort_aantal_palen">
<h6>aantalPalen</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Paalfundering.aantalPalen</td>
</tr>
<tr>
<th>Naam</th>
<td>aantalPalen</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering_attribuutsoort_materiaal_paal">
<h6>materiaalPaal</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Paalfundering.materiaalPaal</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaalPaal</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering_attribuutsoort_diepte_paalkop">
<h6>dieptePaalkop</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Paalfundering.dieptePaalkop</td>
</tr>
<tr>
<th>Naam</th>
<td>dieptePaalkop</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering_attribuutsoort_diepte_paalvoet">
<h6>dieptePaalvoet</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Paalfundering.dieptePaalvoet</td>
</tr>
<tr>
<th>Naam</th>
<td>dieptePaalvoet</td>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering">
<h5>Houten paalfundering</h5>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Houten%20paalfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Houten paalfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Houten%20paalfundering.generalisatie-Paalfundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering">Houten paalfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering">Paalfundering</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering_attribuutsoort_bovenkant_funderingshout">bovenkant funderingshout</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering_attribuutsoort_aanleghoogte_funderingshout">aanleghoogteFunderingshout</a>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering_attribuutsoort_bovenkant_funderingshout">
<h6>bovenkant funderingshout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Houten%20paalfundering.bovenkant%20funderingshout</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering_attribuutsoort_aanleghoogte_funderingshout">
<h6>aanleghoogteFunderingshout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Houten%20paalfundering.aanleghoogteFunderingshout</td>
</tr>
<tr>
<th>Naam</th>
<td>aanleghoogteFunderingshout</td>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_amsterdamse_paalfundering">
<h6>Amsterdamse paalfundering</h6>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Amsterdamse%20paalfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Amsterdamse paalfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Amsterdamse%20paalfundering.generalisatie-Houten%20paalfundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_amsterdamse_paalfundering">Amsterdamse paalfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering">Houten paalfundering</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_amsterdamse_paalfundering_attribuutsoort_materiaal_kesp">materiaalKesp</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_enumeratie_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_amsterdamse_paalfundering_attribuutsoort_materiaal_schuifhout">materiaalSchuifhout</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_enumeratie_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_amsterdamse_paalfundering_attribuutsoort_materiaal_langshout">materiaalLangshout</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_enumeratie_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_amsterdamse_paalfundering_attribuutsoort_materiaal_kesp">
<h6>materiaalKesp</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Amsterdamse%20paalfundering.materiaalKesp</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaalKesp</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_amsterdamse_paalfundering_attribuutsoort_materiaal_schuifhout">
<h6>materiaalSchuifhout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Amsterdamse%20paalfundering.materiaalSchuifhout</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaalSchuifhout</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_amsterdamse_paalfundering_attribuutsoort_materiaal_langshout">
<h6>materiaalLangshout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Amsterdamse%20paalfundering.materiaalLangshout</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaalLangshout</td>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_rotterdamse_paalfundering">
<h6>Rotterdamse paalfundering</h6>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Rotterdamse%20paalfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Rotterdamse paalfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Rotterdamse%20paalfundering.generalisatie-Houten%20paalfundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_rotterdamse_paalfundering">Rotterdamse paalfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering">Houten paalfundering</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_rotterdamse_paalfundering_attribuutsoort_materiaal_schuifhout">materiaalSchuifhout</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_enumeratie_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_rotterdamse_paalfundering_attribuutsoort_materiaal_langshout">materiaalLangshout</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_enumeratie_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_rotterdamse_paalfundering_attribuutsoort_materiaal_kesp">materiaalKesp</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_enumeratie_materiaal">Materiaal</a>
</td>
<td>
0...1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_rotterdamse_paalfundering_attribuutsoort_materiaal_schuifhout">
<h6>materiaalSchuifhout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Rotterdamse%20paalfundering.materiaalSchuifhout</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaalSchuifhout</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_rotterdamse_paalfundering_attribuutsoort_materiaal_langshout">
<h6>materiaalLangshout</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Rotterdamse%20paalfundering.materiaalLangshout</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaalLangshout</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_rotterdamse_paalfundering_attribuutsoort_materiaal_kesp">
<h6>materiaalKesp</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Rotterdamse%20paalfundering.materiaalKesp</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaalKesp</td>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering_met_betonkop">
<h6>Houten paalfundering met betonkop</h6>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Houten%20paalfundering%20met%20betonkop</td>
</tr>
<tr>
<th>Naam</th>
<td>Houten paalfundering met betonkop</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Houten%20paalfundering%20met%20betonkop.generalisatie-Houten%20paalfundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering_met_betonkop">Houten paalfundering met betonkop</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering">Houten paalfundering</a>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering_met_betonoplanger">
<h6>Houten paalfundering met betonoplanger</h6>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Houten%20paalfundering%20met%20betonoplanger</td>
</tr>
<tr>
<th>Naam</th>
<td>Houten paalfundering met betonoplanger</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Houten%20paalfundering%20met%20betonoplanger.generalisatie-Houten%20paalfundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering_met_betonoplanger">Houten paalfundering met betonoplanger</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_houten_paalfundering">Houten paalfundering</a>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_betonnen_paalfundering">
<h5>Betonnen paalfundering</h5>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Betonnen%20paalfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Betonnen paalfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Betonnen%20paalfundering.generalisatie-Paalfundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_betonnen_paalfundering">Betonnen paalfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering">Paalfundering</a>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_staalbuizen_paalfundering">
<h5>Staalbuizen paalfundering</h5>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Staalbuizen%20paalfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Staalbuizen paalfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Staalbuizen%20paalfundering.generalisatie-Paalfundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_staalbuizen_paalfundering">Staalbuizen paalfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_paalfundering">Paalfundering</a>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering">
<h3>Ondiepe Fundering</h3>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Ondiepe%20Fundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Ondiepe Fundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Ondiepe%20Fundering.generalisatie-Funderingsconstructie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering">Ondiepe Fundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_funderingsconstructie">Funderingsconstructie</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering_attribuutsoort_materiaal_ondiepe_fundering">materiaalOndiepeFundering</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_enumeratie_materiaal">Materiaal</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering_attribuutsoort_afmeting_ondiepe_fundering">afmetingOndiepeFundering</a>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering_attribuutsoort_materiaal_ondiepe_fundering">
<h6>materiaalOndiepeFundering</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Ondiepe%20Fundering.materiaalOndiepeFundering</td>
</tr>
<tr>
<th>Naam</th>
<td>materiaalOndiepeFundering</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering_attribuutsoort_afmeting_ondiepe_fundering">
<h6>afmetingOndiepeFundering</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Ondiepe%20Fundering.afmetingOndiepeFundering</td>
</tr>
<tr>
<th>Naam</th>
<td>afmetingOndiepeFundering</td>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_fundering_op_slieten">
<h4>Fundering op slieten</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Fundering%20op%20slieten</td>
</tr>
<tr>
<th>Naam</th>
<td>Fundering op slieten</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Fundering%20op%20slieten.generalisatie-Ondiepe%20Fundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_fundering_op_slieten">Fundering op slieten</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering">Ondiepe Fundering</a>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_strokenfundering">
<h4>Strokenfundering</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Strokenfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Strokenfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Strokenfundering.generalisatie-Ondiepe%20Fundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_strokenfundering">Strokenfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering">Ondiepe Fundering</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_strokenfundering_attribuutsoort_vorstrand">vorstrand</a>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_strokenfundering_attribuutsoort_vorstrand">
<h6>vorstrand</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Strokenfundering.vorstrand</td>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_plaatfundering">
<h4>Plaatfundering</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Plaatfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Plaatfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Plaatfundering.generalisatie-Ondiepe%20Fundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_plaatfundering">Plaatfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering">Ondiepe Fundering</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_plaatfundering_attribuutsoort_vorstrand">vorstrand</a>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_plaatfundering_attribuutsoort_vorstrand">
<h6>vorstrand</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Plaatfundering.vorstrand</td>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_poerenfundering">
<h4>Poerenfundering</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Poerenfundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Poerenfundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Poerenfundering.generalisatie-Ondiepe%20Fundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_poerenfundering">Poerenfundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering">Ondiepe Fundering</a>
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

<section id="informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_getrapte_fundering">
<h4>Getrapte fundering</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Getrapte%20fundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Getrapte fundering</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:CIM%20Fundering%20B:Getrapte%20fundering.generalisatie-Ondiepe%20Fundering</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_getrapte_fundering">Getrapte fundering</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_cim_fundering_b_objecttype_ondiepe_fundering">Ondiepe Fundering</a>
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

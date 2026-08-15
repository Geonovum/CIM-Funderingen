# Informatiemodel CIM - Funderingen
## View Gebouwtypologie

![View Gebouwtypologie](data/model/gebouwtypologie/package-view.png "View Gebouwtypologie")

### Objecttypen

#### Pand {#informatiemodel_informatiemodel_funderingen_view_gebouwtypologie_objecttype_pand}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Gebouwtypologie:Pand</td>
</tr>
<tr>
<th>Naam</th>
<td>Pand</td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:Gebouwtypologie:Pand.generalisatie-Gebouw</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_view_gebouwtypologie_objecttype_pand">Pand</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_nen3610_domein_semantisch_model_objecttype_gebouw">Gebouw (NEN 3610:2022 - Basismodel geo-informatie)</a>
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
<h5>Overzicht Externe koppelingen</h5>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_view_gebouwtypologie_objecttype_pand_externe_koppeling_is_gelijk_aan">isGelijkAan</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_imbag_domein_objecten_objecttype_pand">Pand (cimbag_lv_dummy)</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_view_gebouwtypologie_objecttype_pand_externe_koppeling_heeft_pand">heeftPand</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_imwoz_domein_woz_objecttype_woz_object">WOZObject (imwoz_dummy)</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details Externe koppelingen</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_view_gebouwtypologie_objecttype_pand_externe_koppeling_is_gelijk_aan">
<h6>isGelijkAan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Gebouwtypologie:Pand.isGelijkAan</td>
</tr>
<tr>
<th>Naam</th>
<td>isGelijkAan</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_view_gebouwtypologie_objecttype_pand">Pand</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_imbag_domein_objecten_objecttype_pand">Pand (cimbag_lv_dummy)</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_view_gebouwtypologie_objecttype_pand_externe_koppeling_heeft_pand">
<h6>heeftPand</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Gebouwtypologie:Pand.heeftPand</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftPand</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_view_gebouwtypologie_objecttype_pand">Pand</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_imwoz_domein_woz_objecttype_woz_object">WOZObject (imwoz_dummy)</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

## Domein Fundering

![Domein Fundering](data/model/fundering/package-view.png "Domein Fundering")

### Objecttypen

#### Pand {#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Pand</td>
</tr>
<tr>
<th>Naam</th>
<td>Pand</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Gebaseerd op definitie “pand” in artikel 1 Wet basisregistratie adressen en gebouwen</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/id/begrippenkader/Pand">https://definities.geostandaarden.nl/fundering/id/begrippenkader/Pand</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-08-11</td>
</tr>
<tbody>
</tbody>
</table>

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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_attribuutsoort_bag_id">BAG-ID</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_attribuutsoort_geo_test">geo-test</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_nen3610_domein_waardelijsten_codelijst_void_reason_value">VoidReasonValue (NEN 3610:2022 - Basismodel geo-informatie)</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Overzicht gegevensgroepen</h5>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_gegevensgroep_funderingsgegevens">Funderingsgegevens</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens">Funderingsgegevens</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_gegevensgroep_funderingsgegevens">
<h6>Funderingsgegevens</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Pand.Funderingsgegevens</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingsgegevens</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section class="notoc">
<h5>Details gegevensgroepen</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_gegevensgroep_funderingsgegevens">
<h6>Funderingsgegevens</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Pand.Funderingsgegevens</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingsgegevens</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

### Gegevensgroeptypen

#### Funderingsgegevens {#informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsgegevens</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingsgegevens</td>
</tr>
<tbody>
</tbody>
</table>

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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_aanlegniveau">Aanlegniveau </a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_funderingstype">Funderingstype</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_funderingstype">Funderingstype</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_oorspronkelijke_levensduur">Oorspronkelijke Levensduur</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_funderingstekening_bouwtekening_">Funderingstekening/bouwtekening?</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> URI</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_funderingsdiepte">Funderingsdiepte</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_aantal_palen">aantalPalen</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Integer</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_aanlegniveau">
<h6>Aanlegniveau </h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsgegevens.Aanlegniveau%20</td>
</tr>
<tr>
<th>Naam</th>
<td>Aanlegniveau </td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_funderingstype">
<h6>Funderingstype</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsgegevens.Funderingstype</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingstype</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_oorspronkelijke_levensduur">
<h6>Oorspronkelijke Levensduur</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsgegevens.Oorspronkelijke%20Levensduur</td>
</tr>
<tr>
<th>Naam</th>
<td>Oorspronkelijke Levensduur</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_funderingstekening_bouwtekening_">
<h6>Funderingstekening/bouwtekening?</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsgegevens.Funderingstekening%2Fbouwtekening%3F</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingstekening/bouwtekening?</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_funderingsdiepte">
<h6>Funderingsdiepte</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsgegevens.Funderingsdiepte</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingsdiepte</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_gegevensgroeptype_funderingsgegevens_attribuutsoort_aantal_palen">
<h6>aantalPalen</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingsgegevens.aantalPalen</td>
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
</section>

### Enumeraties

#### Funderingstype {#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_funderingstype}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingstype</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingstype</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht waarden</h5>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 75%"></colgroup>
<tbody>
<tr>
  <th>Waarde</th>
  <th>Definitie</th>
</tr>
<tr>
<td>
Diepe fundering</td>
<td>
</td>
<tr>
<td>
Ondiepe fundering</td>
<td>
</td>
</tbody>
</table>

</section>

### Codelijsten

#### funderingType {#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_fundering_type}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:funderingType</td>
</tr>
<tr>
<th>Naam</th>
<td>funderingType</td>
</tr>
<tbody>
</tbody>
</table>

## Domein Omgeving
## Domein Risico
## Extern BAG

![Extern BAG](data/model/bag/package-view.png "Extern BAG")

### Objecttypen

#### Pand {#informatiemodel_imbag_domein_objecten_objecttype_pand}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.kadaster.nl/imbag/Pand</td>
</tr>
<tr>
<th>Naam</th>
<td>Pand</td>
</tr>
<tr>
<th>Herkomst</th>
<td>BAG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</td>
</tr>
<tbody>
</tbody>
</table>

#### Verblijfsobject {#informatiemodel_imbag_domein_objecten_objecttype_verblijfsobject}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.kadaster.nl/imbag/Verblijfsobject</td>
</tr>
<tr>
<th>Naam</th>
<td>Verblijfsobject</td>
</tr>
<tr>
<th>Herkomst</th>
<td>BAG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Kleinste binnen één of meer panden gelegen en voor woon-, bedrijfsmatige, of recreatieve doeleinden geschikte eenheid van gebruik die ontsloten wordt via een eigen afsluitbare toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte, onderwerp kan zijn van goederenrechtelijke rechtshandelingen en in functioneel opzicht zelfstandig is.</td>
</tr>
<tbody>
</tbody>
</table>

### Enumeraties

#### TypeAdresseerbaarObject {#informatiemodel_imbag_domein_objecten_enumeratie_type_adresseerbaar_object}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.kadaster.nl/imbag/TypeAdresseerbaarObject</td>
</tr>
<tr>
<th>Naam</th>
<td>TypeAdresseerbaarObject</td>
</tr>
<tbody>
</tbody>
</table>

## Extern BRO
## Extern NEN3610

![Extern NEN3610](data/model/nen3610/package-view.png "Extern NEN3610")

### Objecttypen

#### GeoObject {#informatiemodel_nen3610_domein_semantisch_model_objecttype_geo_object}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#GeoObject</td>
</tr>
<tr>
<th>Naam</th>
<td>GeoObject</td>
</tr>
<tr>
<th>Alias</th>
<td>Geo-object</td>
</tr>
<tr>
<th>Herkomst</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een fenomeen in de werkelijkheid dat direct of indirect is geassocieerd met een locatie relatief ten opzichte van de aarde.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Datum opname</th>
<td>20220601</td>
</tr>
<tbody>
</tbody>
</table>

#### ReeelObject {#informatiemodel_nen3610_domein_semantisch_model_objecttype_reeel_object}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#ReeelObject</td>
</tr>
<tr>
<th>Naam</th>
<td>ReeelObject</td>
</tr>
<tr>
<th>Alias</th>
<td>Reëel object</td>
</tr>
<tr>
<th>Herkomst</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geo-object dat zich geheel materieel manifesteert.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Datum opname</th>
<td>20220601</td>
</tr>
<tbody>
</tbody>
</table>

#### Constructie {#informatiemodel_nen3610_domein_semantisch_model_objecttype_constructie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#Constructie</td>
</tr>
<tr>
<th>Naam</th>
<td>Constructie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gebouwd object dat direct of indirect met de bodem is verbonden en bedoeld is om ter plaatse te functioneren.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Datum opname</th>
<td>20220601</td>
</tr>
<tbody>
</tbody>
</table>

#### Gebouw {#informatiemodel_nen3610_domein_semantisch_model_objecttype_gebouw}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#Gebouw</td>
</tr>
<tr>
<th>Naam</th>
<td>Gebouw</td>
</tr>
<tr>
<th>Alias</th>
<td>Gebouw</td>
</tr>
<tr>
<th>Herkomst</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Definitie</th>
<td>Overdekte en geheel of gedeeltelijk met wanden omsloten constructie bedoeld voor het in een afgeschermde omgeving onderbrengen van mensen, dieren of voorwerpen of voor de productie van goederen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Datum opname</th>
<td>20220601</td>
</tr>
<tbody>
</tbody>
</table>

## Extern BRK
## Extern WOZ


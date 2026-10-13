# Informatiemodel CIM - Funderingen

![Pandtypologie](data/model/pandtypologie.png "Pandtypologie")

![Funderingstype](data/model/funderingstype.png "Funderingstype")

## Domein Fundering

![mim:Domein Fundering](data/model/fundering/package-view.png "mim:Domein Fundering")

### Objecttypen

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand">
<h4>Pand</h4>

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
<th>Definitie</th>
<td>Een pand is een kleinste bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/Pand">https://definities.geostandaarden.nl/fundering/begrip/Pand</a></td>
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
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Pand.generalisatie-Pand</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand">Pand</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_imbag_domein_objecten_objecttype_pand">Pand (IMBAG)</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_attribuutsoort_bouwtekening">bouwtekening</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_datatypenoverig_URL"> URL</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_attribuutsoort_pandtype">pandtype</a>
</td>
<td>
Classificatie van een pand op basis van de bouwkundige verschijningsvorm en de constructieve samenhang met omliggende panden.</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_pandtype_nog_te_vervangen">Pandtype - nog te vervangen</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_attribuutsoort_bouwtekening">
<h6>bouwtekening</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Pand.bouwtekening</td>
</tr>
<tr>
<th>Naam</th>
<td>bouwtekening</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand_attribuutsoort_pandtype">
<h6>pandtype</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Pand.pandtype</td>
</tr>
<tr>
<th>Naam</th>
<td>pandtype</td>
</tr>
<tr>
<th>Definitie</th>
<td>Classificatie van een pand op basis van de bouwkundige verschijningsvorm en de constructieve samenhang met omliggende panden.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/id/begrippenkader/Pandtype">https://definities.geostandaarden.nl/fundering/id/begrippenkader/Pandtype</a></td>
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

![Pandtypologie](data/model/fundering/objecttype/pand.pandtypologie.png "Pandtypologie")

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">
<h4>Funderingsconstructie</h4>

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
<h5>Diepe funderingsconstructie</h5>

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
<h6>Houten paalfunderingsconstructie</h6>

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

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_amsterdamse_paalfunderingsconstructie" class="notoc">
<h6>Amsterdamse paalfunderingsconstructie</h6>

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

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_rotterdamse_paalfunderingsconstructie" class="notoc">
<h6>Rotterdamse paalfunderingsconstructie</h6>

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

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonkop" class="notoc">
<h6>Houten paalfunderingsconstructie met betonkop</h6>

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

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_houten_paalfunderingsconstructie_met_betonoplanger" class="notoc">
<h6>Houten paalfunderingsconstructie met betonoplanger</h6>

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
<h6>Betonnen paalfunderingsconstructie</h6>

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
<h6>Staalbuizen paalfunderingsconstructie</h6>

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
<h5>Ondiepe funderingsconstructie</h5>

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
<h6>Fundering op funderingsconstructie</h6>

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
<h6>Strokenfunderingsconstructie</h6>

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
<h6>Plaatfunderingsconstructie</h6>

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
<h6>Poerenfunderingsconstructie</h6>

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
<h6>Getrapte funderingsconstructie</h6>

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

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingseenheid">
<h4>Funderingseenheid</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingseenheid</td>
</tr>
<tr>
<th>Naam</th>
<td>Funderingseenheid</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een cluster van één of meer panden, waarbij voor een cluster dat meerdere panden omvat de belastingen van één of meer panden in het cluster geheel of gedeeltelijk via de fundering van één of meer andere panden in het cluster aan de ondergrond worden overgedragen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/begrip/">https://definities.geostandaarden.nl/fundering/begrip/</a></td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingseenheid_attribuutsoort_naam">naam</a>
</td>
<td>
</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingseenheid_relatiesoort_omvat">omvat</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand">Pand</a>
</td>
<td>
1..*</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingseenheid_attribuutsoort_naam">
<h6>naam</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingseenheid.naam</td>
</tr>
<tr>
<th>Naam</th>
<td>naam</td>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingseenheid_relatiesoort_omvat">
<h6>omvat</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Funderingseenheid.omvat</td>
</tr>
<tr>
<th>Naam</th>
<td>omvat</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Ja</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1..*</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingseenheid">Funderingseenheid</a>
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
</section>

</section>

<section id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering">
<h4>Fundering</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Fundering</td>
</tr>
<tr>
<th>Naam</th>
<td>Fundering</td>
</tr>
<tbody>
</tbody>
</table>

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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering_relatiesoort_hoort_bij">hoort bij</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_pand">Pand</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering_relatiesoort_omvat_geheel_of_deel_van">omvat geheel of deel van</a>
</td>
<td>
</td>
<td>
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_funderingsconstructie">Funderingsconstructie</a>
</td>
<td>
1..*</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering_relatiesoort_hoort_bij">
<h6>hoort bij</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Fundering.hoort%20bij</td>
</tr>
<tr>
<th>Naam</th>
<td>hoort bij</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering">Fundering</a>
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
<section class="notoc" id="informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering_relatiesoort_omvat_geheel_of_deel_van">
<h6>omvat geheel of deel van</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Fundering.omvat%20geheel%20of%20deel%20van</td>
</tr>
<tr>
<th>Naam</th>
<td>omvat geheel of deel van</td>
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
<a class="link" href="#informatiemodel_informatiemodel_funderingen_domein_fundering_objecttype_fundering">Fundering</a>
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

</section>

### Enumeraties

#### Pandtype - nog te vervangen {#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_pandtype_nog_te_vervangen}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Pandtype%20-%20nog%20te%20vervangen</td>
</tr>
<tr>
<th>Naam</th>
<td>Pandtype - nog te vervangen</td>
</tr>
<tr>
<th>Definitie</th>
<td>Classificatie van een pand op basis van de bouwkundige verschijningsvorm en de constructieve samenhang met omliggende panden.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/id/begrippenkader/Pandtype">https://definities.geostandaarden.nl/fundering/id/begrippenkader/Pandtype</a></td>
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
twee-onder-een-kappand</td>
<td>
Een pand met maximaal drie bouwlagen dat een dragende muur deelt met één naastgelegen pand en daarom constructief verbonden is aan één ander pand.</td>
<tr>
<td>
seriematig rijtjespand</td>
<td>
Een pand dat deel uitmaakt van een aaneengesloten rij panden waarbij naastgelegen panden dragende wanden delen en waarvan de bouwkundige kenmerken grotendeels uniform zijn.</td>
<tr>
<td>
niet-seriematig rijtjespand</td>
<td>
Een pand dat deel uitmaakt van een aaneengesloten rij panden waarvan de bouwkundige kenmerken niet grotendeels uniform zijn, maar waarbij sprake is van samenhang met andere panden in de rij die impact kunnen hebben op de fundering.</td>
<tr>
<td>
appartementspand</td>
<td>
Een pand met meerdere bouwlagen dat bestaat uit meerdere appartementen, die doorgaans via een gemeenschappelijke ontsluiting of gemeenschappelijke voorzieningen met elkaar samenhangen.</td>
<tr>
<td>
alleenstaand pand</td>
<td>
Een pand met maximaal drie bouwlagen dat geen wanden of daken gemeenschappelijk heeft met naastgelegen panden en daarom constructief en functioneel gescheiden is van andere panden.</td>
</tbody>
</table>

</section>

#### Houttype {#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_houttype}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Houttype</td>
</tr>
<tr>
<th>Naam</th>
<td>Houttype</td>
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
vuren</td>
<td>
</td>
<tr>
<td>
grenen</td>
<td>
</td>
</tbody>
</table>

</section>

#### Betontype {#informatiemodel_informatiemodel_funderingen_domein_fundering_enumeratie_betontype}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Betontype</td>
</tr>
<tr>
<th>Naam</th>
<td>Betontype</td>
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
gewapend beton</td>
<td>
</td>
<tr>
<td>
ongewapend beton</td>
<td>
</td>
</tbody>
</table>

</section>

### Codelijsten

#### Pandtype - Nog in te vullen {#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_pandtype_nog_in_te_vullen}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Pandtype%20-%20Nog%20in%20te%20vullen</td>
</tr>
<tr>
<th>Naam</th>
<td>Pandtype - Nog in te vullen</td>
</tr>
<tr>
<th>Definitie</th>
<td>Classificatie van een pand op basis van de bouwkundige verschijningsvorm en de constructieve samenhang met omliggende panden.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="https://definities.geostandaarden.nl/fundering/id/begrippenkader/Pandtype">https://definities.geostandaarden.nl/fundering/id/begrippenkader/Pandtype</a></td>
</tr>
<tbody>
</tbody>
</table>

#### Materiaal {#informatiemodel_informatiemodel_funderingen_domein_fundering_codelijst_materiaal}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:Informatiemodel%20Funderingen:Fundering:Materiaal</td>
</tr>
<tr>
<th>Naam</th>
<td>Materiaal</td>
</tr>
<tbody>
</tbody>
</table>

## Extern NEN3610

![mim:Extern NEN3610](data/model/nen3610/package-view.png "mim:Extern NEN3610")

### Objecttypen

<section id="informatiemodel_nen3610_domein_semantisch_model_objecttype_geo_object">
<h4>GeoObject</h4>

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

</section>

<section id="informatiemodel_nen3610_domein_semantisch_model_objecttype_reeel_object">
<h4>ReeelObject</h4>

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

</section>

<section id="informatiemodel_nen3610_domein_semantisch_model_objecttype_constructie">
<h4>Constructie</h4>

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

</section>

<section id="informatiemodel_nen3610_domein_semantisch_model_objecttype_gebouw">
<h4>Gebouw</h4>

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

</section>

## Extern IMBAG

![mim:Extern IMBAG](data/model/imbag/package-view.png "mim:Extern IMBAG")

### Objecttypen

<section id="informatiemodel_imbag_domein_objecten_objecttype_pand">
<h4>Pand</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://bag.basisregistraties.overheid.nl/def/bag#Pand</td>
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
<td>Een Pand is de kleinste, bij de totstandkoming functioneel en bouwkundig-constructief zelfstandige eenheid die direct en duurzaam met de aarde is verbonden en betreedbaar en afsluitbaar is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Artikel 1 Wet basisregistratie adressen en gebouwen</td>
</tr>
<tr>
<th>Datum opname</th>
<td>Februari 2004</td>
</tr>
<tbody>
</tbody>
</table>

</section>

<section id="informatiemodel_imbag_domein_objecten_objecttype_verblijfsobject">
<h4>Verblijfsobject</h4>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://bag.basisregistraties.overheid.nl/def/bag#Verblijfsobject</td>
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
<td>Een Verblijfsobject is de kleinste binnen één of meerdere panden gelegen en voor woon -, bedrijfsmatige - of recreatieve doeleinden geschikte eenheid van gebruik, die ontsloten wordt via een eigen toegang vanaf de openbare weg, een erf of een gedeelde verkeersruimte en die onderwerp kan zijn van rechtshandelingen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Artikel 1 Wet basisregistratie adressen en gebouwen</td>
</tr>
<tr>
<th>Datum opname</th>
<td>Februari 2004</td>
</tr>
<tbody>
</tbody>
</table>

</section>


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

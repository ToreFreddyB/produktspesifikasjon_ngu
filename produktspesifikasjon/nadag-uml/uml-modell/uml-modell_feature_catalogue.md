#### GeotekniskBorehull

geografisk område representert ved et punkt som er den logiske enhet for tolking av laginndeling og egenskaper til de forskjellige jordlag geographical area represented by a location which is the logical unit for interpretation of stratification and properties for the different strata

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boreNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Nummer på borehull benyttet i den geotekniske undersøkelsen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Identifikasjon av et objekt, ivaretatt av den ansvarlige leverandør, som kan benyttes av eksterne applikasjoner som referanse til objektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>EksternIdentifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av ekstern leverendør.<br />Det er data leverendørens ansvar å sørge for at denne eksterne identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternLeveringDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble levert til database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternNavnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som identifiserer datakilden/leverandør til objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternVersjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt  Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Terrenghøyde ved start borehull [m]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeReferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Referansesystem for høydeangivelse, som EPSG-kode.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>NADAG_Høyderef</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- NN2000<br />- NN54<br />- Ukjent høydereferanse</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvikkleirePåvisning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Grad av sikkerhet for påvisning av kvikkleire (omrørt skjærfasthet mindre eller lik 0,5 kPa) eller sprøbruddmateriale (omrørt skjærfasthet mindre enn 2 kPa)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>KvikkleirePåvisningKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Antatt – Benyttes ved sondering<br />- AntattIkkeKvikk – Benyttes ved sondering<br />- IkkeVurdert<br />- Sikker – Kan kun benyttes der kvikkleire eller sprøbruddmateriale er påvist ved prøvetaking<br />- Usikker – Benyttes ved sondering</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>maksBoretLengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lengste boret lengde for borehullsundersøkelsene i dette borhullet [m]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opphav</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opprettetDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble opprettet i database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opprinneligGeotekniskUndersID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>opprinneligGeotekniskUndersID - LokalID fra opprinnelig Geoteknisk undersøkelse.<br />Benyttes for å identifisere orginal undersøkelse med rapporter etc. ved bruk av samme GeotekniskBorehull i flere undersøkelser.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
GeovitenskapligBorehull

**Assosiasjoner**
GeotekniskUnders – rolle: undersOmr – kardinalitet: 0..*
GeotekniskBorehullUnders – rolle: harUndersøkelse – kardinalitet: 0..*

#### KombinasjonSondering

kombinasjon av boremetodene totalsondering og fjellkontrollboring som gjør det mulig å bore både i løsmasse og bergcombination of the boring methods rotary pressure sounding and rock control boring which enables drilling in both soils and rock.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeIBerg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>boret dybde til bergoverflaten [m] drilled depth to the rock surface</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dybde til bergoverflaten som ikke er målt men basert på tolkning [m] depth to the rock surface based on interpretation and not measurements</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BorlengdeTilBerg</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg.borlengdeKvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver om dybden til berg er antatt eller påvist med en sikker metode<br /><br /><br />defines the quality of the depth information either assumed or confirmed by a secure method</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>KvalitetBorlengdeTilBerg</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- antatt – usikker angivelse av dybde til berg

&lt;engelsk&gt;
uncertain depth to rock
&lt;/engelsk&gt;<br />- påvist – sikker angivelse av dybde til berg

&lt;engelsk&gt;
confirmed depth to rock
&lt;/engelsk&gt;</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg.borlengdeTilBerg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dybde til fjell som ikke er målt men basert på tolkning [m]<br /><br /><br />depth to bedrock based on interpretation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>maksLast</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>maksimal nedpressingskraft registrert på overflaten [kN] maximum penetration force recorded on the surface</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
GeotekniskSondering

#### GeotekniskDokument

dokument(er) tilhørende geotekniske undersøkelsesområder og borehull accompanying documents to geotechnical investigation areas and boreholes

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kort informasjon om dokumentet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dokumentDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dato når dokument ble opprettet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dokumentFilnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Filnavn på dokumentet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dokumentID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Unik nøkkel for dokument.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dokumentNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på dokument</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dokumentNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Feks. rapportNr.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dokumentNøkkel</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Benyttes til å angi nøkkelverdi ved kall til Web-api.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dokumentType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Type dokument. Feks. Geoteknisk rapport, Profilbilde</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>NADAG_DokumentType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Andre vedlegg til borehull<br />- Bilde<br />- Bilde borehullsprofil<br />- Bilde koblet til digitalisert DWG tegning<br />- Digitalisert DWG tegning<br />- Geoteknisk rapport<br />- Labrapport<br />- Modell<br />- Opptegningssymbol<br />- Plantegning<br />- Profiltegning<br />- Rådatafil<br />- Tegning<br />- Uspesifisert dokumenttype<br />- Vurderingsrapport</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dokumentURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Komplett URL for dokument med id.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Identifikasjon av et objekt, ivaretatt av den ansvarlige leverandør, som kan benyttes av eksterne applikasjoner som referanse til objektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>EksternIdentifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av ekstern leverendør.<br />Det er data leverendørens ansvar å sørge for at denne eksterne identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternLeveringDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble levert til database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternNavnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som identifiserer datakilden/leverandør til objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternVersjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt  Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>innholdType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Type dokumentformat, feks. Image/png, pdf</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opprettetDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble opprettet i database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
GeotekniskBorehull – rolle: tilhørerGB – kardinalitet: 0..1
GeotekniskUnders – rolle: tilhørerGU – kardinalitet: 0..1
GeotekniskBorehullUnders – rolle: tilhørerGBU – kardinalitet: 0..1
GeotekniskFeltUnders – rolle: tilhørerFeltUnders – kardinalitet: 0..1

#### GeotekniskBorehullUnders

geografisk punkt hvor det er utført feltforsøk, prøvetaking, måling av poretrykk osv. med tilhørende observasjoner geographical location where field tests, sampling, pore pressure measurements etc. with corresponding observations have been carried out

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dybdeGrunnvannstand</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dybde [m] fra terrengoverflaten til det nivå i grunnen der alle porene i jorden er mettet med vann og poretrykket begynner å stige depth [m] from the terrain surface to the level in the ground where all voids are saturated with water, and where the pore pressure starts to increase</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Identifikasjon av et objekt, ivaretatt av den ansvarlige leverandør, som kan benyttes av eksterne applikasjoner som referanse til objektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>EksternIdentifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av ekstern leverendør.<br />Det er data leverendørens ansvar å sørge for at denne eksterne identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternLeveringDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble levert til database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternNavnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som identifiserer datakilden/leverandør til objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternVersjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt  Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forboretDiameter</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>diameter [mm] av forboret hull i en borhullundersøkelse diameter (mm) of a predrilled hole in a borehole investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forboretLengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lengde[m] av forboret hull i en borhullundersøkelse Length[m] of a predrilled borehole in a borehole investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forboretStartLengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>startlengde[m] for hvor forboring startet i en borhullundersøkelse start depth[m] where the predrilling in the  borehole investigation started</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forboringMetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode brukt til boring uten registrering av datapre boring method</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geotekniskMetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Metoder benyttet ved geotekniske borehullundersøkelser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GeotekniskMetodeKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Bergkontrollboring<br />- Blokkprøve<br />- Dilatometertest<br />- Dreiesondering manuell<br />- Dreiesondering maskinell<br />- Dreiesondering uspesifisert<br />- Dreietrykksondering<br />- Dynamisk sondering uspesifisert<br />- Elektrisk sondering<br />- Enkel sondering<br />- Gassmåling<br />- Gassprøve<br />- Graveprøve<br />- Grunnvannsmåling<br />- Hejarsondering A<br />- Hejarsondering B<br />- HK sondering<br />- Hydraulisk test<br />- Ikke angitt<br />- Jord-berg sondering 1<br />- Jord-berg sondering 2<br />- Jord-berg sondering 3<br />- Kanneprøve<br />- Kjerneboring<br />- Kjerneprøve<br />- Kombinasjonssondering uspesifisert<br />- Kombisondering<br />- Miljøundersøkelse<br />- Naverprøve<br />- Platebelastning<br />- Poretrykksmåling<br />- Prøve uspesifisert<br />- Prøveserie uspesifisert<br />- Ramprøve<br />- Ramsondering<br />- Ramsondering A<br />- Ramsondering B<br />- Sedimentprøve<br />- Skovlprøve<br />- Slagsondering<br />- SPT<br />- Statisk sondering uspesifisert<br />- Stempelprøve<br />- Stikksondering<br />- Totalsondering Norge<br />- Totalsondering Sverige<br />- Trykksondering (CPT, CPTU)<br />- Vannprøve<br />- Vektsondering manuell<br />- Vektsondering maskinell<br />- Vingeboring</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Terrenghøyde ved start borehullsundersøkelse [m]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeReferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Referansesystem for høydeangivelse, som EPSG-kode.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>NADAG_Høyderef</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- NN2000<br />- NN54<br />- Ukjent høydereferanse</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opprettetDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble opprettet i database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>stoppKode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tosifret tall som benyttes for å angi årsak til avslutning av borehullundersøkelsecode used to explain the reason for termination of a borehole investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GeotekniskStoppkode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- AntattBerg – kode for avslutning av boring i antatt berg &lt;engelsk&gt;code for termination of boring in presumed rock&lt;/engelsk&gt;<br />- AntattSteinBlokk – kode for avslutning av boring i antatt stein eller blokk &lt;engelsk&gt;code for termination of boring in presumed stone or block&lt;/engelsk&gt;<br />- BruddBorstangSpiss – kode for avslutning av boring ved brudd i borstang eller borspiss &lt;engelsk&gt;code for termination of boring due to failure of drill rod or drill bit&lt;/engelsk&gt;<br />- DybdeIBergOppnådd – kode for avslutning av boring ved oppnådd boredybde i berg &lt;engelsk&gt;code for termination of boring after assumed depth in rock&lt;/engelsk&gt;<br />- DybdeIFjellMerEnn3Meter – kode for avslutning av boring ved oppnådd boredybde i berg større enn 3 m &lt;engelsk&gt;code for termination of boring after assumed depth in rock greater than 3 m&lt;/engelsk&gt;<br />- DybdeIFjellMerEnn3MeterMedAnalyse – kode for avslutning av boring ved oppnådd boredybde i berg større enn 3 m og borestøv har blitt analysert &lt;engelsk&gt;code for termination of boring after assumed depth in rock greater than 3 m and the drill cuttings have been analysed&lt;/engelsk&gt;<br />- KjerneBoringMerEnn3Meter – Det har blitt tatt ut en kjerneprøve på minimum 3 meter&lt;engelsk&gt; core drilling min 3 meter&lt;/engelsk&gt;<br />- MaterialEllerMaskinFeil – kode for avslutning av boring ved feil på borustyr &lt;engelsk&gt;code for termination of boring due to equipment errors&lt;/engelsk&gt;<br />- SonderingAvbrutt – kode for avslutning av boring ved avbrutt sondering &lt;engelsk&gt;code for termination of boring due to interrupted sounding&lt;/engelsk&gt;<br />- SonderingAvbruttFastGrunn – kode for avslutning av boring i fast grunn &lt;engelsk&gt;code for termination of boring in firm ground&lt;/engelsk&gt;<br />- SonderingAvsluttetUtenStopp – kode for avslutning av sondering uten stopp &lt;engelsk&gt;code for termination of sounding without stop&lt;/engelsk&gt;<br />- SteinBlokkFjell – kode for avslutning av boring i stein, blokk eller berg &lt;engelsk&gt;code for termination of boring in presumed stone, block or rock&lt;/engelsk&gt;<br />- Uspesifisert – kode for avslutning av boring ved uspesifisert årsak &lt;engelsk&gt;code for termination of boring due to unspecified reasons&lt;/engelsk&gt;</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>undersøkelseNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Nummer på borehullundersøkelse benyttet i den geotekniske undersøkelsen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
GeovitenskapligBorehullUndersøkelse

**Assosiasjoner**
GeotekniskBorehull – rolle: undersPkt – kardinalitet: 0..1
Geotekniskmetode – rolle: metode – kardinalitet: 0..*

#### GeotekniskFeltUnders

Geoteknisk feltundersøkelse

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternidentifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Identifikasjon av et objekt, ivaretatt av den ansvarlige leverandør, som kan benyttes av eksterne applikasjoner som referanse til objektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>EksternIdentifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternidentifikasjon.eksternId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av ekstern leverendør.<br />Det er data leverendørens ansvar å sørge for at denne eksterne identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternidentifikasjon.eksternLeveringDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble levert til database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternidentifikasjon.eksternNavnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som identifiserer datakilden/leverandør til objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternidentifikasjon.eksternVersjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt  Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>feltundersNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Nummer på feltundersøkelse benyttet i den geotekniske undersøkelsen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>feltundersType</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>FeltUndersTypeKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/sosi/produktspesifikasjon/grunnundersoekelse/1.0/GeotekniskMetodeKode.xml">http://skjema.geonorge.no/sosi/produktspesifikasjon/grunnundersoekelse/1.0/GeotekniskMetodeKode.xml</a><br />- FeltUndersMetode<br />- Tolket<br />- TolketBerghøyde</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geotekniskFeltUndersMetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Metoder benyttet ved geotekniske feltundersøkelser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GeotekniskFeltUndersMetodeKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- BelastningTest<br />- ElektriskSondering<br />- HelningMåling<br />- PermeabilitetMåling<br />- Ramsondering<br />- SetningMåling<br />- Skovlboring<br />- Skrueplate<br />- SPT</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Terrenghøyde ved start feltundersøkelse [m]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeFjell</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høyde på observert fjell [m]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeReferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Referansesystem for høydeangivelse, som EPSG-kode.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>NADAG_Høyderef</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- NN2000<br />- NN54<br />- Ukjent høydereferanse</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterers. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />NOTE Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opprettetDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble opprettet i database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted objektet eksisterer på bestemt av måleutstyr</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tolkningMetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Metoder benyttet for tolkning av geotekniske feltundersøkelser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TolkningMetodeKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- +Le<br />- BG<br />- BH<br />- F</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
GeotekniskUnders – rolle: tilhørerGU – kardinalitet: 0..1

#### GeotekniskTolketLag

Lag med geoteknisk tolkning

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Identifikasjon av et objekt, ivaretatt av den ansvarlige leverandør, som kan benyttes av eksterne applikasjoner som referanse til objektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>EksternIdentifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av ekstern leverendør.<br />Det er data leverendørens ansvar å sørge for at denne eksterne identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternLeveringDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble levert til database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternNavnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som identifiserer datakilden/leverandør til objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternVersjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt  Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>hovedLagKlassifiseringsKode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>oversikt over lagdeling og jordart for klassifisering og identifisering av grunnforhold</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>HovedLagKlassifisering</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- AnnetOrganiskMateriale – annet organisk materiale&lt;engelsk&gt;other organic materials&lt;/engelsk&gt;<br />- AntattForurensning – antatt forurenset materiale&lt;engelsk&gt;assumed contaminated material&lt;/engelsk&gt;<br />- Berg – berg&lt;engelsk&gt;rock&lt;/engelsk&gt;<br />- BergEllerBlokk – Berg eller blokk&lt;engelsk&gt;Rock or boulders&lt;/engelsk&gt;<br />- Blokk – blokk (fraksjoner større enn 200 mm)&lt;engelsk&gt;boulders (fractions &gt; 200 mm&lt;/engelsk&gt;<br />- BlokkigOgSteinigMorene – Blokkig og steinig morene &lt;engelsk&gt;Boulder and Cobble till &lt;/engelsk&gt;<br />- DelvisFibrigTorv – Delvis fibrig torv. Gjenkjennelig plantestruktur, ingen styrke i planterestene&lt;engelsk&gt;Pseudo-fibrous peat&lt;/engelsk&gt;<br />- Dy – dy (Dy består av vannavsatte plante- og dyrerester og er en strukturløs masse)&lt;engelsk&gt;organic material consisting of plant and animal debris sedimented in water. The material is not showing a special structure&lt;/engelsk&gt;<br />- FibrigTorv – Fibrig torv. Fibrig struktur, lett gjenkjennelig plantestruktur, viser noe styrke,&lt;engelsk&gt; Fibrous peat&lt;/engelsk&gt;<br />- ForvitretTorv – forvitret torv (Torv er mer eller mindre omvandlede planterester, klassifiseres etter von Post skala)&lt;engelsk&gt;weathered peat (Peat is more or less transformed plant debris and is classified according to the von Post scale)&lt;/engelsk&gt;<br />- Friksjonsjord – friksjonsjord&lt;engelsk&gt;non-cohesive soil &lt;/engelsk&gt;<br />- Fyllmasse – fyllmasse&lt;engelsk&gt;fill mass&lt;/engelsk&gt;<br />- Grus – grus (fraksjoner mellom 2,0 og 63 mm)&lt;engelsk&gt;gravel (fractions between 2,0 and 63 mm&lt;/engelsk&gt;<br />- GrusigMorene – Grussig morene&lt;engelsk&gt;Gravel till&lt;/engelsk&gt;<br />- Gytje – gytje (Gytje består av vannavsatte plante- og dyrerester og viser vanligvis organisk struktur)&lt;engelsk&gt;organic material consisting of plant and animal debris. The material usually shows a special structure&lt;/engelsk&gt;<br />- GytjeOgLeire – leirblandet gytje (organisk materiale )&lt;engelsk&gt;organic material consisting of plant, animal debris and clay.&lt;/engelsk&gt;<br />- Humus – humus (Humus er en fellesbetegnelse på organisk materiale i jordarter)&lt;engelsk&gt;common denotation of organic matter in soils&lt;/engelsk&gt;<br />- Jord – Jord&lt;engelsk&gt;soil&lt;/engelsk&gt;<br />- Kohesjonsjord<br />- Kull – kull&lt;engelsk&gt;coal&lt;/engelsk&gt;<br />- Kvikkleire – kvikkleire (omrørt skjærfasthet &lt; 0,5 kPa)&lt;engelsk&gt;quick clay (remoulded shear strength &lt; 0,5 kPa)&lt;/engelsk&gt;<br />- Leire – leire (materiale med mer enn 30 % i leirfraksjonen &lt; 2 µm)&lt;engelsk&gt;clay (material with more than 30 % in the clay fraction &lt; 2 µm)&lt;/engelsk&gt;<br />- LeirigMorene – Leirig morene&lt;engelsk&gt;Clay till&lt;/engelsk&gt;<br />- Matjord – matjord &lt;engelsk&gt;humus&lt;/engelsk&gt;<br />- Morene – morene&lt;engelsk&gt;glacial deposit&lt;/engelsk&gt;<br />- OppsprukketBerg – oppsprukket berg&lt;engelsk&gt;jointed rock&lt;/engelsk&gt;<br />- Planterester – planterester&lt;engelsk&gt;plant remnants&lt;/engelsk&gt;<br />- Sand – Sand (fraksjoner mellom 0,063 og 2,0 mm)&lt;engelsk&gt;sand (fractions between  0,063 and 2,0 mm&lt;/engelsk&gt;<br />- SandigMorene – Sandig morene&lt;engelsk&gt;Sand till&lt;/engelsk&gt;<br />- Silt – silt (fraksjoner mellom 0,002 og 0,063 mm)&lt;engelsk&gt;silt (fractions between 0,002 and 0,063 mm&lt;/engelsk&gt;<br />- SiltigMorene – Siltig morene&lt;engelsk&gt;Silt till&lt;/engelsk&gt;<br />- Skjell – Skjell&lt;engelsk&gt;Shells&lt;/engelsk&gt;<br />- Skjellgrus – skjellgrus&lt;engelsk&gt;coquina&lt;/engelsk&gt;<br />- Skjellsand – skjellsand&lt;engelsk&gt;shellsand&lt;/engelsk&gt;<br />- Stein – Stein&lt;engelsk&gt;Cobbles&lt;/engelsk&gt;
stein (fraksjoner mellom 63 og 200 mm)&lt;engelsk&gt;cobbles (fractions between 63 and 200 mm&lt;/engelsk&gt;<br />- SteinigMorene – Steinig morene&lt;engelsk&gt;Cobble till&lt;/engelsk&gt;<br />- SulfidholdigJord – suldidholdig sand&lt;engelsk&gt;sulphide sand&lt;/engelsk&gt;<br />- Torv – torv&lt;engelsk&gt;peat&lt;/engelsk&gt;<br />- TørrskorpeLeire – tørrskorpe leire&lt;engelsk&gt;crusty clay&lt;/engelsk&gt;<br />- UkjentMateriale – Ukjent materiale &lt;engelsk&gt;Unknown material&lt;/engelsk&gt;<br />- UspesifisertMateriale – uspesifisert materiale&lt;engelsk&gt;unspecified material&lt;/engelsk&gt;</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Laghøyde for tolkning [m]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeReferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referansesystem for høydeangivelse, som EPSG-kode.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>NADAG_Høyderef</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- NN2000<br />- NN54<br />- Ukjent høydereferanse</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>klassifiseringMetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>oversikt over klassifiseringsmetoder for bestemmelse av grunnforhold</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>KlassifiseringsMetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- BeregnetFraTerrengoverflaten – beregnet størrelse fra terrengoverflaten&lt;engelsk&gt;calculated from the terrain surface&lt;/engelsk&gt;<br />- Observasjon – tolket fra observasjon&lt;engelsk&gt;interpreted from observation&lt;/engelsk&gt;<br />- TolketBergBoring – tolket fra boring i berg&lt;engelsk&gt;interpreted from drilling in rock&lt;/engelsk&gt;<br />- TolketBergBoring3Meter – tolket fra boring 3 m inn i berg&lt;engelsk&gt;interpreted from boring 3 m into rock&lt;/engelsk&gt;<br />- TolketFeltsondering – tolket fra sondering i felt&lt;engelsk&gt;interpreted from sounding in the field&lt;/engelsk&gt;<br />- TolketLab – tolket fra prøving i laboratoriet&lt;engelsk&gt;interpreted from testing in the laboratory&lt;/engelsk&gt;<br />- TolketPrøvetak – tolket fra prøvetaking i felt&lt;engelsk&gt;interpreted from sampling in the field&lt;/engelsk&gt;<br />- TolketTegning – tolket fra tegning&lt;engelsk&gt;interpreted from drawing&lt;/engelsk&gt;<br />- Uspesifisert – uspesifisert tolkningskilde&lt;engelsk&gt;unspecified source of interpretation&lt;/engelsk&gt;</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lagBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskrivelse av tolket lag feks. Sand</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på tolket lag</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning gitt i x.y,z.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>påTerrengOverflate</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Om tolkning er på terrengoverflate</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tolketAv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Hvem som har gjort tolkning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tolketLagID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Unik nøkkel for tolktet lag</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tolketTidspunkt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når tolkning ble utført</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tolkningMerknad</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kommentar til tolkning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>underTerrengOverflate</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Om tolkning er under terrengoverflate</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vurdering</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Hvor sikker tolkning er, med  0=Udefinert,5=Sikker og glidende skala imellom.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
GeotekniskTolketPunkt – rolle: tilhørerTolketPunkt – kardinalitet: 0..1

#### GeotekniskTolketPunkt

Punkt med geoteknisk tolkning i GeotekniskTolketLag

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kort tilleggsinformasjon om punktet for tolkning/er<br /><br />a short description</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>digitaliseringsmålestokk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kartmålestokk registreringene/ datene er hentet fra/ registrert på<br /><br />Eksempel: 1:50 000 = 50000.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Terrenghøyde overflate for punkt med tolkning(/er)[m]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydeReferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Referansesystem for høydeangivelse, som EPSG-kode.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>NADAG_Høyderef</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- NN2000<br />- NN54<br />- Ukjent høydereferanse</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterers. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />NOTE Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av kvaliteten på stedfestingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>PosisjonskvalitetNADAG</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.målemetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Målemetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Aerotriangulert – (Pkt. beregnet v/ aerotriangulering)

-- Definition --
Point calculated by aerotriangulation<br />- Analytisk plotter<br />- Annet  (denne har ingen mening, bør fjernes?) – Annet<br />- Annet (spesifiseres i filhode) ( bør vel fjernes, blir borte ved overføring mellom systemer) – Annet (spesifiseres i filhode)<br />- Autograf - vanlig registrering<br />- Beregnet<br />- Dig. på skjerm fra scannet samkopi – (Raster)<br />- Digitalisert fra flybilde - monodigitalisert fra film<br />- Digitalisert fra flybilde - monodigitalisert fra fotokopi<br />- Digitalisert fra krokering på kart<br />- Digitalisert fra ortofoto<br />- Digitalisert fra ortofoto - film<br />- Digitalisert fra ortofoto - fotokopi<br />- Digitalisert på dig.bord fra blyantoriginal<br />- Digitalisert på dig.bord fra ortofoto/flybilde<br />- Digitalisert på dig.bord fra papirkopi<br />- Digitalisert på dig.bord fra rissefolie<br />- Digitalisert på dig.bord fra strek-kart<br />- Digitalisert på dig.bord fra transparent film - god kvalitet<br />- Digitalisert på dig.bord fra transparent film - mindre god kvalitet<br />- Digitalisert på skjerm fra satellittbilde<br />- Digitalt stereoinstrument<br />- Direkte innlagt på skjerm<br />- Fastsatt punkt – punkt fastsatt ut fra et grunnlag f.eks ved partenes enighet ved oppmålingsforretning.<br />- Fastsatt ved dom eller kongelig resolusjon<br />- Flybåren laserscanner<br />- Frihåndstegning<br />- Generalisert<br />- Generert i terrengmodell<br />- Generert sentralpunkt<br />- Generert sirkelgeometri<br />- Genererte data (interpolasjon)<br />- GPS Fasemåling RTK – (Realtids kinematisk måling). Tidligere GPS kinematisk (Real time kinematic)

-- Definition --
(Real time kinematic measurement). Previous GPS kinematic (Real time kinematic)<br />- GPS Fasemåling, andre metoder – (utenom RTK). Tidligere GPS-Absolutt, fase

-- Definition --
(not including RTK). Previous Absolute GPS, phase<br />- GPS Fasemåling, float-løsning<br />- GPS Fasemåling, statisk måling – Tidligere GPS, Differensiell

-- Definition --
Previous GPS, differential<br />- GPS Kodemåling, enkeltmålinger – Tidligere GPS, Absolutt, pseudorange

-- Definition --
Previous GPS, absolute, pseudorange<br />- GPS Kodemåling, relative målinger – Tidligere GPS-Differensiell, pseudorange

-- Definition --
Previous GPS differential, pseudorange<br />- Kombinasjon av GPS/Treghet<br />- Koordinater hentet fra GAB<br />- Koordinater hentet fra JREG<br />- Målt med målehjul<br />- Målt med stigningsmåler<br />- Målt med stikkstang<br />- Målt med waterstang<br />- Ortogonalmetoden<br />- Sammenknytningspunkt/randpunkt<br />- Scannet fra blyantoriginal<br />- Scannet fra kart<br />- Scannet fra papirkopi<br />- Scannet fra rissefolie<br />- Scannet fra transparent folie - god kvalitet<br />- Scannet fra transparent folie - mindre god kvalitet<br />- Spesielle metoder<br />- Stereoinstrument<br />- Tatt fra plan<br />- Teodolitt med elektronisk avstandsmåler<br />- Teodolitt med målebånd<br />- Terrengmålt<br />- Totalstasjon<br />- Treghetsstedfesting<br />- Ukjent målemetode<br />- Utmål – Punkt beregnet på bakgrunn av andre punkter, slik som to avstander eller avstand + retning

-- Definition --
Point calculated on the basis of other items, such as two distances or distance + direction.<br />- Vektet middel</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.målemetodeHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for å måle høyden</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MålemetodeHøyde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Aerotriangulert<br />- Analytisk plotter<br />- Annet<br />- Annet (spesifiseres i filhode)<br />- Autograf - vanlig registrering<br />- Beregnet (?)<br />- Digitalt stereoinstrument<br />- Fastsatt ved dom eller kongelig resolusjon<br />- Flybåren laserscanning<br />- Generalisert<br />- Generert i terrengmodell<br />- Generert sirkelgeometri<br />- Genererte data (interpolasjon)<br />- GPS Fasemåling RTK<br />- GPS Fasemåling, andre metoder<br />- GPS Fasemåling, statisk måling.<br />- GPS Kodemåling, enkeltpunktbestemmelser<br />- GPS Kodemåling, relative målinger.<br />- Kombinasjon av GPS/Treghet<br />- Koordinater hentet fra GAB<br />- Koordinater hentet fra JREG (?)<br />- Målt med stigningsmåler<br />- Nivellement<br />- Ortogonalmetoden<br />- Sammenknytningspunkt/randpunkt<br />- Spesielle metoder<br />- Stereoinstrument<br />- Tatt fra plan<br />- Teodolitt med elektronisk avstandsmåler<br />- Teodolitt med målebånd<br />- Terrengmålt<br />- Totalstasjon<br />- Treghetsstedfesting<br />- Ukjent målemetode<br />- Vektet middel</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i [cm]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighetHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nøyaktighet for høyden i [cm]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på tolket punkt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning gitt i x.y,z.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tolketAv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Hvem som har tolket punktet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tolketTidspunkt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når tolkning ble utført</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
GeotekniskBorehull – rolle: tilhørerGB – kardinalitet: 0..1
GeotekniskUnders – rolle: tilhørerGU – kardinalitet: 0..1

#### GeotekniskUndersøkelseGrense

avgrensning av et område for geotekniske undersøkelser. Merk: Benyttes kun for de formater som krever egen geometri for avgrensning av flate. demarcation of an area with soil investigations. Only used for delivery formats that requier it.

Egenskaper

(ingen)

Relasjoner

**Arv**
GeovitenskapeligUndersøkelseGrense

#### GeotekniskUnders

geografisk område hvor det finnes eller er planlagt geotekniske borehull tilhørende et gitt prosjekt geographical area where there are or are planned geotechnical boreholes for a given project

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Identifikasjon av et objekt, ivaretatt av den ansvarlige leverandør, som kan benyttes av eksterne applikasjoner som referanse til objektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>EksternIdentifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av ekstern leverendør.<br />Det er data leverendørens ansvar å sørge for at denne eksterne identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternLeveringDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble levert til database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternNavnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som identifiserer datakilden/leverandør til objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eksternIdentifikasjon.eksternVersjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt  Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opphav</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opprettetDato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Når objektet ble opprettet i database (Nadag)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>prosjektNr</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Nummer på prosjekt benyttet for den geotekniske undersøkelsen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>representasjonKvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hva avgrensningen/polygonen for en geoteknisk undersøkelse fysisk representerer.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RepresentasjonKvalitet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Polygon for GU med kun et enkelt borehull (100x100m) – Polygon for GU med kun et enkelt borehull (100x100m).<br />- Polygon hentet  fra borehull i GU, min og  maks koordinater.<br />- Polygon som avgrenser borehull i GU. – Avgrensning av en geoteknisk undersøkelse som i hovedsak avgrenser inngående borehull.<br />- Polygon som representerer prosjektområde. – Avgrensning av en geoteknisk undersøkelse som representerer prosjektområde.<br />- Representasjonspunkt for kommunalt/regionalt GU-område. – Avgrensning av en geoteknisk undersøkelse basert på et representasjonspunkt. Her for et område som er av kommunal/regional størrelse.<br />- Representasjonspunkt for mindre GU-område. Opptil ca. 10 mål. – Avgrensning av en geoteknisk undersøkelse basert på et representasjonspunkt. Her for et mindre område, opptil ca 10 mål.<br />- Representasjonspunkt for større GU-område. Over ca. 10 mål, eller lengre enn ca. 0,5 km – Avgrensning av en geoteknisk undersøkelse basert på et representasjonspunkt. Her for et større område, over ca 10 mål eller lenger enn ca. 0,5km.<br />- Ukjent – Hva avvgrensing av geoteknisk undersøkelse representerer er ikke kjent.</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>undersøkelseÅrAntatt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Antatt år for gjennomføring av den geotekniske undersøkelsen. For største delen av de leverte dataene har det vært dårlig infomasjon i egenskapene for undersøkelseperiode og derfor utvides det med denne egenskapen. Årstallet her er hentet fra ulike kilder i leveransene og avhengig av hva for leveranser det er varierer usikkerheten på på det antatte årstallet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
GeovitenskapeligUndersøkelse

**Assosiasjoner**
GeotekniskBorehull – rolle: undersPkt – kardinalitet: 0..*

#### Supertype_Geotekn_obj_omr (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og kan benyttes for alle objekttyper<br /><br />Merknad:<br />Spesielt i produktspesifikasjonsarbeid vil en velge egenskaper og av grensningslinjer fra denne klassen.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt<br /><br />Merknad: Bør bruke UUID.  se <a href="http://en.wikipedia.org/wiki/UUID">http://en.wikipedia.org/wiki/UUID</a><br />De som ikke benytter UUID må selv sørge for at denne er globalt unik.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterers. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />NOTE Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

#### Supertype_Geotekn_obj_pkt (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og kan benyttes for alle objekttyper<br /><br />Merknad:<br />Spesielt i produktspesifikasjonsarbeid vil en velge egenskaper og av grensningslinjer fra denne klassen.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet siste gang ble registrert/observert/målt i terrenget<br /><br />Merknad: I mange tilfeller er denne forskjellig fra Oppdateringsdato, da registrerte endringer kan bufres i en kortere eller lengre periode før disse legges inn i databasen.<br />Ved førstegangsregistrering settes Datafangstdato lik førsteDatafangstdato.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>digitaliseringsmålestokk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kartmålestokk registreringene/ datene er hentet fra/ registrert på<br /><br />Eksempel: 1:50 000 = 50000.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt<br /><br />Merknad: Bør bruke UUID.  se <a href="http://en.wikipedia.org/wiki/UUID">http://en.wikipedia.org/wiki/UUID</a><br />De som ikke benytter UUID må selv sørge for at denne er globalt unik.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterers. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />NOTE Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av kvaliteten på stedfestingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>PosisjonskvalitetNADAG</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.målemetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Målemetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Aerotriangulert – (Pkt. beregnet v/ aerotriangulering)

-- Definition --
Point calculated by aerotriangulation<br />- Analytisk plotter<br />- Annet  (denne har ingen mening, bør fjernes?) – Annet<br />- Annet (spesifiseres i filhode) ( bør vel fjernes, blir borte ved overføring mellom systemer) – Annet (spesifiseres i filhode)<br />- Autograf - vanlig registrering<br />- Beregnet<br />- Dig. på skjerm fra scannet samkopi – (Raster)<br />- Digitalisert fra flybilde - monodigitalisert fra film<br />- Digitalisert fra flybilde - monodigitalisert fra fotokopi<br />- Digitalisert fra krokering på kart<br />- Digitalisert fra ortofoto<br />- Digitalisert fra ortofoto - film<br />- Digitalisert fra ortofoto - fotokopi<br />- Digitalisert på dig.bord fra blyantoriginal<br />- Digitalisert på dig.bord fra ortofoto/flybilde<br />- Digitalisert på dig.bord fra papirkopi<br />- Digitalisert på dig.bord fra rissefolie<br />- Digitalisert på dig.bord fra strek-kart<br />- Digitalisert på dig.bord fra transparent film - god kvalitet<br />- Digitalisert på dig.bord fra transparent film - mindre god kvalitet<br />- Digitalisert på skjerm fra satellittbilde<br />- Digitalt stereoinstrument<br />- Direkte innlagt på skjerm<br />- Fastsatt punkt – punkt fastsatt ut fra et grunnlag f.eks ved partenes enighet ved oppmålingsforretning.<br />- Fastsatt ved dom eller kongelig resolusjon<br />- Flybåren laserscanner<br />- Frihåndstegning<br />- Generalisert<br />- Generert i terrengmodell<br />- Generert sentralpunkt<br />- Generert sirkelgeometri<br />- Genererte data (interpolasjon)<br />- GPS Fasemåling RTK – (Realtids kinematisk måling). Tidligere GPS kinematisk (Real time kinematic)

-- Definition --
(Real time kinematic measurement). Previous GPS kinematic (Real time kinematic)<br />- GPS Fasemåling, andre metoder – (utenom RTK). Tidligere GPS-Absolutt, fase

-- Definition --
(not including RTK). Previous Absolute GPS, phase<br />- GPS Fasemåling, float-løsning<br />- GPS Fasemåling, statisk måling – Tidligere GPS, Differensiell

-- Definition --
Previous GPS, differential<br />- GPS Kodemåling, enkeltmålinger – Tidligere GPS, Absolutt, pseudorange

-- Definition --
Previous GPS, absolute, pseudorange<br />- GPS Kodemåling, relative målinger – Tidligere GPS-Differensiell, pseudorange

-- Definition --
Previous GPS differential, pseudorange<br />- Kombinasjon av GPS/Treghet<br />- Koordinater hentet fra GAB<br />- Koordinater hentet fra JREG<br />- Målt med målehjul<br />- Målt med stigningsmåler<br />- Målt med stikkstang<br />- Målt med waterstang<br />- Ortogonalmetoden<br />- Sammenknytningspunkt/randpunkt<br />- Scannet fra blyantoriginal<br />- Scannet fra kart<br />- Scannet fra papirkopi<br />- Scannet fra rissefolie<br />- Scannet fra transparent folie - god kvalitet<br />- Scannet fra transparent folie - mindre god kvalitet<br />- Spesielle metoder<br />- Stereoinstrument<br />- Tatt fra plan<br />- Teodolitt med elektronisk avstandsmåler<br />- Teodolitt med målebånd<br />- Terrengmålt<br />- Totalstasjon<br />- Treghetsstedfesting<br />- Ukjent målemetode<br />- Utmål – Punkt beregnet på bakgrunn av andre punkter, slik som to avstander eller avstand + retning

-- Definition --
Point calculated on the basis of other items, such as two distances or distance + direction.<br />- Vektet middel</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.målemetodeHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for å måle høyden</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MålemetodeHøyde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Aerotriangulert<br />- Analytisk plotter<br />- Annet<br />- Annet (spesifiseres i filhode)<br />- Autograf - vanlig registrering<br />- Beregnet (?)<br />- Digitalt stereoinstrument<br />- Fastsatt ved dom eller kongelig resolusjon<br />- Flybåren laserscanning<br />- Generalisert<br />- Generert i terrengmodell<br />- Generert sirkelgeometri<br />- Genererte data (interpolasjon)<br />- GPS Fasemåling RTK<br />- GPS Fasemåling, andre metoder<br />- GPS Fasemåling, statisk måling.<br />- GPS Kodemåling, enkeltpunktbestemmelser<br />- GPS Kodemåling, relative målinger.<br />- Kombinasjon av GPS/Treghet<br />- Koordinater hentet fra GAB<br />- Koordinater hentet fra JREG (?)<br />- Målt med stigningsmåler<br />- Nivellement<br />- Ortogonalmetoden<br />- Sammenknytningspunkt/randpunkt<br />- Spesielle metoder<br />- Stereoinstrument<br />- Tatt fra plan<br />- Teodolitt med elektronisk avstandsmåler<br />- Teodolitt med målebånd<br />- Terrengmålt<br />- Totalstasjon<br />- Treghetsstedfesting<br />- Ukjent målemetode<br />- Vektet middel</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i [cm]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighetHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nøyaktighet for høyden i [cm]</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

#### Geotekniskmetode (abstrakt)

Abstrakt objekttype for å samle felles-egenskaper for en del geotekniske prøver.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterers. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />NOTE Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

#### GeovitenskapeligUndersøkelse (abstrakt)

geovitenskaplig undersøkelse som utføres innen for et gitt område og tidsperiode og som ofte er knyttet til et prosjekt<br /><br /><br />soil geoscientific investigation of a given area and time period and usually with a connection to a specific project

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av de geovitenskaplige undersøkelsene<br /><br /><br />description of the geoscientific investigations</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>areal som er gjenstand for undersøkelse<br /><br /><br />area coverd by the investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Surface</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdragsgiver</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av bestiller (kunde) og dennes organisasjon<br /><br /><br />identifikation of the the customer organisation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdragstaker</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av utførende organisasjon<br /><br /><br />identification of the the organisation responsible for carrying out the project</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>prosjektNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>prosjekt navn og/eller nummer<br /><br /><br />name or number of the project - e.g. projectnumber</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>sammensattområde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>areal som er gjenstand for undersøkelse<br /><br /><br />area coverd by the investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_MultiSurface</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>undersøkelsePeriodeFra</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>startdato for undersøkelsen<br /><br /><br />starting date of the investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>undersøkelsePeriodeTil</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sluttdato for undersøkelsen<br /><br /><br />ending date of the investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Supertype_Geotekn_obj_omr

#### GeovitenskapligBorehullUndersøkelse (abstrakt)

et enkelt fysisk undersøkelsespunkt som inneholder beskrivelsen av borehullforløpet<br /><br />Merknad: Flere undersøkelser kan tilhøre det samme borehullet, men det er undersøkelsen som representerer de enkelte sonderinger / boringer.<br /><br />a pysical borehole which contain a description of the borehole geometry Note: Several investigations can belong to the same borehole, and it is the investigation which contain the geometry along the borehole.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boreBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forklaring av hva som er utført og/eller observert i denne undersøkelsen<br /><br /><br />a general description of actions performed and/or observed in this investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>borehullForløp</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>detaljert beskrivelse av borhullets geometri, dvs. et en-dimensjonalt referansesystem nedover i senterlinjen av borehullet<br /><br /><br />detailed description of the borehole geometry, i.e. a one-dimensional reference system along the borehole centerline</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretAzimuth</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>vinkelen mellom en referansevektor i et referanseplan og en annen vektor i det samme planet som peker mot noe av interesse [°]<br /><br /><br />The vector from an observer (origin) to a point of interest is projected perpendicularly onto a reference plane, the angle between the projected vector and the reference vector on the reference plane is called the azimuth</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretHelningsgrad</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>helning hvor 90 grader er vertikalt, 0 grader er horisontalt [°]<br /><br /><br />the inclination of the borehole<br /><br />Note: 90 degrees represent the vertical inclination and 0 degrees the horizontal</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>total lengde av borehullets forløp, tilsvarer dyp ved vertikal boring [m]<br /><br /><br />total length of the investigation in the physical borehole, the same as depth in a vertical borehole</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dybde til fjell som ikke er målt men basert på tolkning<br /><br /><br />depth to bedrock based on interpretation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BorlengdeTilBerg</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg.borlengdeKvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver om dybden til berg er antatt eller påvist med en sikker metode<br /><br /><br />defines the quality of the depth information either assumed or confirmed by a secure method</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>KvalitetBorlengdeTilBerg</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- antatt – usikker angivelse av dybde til berg

&lt;engelsk&gt;
uncertain depth to rock
&lt;/engelsk&gt;<br />- påvist – sikker angivelse av dybde til berg

&lt;engelsk&gt;
confirmed depth to rock
&lt;/engelsk&gt;</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg.borlengdeTilBerg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dybde til fjell som ikke er målt men basert på tolkning [m]<br /><br /><br />depth to bedrock based on interpretation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dybdeFraGittPosisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>avstanden fra måleutstyret og ned til det punkt på jordoverflaten hvor boring/måling faktisk starter [m]<br /><br />Merknad: Borehullundersøkelsens posisjon er vanligvis angitt med x,y,z-koordinat. Disse verdiene representerer vanligvis et punkt på jordoverflaten. Dybden fra denne gitte posisjon vil da være 0. Hvis boringen derimot er utført fra flåte,  skip eller is, er det viktig at dybdeFraGittPosisjon blir angitt. Denne vil da være avstanden fra måleutstyrets senter (0 dybde) og ned til havbunnen, innsjøbunnen eller elvebunnen hvor sonderingen/boringen faktisk starter fra).<br /><br /><br />distance from the drill or measure equipment down to the vertical level where the borehole/measurement actually begins<br /><br />Note: This is important to specify if the drilling/sounding is performed from e.g. a raft, ship or from ice. The depth will then be the depth from the measuring equipments origin (0 depth) and down to where drilling/sounding actually begins (on the sea surface, bottom of a lake or river, etc.)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dybdeFraVannoverflaten</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>den lengden hvor sonderingsutstyret befinner seg i vann [m]<br /><br />Merknad: Av spesiell interesse hvis boring er utført fra is eller fra flåte/skip.<br /><br /><br />free water depth at the location of the sounding [m]<br /><br />Note: Of special interest if drilling is performed from raft or ice.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lenkeTilTileggsinfo</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke til hvor en finner tilleggsinformasjon om borehullsundersøkelsen<br /><br />Merknad: URL/URI for aktuelt dokument, bilde, video etc.<br /><br /><br />link to extra information about the borehole investigation<br />Note: URL/URI for the particular document, picture, video</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>opphav</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering<br /><br /><br />reference to copyright, source, organization/publication source<br /><br />Note: May also include name of person and cause of update</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning gitt i x,y,z.<br /><br />Merknad: Den virkelige posisjonen til denne borehullsundersøkelsen.<br /><br /><br />The position of the investigation, determined by its x,y and z.<br /><br />Note: The origin (coordinate system/projection) of the position must be specified.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>undersøkelseSlutt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tidspunkt for stopp av undersøkelsen<br /><br />end time/date for the investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>undersøkelseStart</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tidspunkt for start av undersøkelsen<br /><br />start time/date for the investigation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>værforholdVedBoring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av værforhold under utførelsen av borehullundersøkelsen<br /><br />Weather conditions - general description.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Supertype_Geotekn_obj_pkt

#### GeotekniskSondering (abstrakt)

metode som brukes i en grunnundersøkelse for å måle penetrasjonsmotstanden i de forskjellige jordlag method used in a ground investigation to measure the penetration resistance of various soil layers

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fraBorlengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lengde målt fra toppen av kurven/linja som beskriver borehullforløpet [m] distance measured from the top of  the curve describing the borehole geometry</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tilBorlengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lengde målt fra toppen av kurven/linja som beskriver borehullforløpet [m] distance measured from the top of  the curve describing the borehole geometry</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>torvTykkelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tykkelse på torvlag i meter [m] thickness of peat in meter</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Geotekniskmetode

#### GeovitenskapligBorehull (abstrakt)

område representert ved et punkt hvor det skal foretas en eller flere borehullundersøkelser - også kalt logisk borehull i motsetning til borhullundersøkelse som representerer hvert fysiske borehull<br /><br />Merknad: Det logiske borehullet har en posisjon som representerer de fysiske borhullundersøkelsene foretatt i området<br /><br /><br />borehole consists of one or more physical borehole investigations. The borehole has a position, representing a collection of borehole investigations. The position of the borehole is often given the same position as one of the asscoated borehole investigations. The associated borehole investigations should be in a reasonable short distance (e.g. 0,5 m) from the position of the borehole.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallBorehullUndersøkelser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antall borehullsundersøkeelser i borehullets område<br /><br />Merknad: Borhullet er et logisk borhull hvor det innen et lite område er foretatt flere fysiske borhullsundersøkelser som tilhører det samme borehull.<br /><br /><br />Number of boreholeInvestigations (virtual boreholes) performed at the location of the borehole<br /><br />Note: A virtual borehole is a fictitious feature for all boreholes/soundings performed within an reasonable small area (e.g.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>beskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forklaring til objektet og undersøkelser utført på lokaliteten<br /><br /><br />a short description of the investigations at the location of the borehole</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dybde til berg som ikke er målt men basert på tolkning<br /><br /><br />depth to bedrock based on interpretation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BorlengdeTilBerg</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg.borlengdeKvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver om dybden til berg er antatt eller påvist med en sikker metode<br /><br /><br />defines the quality of the depth information either assumed or confirmed by a secure method</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>KvalitetBorlengdeTilBerg</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- antatt – usikker angivelse av dybde til berg

&lt;engelsk&gt;
uncertain depth to rock
&lt;/engelsk&gt;<br />- påvist – sikker angivelse av dybde til berg

&lt;engelsk&gt;
confirmed depth to rock
&lt;/engelsk&gt;</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>boretLengdeTilBerg.borlengdeTilBerg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dybde til fjell som ikke er målt men basert på tolkning [m]<br /><br /><br />depth to bedrock based on interpretation</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>gjennomboretMedium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>material som er gjennomboret<br /><br />Merknad: spesifisert ved å bruke kodeliste GjennomboretMedium.<br /><br /><br />material penetrated by the borehole<br /><br />Note: Specified by using codes from codelist: GjennomboretMedium</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GjennomboretMedium</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Berg – berggrunn/fjell

&lt;engelsk&gt;
bedrock
&lt;/engelsk&gt;<br />- Is – is

&lt;engelsk&gt;
ice
&lt;/engelsk&gt;<br />- Luft – luft

&lt;engelsk&gt;
air
&lt;/engelsk&gt;<br />- Løsmasse – løsmasse

&lt;engelsk&gt;
uncompacted material
&lt;/engelsk&gt;<br />- Uspesifisert – medium/material er ikke angitt

&lt;engelsk&gt;
medium/material is undefined
&lt;/engelsk&gt;<br />- Vann – vann

&lt;engelsk&gt;
water
&lt;/engelsk&gt;</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted objektet eksisterer på bestemt av måleutstyr<br /><br /><br />the actual position of the object determined by a measuring device</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Supertype_Geotekn_obj_pkt

#### GeovitenskapeligUndersøkelseGrense (abstrakt)

avgrensning av et område for en geovitenskapelig undersøkelse<br /><br />boundary of geoscientific investigation

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>grense</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger overgang mellom ulike fenomener</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
    </tr>
  </tbody>
</table>

### Kodelister

#### «Enumeration» NADAG_Høyderef

**Definisjon:** Brukte høydereferansesystemer i NADAG for egenskapen Høyde. EPSG-koder benyttes.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>NN2000</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>NN54</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent høydereferanse</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» KvikkleirePåvisningKode

**Definisjon:** Koder for grad av sikkerhet for påvisning av kvikkleire eller sprøbruddmateriale

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Antatt</td>
      <td>Benyttes ved sondering</td>
      <td></td>
    </tr>
    <tr>
      <td>AntattIkkeKvikk</td>
      <td>Benyttes ved sondering</td>
      <td></td>
    </tr>
    <tr>
      <td>IkkeVurdert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sikker</td>
      <td>Kan kun benyttes der kvikkleire eller sprøbruddmateriale er påvist ved prøvetaking</td>
      <td></td>
    </tr>
    <tr>
      <td>Usikker</td>
      <td>Benyttes ved sondering</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» KvalitetBorlengdeTilBerg

**Definisjon:** beskriver om borlengde til berg er antatt eller påvist med en sikker metode

&lt;engelsk&gt;
defines the quality of the depth information either assumed or confirmed by a secure method
&lt;/engelsk&gt;

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>antatt</td>
      <td>usikker angivelse av dybde til berg

&lt;engelsk&gt;
uncertain depth to rock
&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>påvist</td>
      <td>sikker angivelse av dybde til berg

&lt;engelsk&gt;
confirmed depth to rock
&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» NADAG_DokumentType

**Definisjon:** Typer av dokument brukt i NADAG forvaltningsløsning.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Andre vedlegg til borehull</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bilde</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bilde borehullsprofil</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bilde koblet til digitalisert DWG tegning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert DWG tegning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Geoteknisk rapport</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Labrapport</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Modell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Opptegningssymbol</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Plantegning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Profiltegning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rådatafil</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tegning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Uspesifisert dokumenttype</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vurderingsrapport</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» GeotekniskMetodeKode

**Definisjon:** Kode for metoder benyttet ved geotekniske borehullundersøkelser

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Bergkontrollboring</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Blokkprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dilatometertest</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dreiesondering manuell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dreiesondering maskinell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dreiesondering uspesifisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dreietrykksondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dynamisk sondering uspesifisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Elektrisk sondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Enkel sondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gassmåling</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gassprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Graveprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grunnvannsmåling</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hejarsondering A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hejarsondering B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>HK sondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hydraulisk test</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ikke angitt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jord-berg sondering 1</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jord-berg sondering 2</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jord-berg sondering 3</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kanneprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kjerneboring</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kjerneprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kombinasjonssondering uspesifisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kombisondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Miljøundersøkelse</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Naverprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Platebelastning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Poretrykksmåling</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Prøve uspesifisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Prøveserie uspesifisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ramprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ramsondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ramsondering A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ramsondering B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sedimentprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skovlprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Slagsondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>SPT</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Statisk sondering uspesifisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stempelprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stikksondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Totalsondering Norge</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Totalsondering Sverige</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Trykksondering (CPT, CPTU)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vannprøve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vektsondering manuell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vektsondering maskinell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vingeboring</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» GeotekniskStoppkode

**Definisjon:** oversikt over koder for stopp av boring ved utførelse av en grunnundersøkelse &lt;engelsk&gt;overview of codes for termination of boring in a ground investigation&lt;/engelsk&gt;

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>AntattBerg</td>
      <td>kode for avslutning av boring i antatt berg &lt;engelsk&gt;code for termination of boring in presumed rock&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>AntattSteinBlokk</td>
      <td>kode for avslutning av boring i antatt stein eller blokk &lt;engelsk&gt;code for termination of boring in presumed stone or block&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>BruddBorstangSpiss</td>
      <td>kode for avslutning av boring ved brudd i borstang eller borspiss &lt;engelsk&gt;code for termination of boring due to failure of drill rod or drill bit&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>DybdeIBergOppnådd</td>
      <td>kode for avslutning av boring ved oppnådd boredybde i berg &lt;engelsk&gt;code for termination of boring after assumed depth in rock&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>DybdeIFjellMerEnn3Meter</td>
      <td>kode for avslutning av boring ved oppnådd boredybde i berg større enn 3 m &lt;engelsk&gt;code for termination of boring after assumed depth in rock greater than 3 m&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>DybdeIFjellMerEnn3MeterMedAnalyse</td>
      <td>kode for avslutning av boring ved oppnådd boredybde i berg større enn 3 m og borestøv har blitt analysert &lt;engelsk&gt;code for termination of boring after assumed depth in rock greater than 3 m and the drill cuttings have been analysed&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>KjerneBoringMerEnn3Meter</td>
      <td>Det har blitt tatt ut en kjerneprøve på minimum 3 meter&lt;engelsk&gt; core drilling min 3 meter&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>MaterialEllerMaskinFeil</td>
      <td>kode for avslutning av boring ved feil på borustyr &lt;engelsk&gt;code for termination of boring due to equipment errors&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>SonderingAvbrutt</td>
      <td>kode for avslutning av boring ved avbrutt sondering &lt;engelsk&gt;code for termination of boring due to interrupted sounding&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>SonderingAvbruttFastGrunn</td>
      <td>kode for avslutning av boring i fast grunn &lt;engelsk&gt;code for termination of boring in firm ground&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>SonderingAvsluttetUtenStopp</td>
      <td>kode for avslutning av sondering uten stopp &lt;engelsk&gt;code for termination of sounding without stop&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>SteinBlokkFjell</td>
      <td>kode for avslutning av boring i stein, blokk eller berg &lt;engelsk&gt;code for termination of boring in presumed stone, block or rock&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Uspesifisert</td>
      <td>kode for avslutning av boring ved uspesifisert årsak &lt;engelsk&gt;code for termination of boring due to unspecified reasons&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» FeltUndersTypeKode

**Definisjon:** Kodeliste for feltundersøkelsestype

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/sosi/produktspesifikasjon/grunnundersoekelse/1.0/GeotekniskMetodeKode.xml">http://skjema.geonorge.no/sosi/produktspesifikasjon/grunnundersoekelse/1.0/GeotekniskMetodeKode.xml</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FeltUndersMetode</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tolket</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TolketBerghøyde</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» GeotekniskFeltUndersMetodeKode

**Definisjon:** Koder for metoder benyttet ved geotekniske feltundersøkelser

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>BelastningTest</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ElektriskSondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>HelningMåling</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>PermeabilitetMåling</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ramsondering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>SetningMåling</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skovlboring</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skrueplate</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>SPT</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» TolkningMetodeKode

**Definisjon:** Metoder benyttet for tolkning av geotekniske feltundersøkelser

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>+Le</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>BG</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>BH</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>F</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» HovedLagKlassifisering

**Definisjon:** oversikt over lagdeling og jordart for klassifisering og identifisering av grunnforhold&lt;engelsk&gt;overview of stratification and soil type for classification and identification of ground conditions&lt;/engelsk&gt;

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>False</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>AnnetOrganiskMateriale</td>
      <td>annet organisk materiale&lt;engelsk&gt;other organic materials&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>AntattForurensning</td>
      <td>antatt forurenset materiale&lt;engelsk&gt;assumed contaminated material&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Berg</td>
      <td>berg&lt;engelsk&gt;rock&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>BergEllerBlokk</td>
      <td>Berg eller blokk&lt;engelsk&gt;Rock or boulders&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Blokk</td>
      <td>blokk (fraksjoner større enn 200 mm)&lt;engelsk&gt;boulders (fractions &gt; 200 mm&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>BlokkigOgSteinigMorene</td>
      <td>Blokkig og steinig morene &lt;engelsk&gt;Boulder and Cobble till &lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>DelvisFibrigTorv</td>
      <td>Delvis fibrig torv. Gjenkjennelig plantestruktur, ingen styrke i planterestene&lt;engelsk&gt;Pseudo-fibrous peat&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Dy</td>
      <td>dy (Dy består av vannavsatte plante- og dyrerester og er en strukturløs masse)&lt;engelsk&gt;organic material consisting of plant and animal debris sedimented in water. The material is not showing a special structure&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>FibrigTorv</td>
      <td>Fibrig torv. Fibrig struktur, lett gjenkjennelig plantestruktur, viser noe styrke,&lt;engelsk&gt; Fibrous peat&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>ForvitretTorv</td>
      <td>forvitret torv (Torv er mer eller mindre omvandlede planterester, klassifiseres etter von Post skala)&lt;engelsk&gt;weathered peat (Peat is more or less transformed plant debris and is classified according to the von Post scale)&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Friksjonsjord</td>
      <td>friksjonsjord&lt;engelsk&gt;non-cohesive soil &lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Fyllmasse</td>
      <td>fyllmasse&lt;engelsk&gt;fill mass&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Grus</td>
      <td>grus (fraksjoner mellom 2,0 og 63 mm)&lt;engelsk&gt;gravel (fractions between 2,0 and 63 mm&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>GrusigMorene</td>
      <td>Grussig morene&lt;engelsk&gt;Gravel till&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Gytje</td>
      <td>gytje (Gytje består av vannavsatte plante- og dyrerester og viser vanligvis organisk struktur)&lt;engelsk&gt;organic material consisting of plant and animal debris. The material usually shows a special structure&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>GytjeOgLeire</td>
      <td>leirblandet gytje (organisk materiale )&lt;engelsk&gt;organic material consisting of plant, animal debris and clay.&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Humus</td>
      <td>humus (Humus er en fellesbetegnelse på organisk materiale i jordarter)&lt;engelsk&gt;common denotation of organic matter in soils&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Jord</td>
      <td>Jord&lt;engelsk&gt;soil&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Kohesjonsjord</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kull</td>
      <td>kull&lt;engelsk&gt;coal&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Kvikkleire</td>
      <td>kvikkleire (omrørt skjærfasthet &lt; 0,5 kPa)&lt;engelsk&gt;quick clay (remoulded shear strength &lt; 0,5 kPa)&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Leire</td>
      <td>leire (materiale med mer enn 30 % i leirfraksjonen &lt; 2 µm)&lt;engelsk&gt;clay (material with more than 30 % in the clay fraction &lt; 2 µm)&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>LeirigMorene</td>
      <td>Leirig morene&lt;engelsk&gt;Clay till&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Matjord</td>
      <td>matjord &lt;engelsk&gt;humus&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Morene</td>
      <td>morene&lt;engelsk&gt;glacial deposit&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>OppsprukketBerg</td>
      <td>oppsprukket berg&lt;engelsk&gt;jointed rock&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Planterester</td>
      <td>planterester&lt;engelsk&gt;plant remnants&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Sand</td>
      <td>Sand (fraksjoner mellom 0,063 og 2,0 mm)&lt;engelsk&gt;sand (fractions between  0,063 and 2,0 mm&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>SandigMorene</td>
      <td>Sandig morene&lt;engelsk&gt;Sand till&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Silt</td>
      <td>silt (fraksjoner mellom 0,002 og 0,063 mm)&lt;engelsk&gt;silt (fractions between 0,002 and 0,063 mm&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>SiltigMorene</td>
      <td>Siltig morene&lt;engelsk&gt;Silt till&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Skjell</td>
      <td>Skjell&lt;engelsk&gt;Shells&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Skjellgrus</td>
      <td>skjellgrus&lt;engelsk&gt;coquina&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Skjellsand</td>
      <td>skjellsand&lt;engelsk&gt;shellsand&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Stein</td>
      <td>Stein&lt;engelsk&gt;Cobbles&lt;/engelsk&gt;
stein (fraksjoner mellom 63 og 200 mm)&lt;engelsk&gt;cobbles (fractions between 63 and 200 mm&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>SteinigMorene</td>
      <td>Steinig morene&lt;engelsk&gt;Cobble till&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>SulfidholdigJord</td>
      <td>suldidholdig sand&lt;engelsk&gt;sulphide sand&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Torv</td>
      <td>torv&lt;engelsk&gt;peat&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>TørrskorpeLeire</td>
      <td>tørrskorpe leire&lt;engelsk&gt;crusty clay&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>UkjentMateriale</td>
      <td>Ukjent materiale &lt;engelsk&gt;Unknown material&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>UspesifisertMateriale</td>
      <td>uspesifisert materiale&lt;engelsk&gt;unspecified material&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» KlassifiseringsMetode

**Definisjon:** oversikt over klassifiseringsmetoder for bestemmelse av grunnforhold&lt;engelsk&gt;overview of classification methods for determination of ground conditions&lt;/engelsk&gt;

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>BeregnetFraTerrengoverflaten</td>
      <td>beregnet størrelse fra terrengoverflaten&lt;engelsk&gt;calculated from the terrain surface&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Observasjon</td>
      <td>tolket fra observasjon&lt;engelsk&gt;interpreted from observation&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>TolketBergBoring</td>
      <td>tolket fra boring i berg&lt;engelsk&gt;interpreted from drilling in rock&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>TolketBergBoring3Meter</td>
      <td>tolket fra boring 3 m inn i berg&lt;engelsk&gt;interpreted from boring 3 m into rock&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>TolketFeltsondering</td>
      <td>tolket fra sondering i felt&lt;engelsk&gt;interpreted from sounding in the field&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>TolketLab</td>
      <td>tolket fra prøving i laboratoriet&lt;engelsk&gt;interpreted from testing in the laboratory&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>TolketPrøvetak</td>
      <td>tolket fra prøvetaking i felt&lt;engelsk&gt;interpreted from sampling in the field&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>TolketTegning</td>
      <td>tolket fra tegning&lt;engelsk&gt;interpreted from drawing&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Uspesifisert</td>
      <td>uspesifisert tolkningskilde&lt;engelsk&gt;unspecified source of interpretation&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Målemetode

**Definisjon:** metode som ligger til grunn for registrering av posisjon


-- Definition - -
method on which registration of position is based

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Aerotriangulert</td>
      <td>(Pkt. beregnet v/ aerotriangulering)

-- Definition --
Point calculated by aerotriangulation</td>
      <td></td>
    </tr>
    <tr>
      <td>Analytisk plotter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annet  (denne har ingen mening, bør fjernes?)</td>
      <td>Annet</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet (spesifiseres i filhode) ( bør vel fjernes, blir borte ved overføring mellom systemer)</td>
      <td>Annet (spesifiseres i filhode)</td>
      <td></td>
    </tr>
    <tr>
      <td>Autograf - vanlig registrering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Beregnet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dig. på skjerm fra scannet samkopi</td>
      <td>(Raster)</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert fra flybilde - monodigitalisert fra film</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert fra flybilde - monodigitalisert fra fotokopi</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert fra krokering på kart</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert fra ortofoto</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert fra ortofoto - film</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert fra ortofoto - fotokopi</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på dig.bord fra blyantoriginal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på dig.bord fra ortofoto/flybilde</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på dig.bord fra papirkopi</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på dig.bord fra rissefolie</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på dig.bord fra strek-kart</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på dig.bord fra transparent film - god kvalitet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på dig.bord fra transparent film - mindre god kvalitet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra satellittbilde</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalt stereoinstrument</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Direkte innlagt på skjerm</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fastsatt punkt</td>
      <td>punkt fastsatt ut fra et grunnlag f.eks ved partenes enighet ved oppmålingsforretning.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fastsatt ved dom eller kongelig resolusjon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flybåren laserscanner</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Frihåndstegning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Generalisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Generert i terrengmodell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Generert sentralpunkt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Generert sirkelgeometri</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Fasemåling RTK</td>
      <td>(Realtids kinematisk måling). Tidligere GPS kinematisk (Real time kinematic)

-- Definition --
(Real time kinematic measurement). Previous GPS kinematic (Real time kinematic)</td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Fasemåling, andre metoder</td>
      <td>(utenom RTK). Tidligere GPS-Absolutt, fase

-- Definition --
(not including RTK). Previous Absolute GPS, phase</td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Fasemåling, float-løsning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Fasemåling, statisk måling</td>
      <td>Tidligere GPS, Differensiell

-- Definition --
Previous GPS, differential</td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Kodemåling, enkeltmålinger</td>
      <td>Tidligere GPS, Absolutt, pseudorange

-- Definition --
Previous GPS, absolute, pseudorange</td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Kodemåling, relative målinger</td>
      <td>Tidligere GPS-Differensiell, pseudorange

-- Definition --
Previous GPS differential, pseudorange</td>
      <td></td>
    </tr>
    <tr>
      <td>Kombinasjon av GPS/Treghet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Koordinater hentet fra GAB</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Koordinater hentet fra JREG</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Målt med målehjul</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Målt med stigningsmåler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Målt med stikkstang</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Målt med waterstang</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ortogonalmetoden</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sammenknytningspunkt/randpunkt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Scannet fra blyantoriginal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Scannet fra kart</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Scannet fra papirkopi</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Scannet fra rissefolie</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Scannet fra transparent folie - god kvalitet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Scannet fra transparent folie - mindre god kvalitet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tatt fra plan</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Teodolitt med elektronisk avstandsmåler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Teodolitt med målebånd</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Totalstasjon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Treghetsstedfesting</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent målemetode</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Utmål</td>
      <td>Punkt beregnet på bakgrunn av andre punkter, slik som to avstander eller avstand + retning

-- Definition --
Point calculated on the basis of other items, such as two distances or distance + direction.</td>
      <td></td>
    </tr>
    <tr>
      <td>Vektet middel</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» MålemetodeHøyde

**Definisjon:** metode for å måle objekttypens høydeverdi

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Aerotriangulert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Analytisk plotter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annet (spesifiseres i filhode)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Autograf - vanlig registrering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Beregnet (?)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalt stereoinstrument</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fastsatt ved dom eller kongelig resolusjon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flybåren laserscanning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Generalisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Generert i terrengmodell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Generert sirkelgeometri</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Fasemåling RTK</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Fasemåling, andre metoder</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Fasemåling, statisk måling.</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Kodemåling, enkeltpunktbestemmelser</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Kodemåling, relative målinger.</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kombinasjon av GPS/Treghet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Koordinater hentet fra GAB</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Koordinater hentet fra JREG (?)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Målt med stigningsmåler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nivellement</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ortogonalmetoden</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sammenknytningspunkt/randpunkt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tatt fra plan</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Teodolitt med elektronisk avstandsmåler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Teodolitt med målebånd</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Totalstasjon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Treghetsstedfesting</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent målemetode</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vektet middel</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» RepresentasjonKvalitet

**Definisjon:** Angir hva avgrensningen/polygonen for en geoteknisk undersøkelse fysisk representerer.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Polygon for GU med kun et enkelt borehull (100x100m)</td>
      <td>Polygon for GU med kun et enkelt borehull (100x100m).</td>
      <td></td>
    </tr>
    <tr>
      <td>Polygon hentet  fra borehull i GU, min og  maks koordinater.</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Polygon som avgrenser borehull i GU.</td>
      <td>Avgrensning av en geoteknisk undersøkelse som i hovedsak avgrenser inngående borehull.</td>
      <td></td>
    </tr>
    <tr>
      <td>Polygon som representerer prosjektområde.</td>
      <td>Avgrensning av en geoteknisk undersøkelse som representerer prosjektområde.</td>
      <td></td>
    </tr>
    <tr>
      <td>Representasjonspunkt for kommunalt/regionalt GU-område.</td>
      <td>Avgrensning av en geoteknisk undersøkelse basert på et representasjonspunkt. Her for et område som er av kommunal/regional størrelse.</td>
      <td></td>
    </tr>
    <tr>
      <td>Representasjonspunkt for mindre GU-område. Opptil ca. 10 mål.</td>
      <td>Avgrensning av en geoteknisk undersøkelse basert på et representasjonspunkt. Her for et mindre område, opptil ca 10 mål.</td>
      <td></td>
    </tr>
    <tr>
      <td>Representasjonspunkt for større GU-område. Over ca. 10 mål, eller lengre enn ca. 0,5 km</td>
      <td>Avgrensning av en geoteknisk undersøkelse basert på et representasjonspunkt. Her for et større område, over ca 10 mål eller lenger enn ca. 0,5km.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Hva avvgrensing av geoteknisk undersøkelse representerer er ikke kjent.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» GjennomboretMedium

**Definisjon:** angir hvilket medium en boring er foretatt i

&lt;engelsk&gt;
define what kind of medium/material the borehole has penetrated.&lt;/engelsk&gt;

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Berg</td>
      <td>berggrunn/fjell

&lt;engelsk&gt;
bedrock
&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Is</td>
      <td>is

&lt;engelsk&gt;
ice
&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Luft</td>
      <td>luft

&lt;engelsk&gt;
air
&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Løsmasse</td>
      <td>løsmasse

&lt;engelsk&gt;
uncompacted material
&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Uspesifisert</td>
      <td>medium/material er ikke angitt

&lt;engelsk&gt;
medium/material is undefined
&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Vann</td>
      <td>vann

&lt;engelsk&gt;
water
&lt;/engelsk&gt;</td>
      <td></td>
    </tr>
  </tbody>
</table>

Tabelka w html

<table>
<tr>
	<td><b>Funkcja</b></td>	<td><b>ASCI</b></td>		<td><b>MARKDOWN</b></td>
</tr>
<tr>
	<td>Nagłówek H</td>	<td>====lub==H1</td>		<td></td>
</tr>
<tr>
	<td>Nagłówek H1</td>	<td>----lub ===H2</td>		<td>#</td>
</tr>
<tr>
	<td>Nagłówek H2</td>	<td>~~~~lub ====H3</td>		<td>##</td>
</tr>
<tr>
	<td>Nagłówek H3</td>	<td>^^^^lub =====H4</td>	<td>###</td>
</tr>
<tr>
	<td>Nagłówek H4</td>	<td>++++lub ======H5</td>	<td>####</td>
</tr>
<tr>
	<td>kursywa</td>	<td>_tekst_</td>	<td>*tekst* _tekst_</td>
</tr>
<tr>
	<td>pogrubienie</td>	<td>**tekst**</td>	<td>**tekst**</td>
</tr>
<tr>
	<td>przekreślenie</td>	<td></td>	<td>~~tekst~~</td>
</tr>
<tr>
	<td>zacienienie</td>	<td>+tekst+</td>	<td>``tekst``</td>
</tr>
<tr>
	<td>lista numerowana</td>	<td>. Jeden</td>	<td>1. Jeden</td>
</tr>
<tr>
	<td>Lista kropokowana</td>	<td>- Jeden</td>	<td>- punkt (*lub+)</td>
</tr>
<tr>
	<td>podlista numerowana</td>	<td>.. podpunkt(ile ..taki stopień)</td>	<td> 1/ podpunkt</td>
</tr>
<tr>
	<td>podlista kropki</td>	<td>* podpunkt(ile *** taki stopień)</td>	<td> - podpunkt(* lub +)</td>
</tr>
<tr>
	<td>Linki</td>	<td> h.ttp://adres.pl[nazwa]</td>	<td>[nazwa](www.adres.pl)</td>
</tr>
<tr>
	<td>Linki z "opisem"</td>	<td></td>	<td>[nazwa](www.adres.pl"opis")</td>
</tr>
<tr>
	<td>Link z "przypisem"</td>	<td></td>	<td>tekst[1] [1]:www.adres.pl</td>
</tr>
<tr>
	<td>Obrazek</td>	<td></td>	<td>![alt text](https://adres.pl "Tytył,nazwa")</td>
</tr>

</table>

| FUNKCJA        | ASCUU          | MARKDOWN |
| ------------- |:-------------:| -----:|
| Nagłówek H     | ====== lub ==H | nie ma |
| Nagłówek H1      | ----- lub ===H1      |   # |
| Nagłówek H2 | ~~~~~ lub ====H2      |    ## |
| Nagłówek H3 | ^^^^^ lub =====H3    |    ### |
| Nagłówek H4 | +++++ lub ======H4     |   #### |
|Kursywa | _tekst_    |    ## |
|Pogrubienie | **teskt**  | **tekst**|
|Przekreślenie| brak  |  ~~tekst~~|
|Zacienienie |+tekst+  |   ``tekst`` |
|Lista numerowana |.jeden .dwa   |   1. jeden 2. dwa |
|Lista punktowana| *jeden **dwa     |   - punkt (* lub +)|
|Podlista numerowana|..podpunkt (ile ... taki stopień)  | ⟶ 1. podpunkt|
|Podlusta punkty| * podpuntk (ile ** taki podpunkt)  | ⟶ - podpunkt(* lub +) |
|Link|http://adres.pl [nazawa]   |  [nazwa](www.adres.pl) |



Biegi narciarskie (MARKDOWN)

| Data       | Godzina         | Konkurencja |
| ------------- |:-------------:| -----:|
| 19 lutego    | 15:15|Sprinty s. klasycznym |
| 21 lutego       | 13:00 14:30   | Bieg łączony kobiet 7,5+7,5km 	Bieg łączony mężczyzn 15+15km |
| 22 lutego   |14:30   |  Sprinty drużynowe s. dowolnym |
| 24 lutego   | 13:30 |   10 km s. dowolnym kobiet|
| 25 lutego  |13:30  |  15 km s. dowolnym mężczyzn |
|26 lutego  | 13:30   |    Sztafeta kobiet 4x5 km |
|27 lutego   | 13:30 | Sztafeta mężczyzn 4x10 km|
|28 lutego| 13:00 |  30 km s. klasycznym kobiet (bieg masowy)|
|1 marca |13:30  |  50 km s. klasycznym mężczyzn (bieg masowy) |










<table width="750" align="center" cellspacing="0" cellpadding="10">
<tr>
<td bgcolor="kolor góra" colspan="2" align="center" valign="middle">Tutaj można umieścić logo serwisu</td>
</tr>
<tr>
<td bgcolor="kolor menu" width="150" valign="top">
<!-- MENU -->
<a target="strona" href="home.html">Strona główna</a><br />
<a target="strona" href="strona1.html">Rozdział 1</a><br />
<a target="strona" href="strona2.html">Rozdział 2</a><br />
<a target="strona" href="linki.html">Linki</a><br />
<a href="mailto:jan_kowalski@example.com">Kontakt</a><br>
<!-- MENU koniec -->
</td>
<td bgcolor="kolor strony" valign="top"><iframe name="strona" src="home.html" width="560" height="440" frameborder="0"></iframe></td>
</tr>
</table>

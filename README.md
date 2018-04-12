# Vmesno poročilo

Midva sva se odločila, da bi poiskala najboljšo lokacijo za odprtje avtovleke glede na število nesreč po Sloveniji. Za zbiranje podatkov sva uporabila področje Infrastruktura in promet na strani https://podatki.gov.si/, kjer sva pogledala več različnih datotek, v katerih so zbrani razni podatki o nesrečah. Najprej sva se odločila pogledati skupno število nesreč po letih od 2003 do 2014 (nekateri podatki niso dostopni v istem časovnem intervalu, zadnji podatki so iz leta 2014). 

<p align="center">
  <img src="https://github.com/TheBraveCat/PR18NRMT/blob/master/images/allAccidentsYears.PNG"/>
</p>

Ugotovila sva da se število prometnih nesreč drastično zmanjšuje, kar je tudi po napredku varnostne tehnologije pričakovano. Število prometnih neseč v enem letu se je med letoma 2003 in 2014 zmanjšalo za več kot polovico, kar je zelo dobra novica.

Nato sva pogledala na katerihi tipih cest je največ nesreč. 

<p align="center">
  <img src="https://github.com/TheBraveCat/PR18NRMT/blob/master/images/allAccidentsType.PNG"/>
</p>

Največ nesreč se je zgodilo v naseljih z dodatnimi ulicami, kar je morda pričakovano, saj je tam več ljudi in tudi več stvari dogaja hkrati, zato je lahko pozornost voznikov drastično zmanjšana. Veliko nesreč je tudi na regionalnih oz turističnih (bolj prometnih) cestah, saj so nekatere že zelo stare in obdelano, prav tako pa so zelo ovinkaste. 

Ker je odgovor na najin problem število nesreč z materialno škodo sva si pogledala tudi ta graf, a sva nato ugotovila, da nam ta graf prikazuje samo nesreče, kjer je nastala le materialna škoda brez kakršnih poškodb. To pa nama ne pomaga preveč, saj potrebujeva informacije o vseh nesrečah pri katerih je potrebno posredovanje avtovleke. 

Zanima pa naju tudi pogostost cestnoprometnih nesreč glede na regijo zato sva si izrisala tudi ta graf. 

<p align="center">
  <img src="https://github.com/TheBraveCat/PR18NRMT/blob/master/images/allAccidentsRegions.PNG"/>
</p>

Ugotovila sva, da se največ nesreč dogaja v Osrednjeslovenski regiji, kar ni nič presenetljivega glede na to, da je gostota prebivalstva na tem območju največja.

Nato sva pogledala število nesreč, ki so se zgodile samo v tej regiji skozi leta (tukaj podatki niso dostopni od leta 2003 do 2006).


<p align="center">
  <img src="https://github.com/TheBraveCat/PR18NRMT/blob/master/images/accidentsInOsrednjeslovenska.PNG"/>
</p>

Za nadalnje ugotovitve in odgovore na naša vprašanja sva si tudi pripravila podatke o podjetjih in njihovih lokacijah za urejanje registracij in izvajanje tehničnih pregledov. Pri pripravi teh podatkov sva naletela na nekaj "nevšečnosti", saj se je v datoteko prikradel tiskarski škrat in vstavil nekaj elementov, ki jih codec utf-8 ni znal razbrati. Napako sva odpravila tako, da sva ročno pregledala datoteko in take elemente odstranila.

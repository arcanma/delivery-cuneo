

dati ricavati con query overpass:

{{geocodeArea:Perugia, Perugia}}->.searchArea;
(
  nwr["delivery:covid19"="yes"](area.searchArea);
);
out center;
>;


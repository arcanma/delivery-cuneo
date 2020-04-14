

dati ricavati con query overpass:

{{geocodeArea:Perugia, Perugia}}->.searchArea;
(
  nwr["delivery"][delivery!=no](area.searchArea);
  nwr["delivery:covid19"]["delivery:covid19"!="no"](area.searchArea);
);
out center;
>;

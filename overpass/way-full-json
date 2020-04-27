[out:json][timeout:300];
(
    area["name"="Београд"]["place"="city"];
)->.a;
(
    way["highway"]["name"]["highway"!="bus_stop"]["highway"!="service"](area.a);
    way["place"="square"]["name"](area.a);
);
out body;
>;
out skel qt;



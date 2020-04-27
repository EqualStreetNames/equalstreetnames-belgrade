/**
 * Get all the relevant relations in Brussels Region.
 */
[out:json][timeout:300];
(
  area["name"="Београд"]["place"="city"];
) -> .a;
(
    relation["type"="street"](area.a);
    relation["type"="multipolygon"]["place"]["name"](area.a);
    relation["type"="multipolygon"]["highway"]["name"](area.a);
);
out body;
>;
out skel qt;

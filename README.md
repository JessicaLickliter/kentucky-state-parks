# kentucky-state-parks
Map notating all State Parks in Kentucky
Got information on Ky County lines and State Park boundaries from openisdata.ky.gov
Tree Icon is from iconpacks.net
I made this map because of how important I believe State Parks. It is my hope to be able to visit all of them and having a map will be handy for that.
I uploaded files from openisdata.ky.gov into tiles on Mapbox
I then doublicated the tile set for state park boundaries and changed it to an icon
I changed what you would see based on the zoom

// 
mapboxgl.acessToken = 'pk.eyJ1IjoiamVzc2ljYWxpY2tsaXRlciIsImEiOiJjbW9jN3NrazUwOWViMnNxMXRrcHZtaW9qIn0.hfi6DW739PZbY6LdpMKkJg'; //
// 

var map = new mapboxgl.Map({
container: 'map',

// 
style: 'mapbox://styles/jessicalickliter/cmohutnhb003501s67qd21diz', //
//

//
zoom:6.30
center: [-84.967448, 37.665919]
//

<!DOCTYPE html>
<html>
  <head>
    <title>Telkom University</title>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=default"></script>
    <link rel="stylesheet" type="text/css" href="./style.css" />
    <script src="./index.js"></script>
  </head>
  <body>
    <div id="map"></div>
    <script>   
 function initMap() {
        var directionsDisplay = new google.maps.DirectionsRenderer;
        var directionsService = new google.maps.DirectionsService;
        var map = new google.maps.Map(document.getElementById('map'), {
          zoom: 16.53,
          center: {lat: -6.97395, lng: 107.631057},
          mapTypeId: 'terrain'
        });
        directionsDisplay.setMap(map);
        directionsDisplay.setPanel(document.getElementById('right-panel'))};
    function initMap() {
    const map = new google.maps.Map(document.getElementById("map"), {
    zoom: 16.53,
    center: { lat: -6.97395, lng: 107.631057 },
    mapTypeId: "terrain",
  });

  
  
  // BATAS
  const batasCoords = [
    { lat: -6.9739251, lng: 107.6326182 },
    { lat: -6.9726791, lng: 107.6339003 },
    { lat: -6.9725354, lng: 107.6339486 },
    { lat: -6.9724076, lng: 107.6338789 },
    { lat: -6.9721866, lng: 107.633734 },
    { lat: -6.971316, lng: 107.6324519 },
    { lat: -6.9704587, lng: 107.6312127 },
    { lat: -6.970315, lng: 107.6309982 },
    { lat: -6.9696866, lng: 107.6307568 },
    { lat: -6.9695109, lng:  107.6299467 },
    { lat: -6.9691861, lng: 107.6285895 },
    { lat: -6.9684673, lng: 107.6284286 },
    { lat: -6.9684939, lng: 107.6275435 },
    { lat: -6.9695269, lng: 107.6276508 },
    { lat: -6.9702191, lng:  107.6267871 },
    { lat: -6.9712787 , lng: 107.6267549  },
    { lat: -6.9713799 , lng: 107.6284608 },
    { lat: -6.9731797, lng: 107.6282516 },
    { lat: -6.973792, lng: 107.6280155 },
    { lat: -6.9741701, lng: 107.6280799 },
    { lat: -6.9751285, lng:107.628906 },
    { lat: -6.9762148, lng: 107.6289543 },
    { lat: -6.9777909 , lng: 107.6289811 },
    { lat: -6.9777004, lng: 107.629598 },
    { lat: -6.9777483, lng: 107.6303759 },
    { lat: -6.9778654 , lng: 107.6311054 },
    { lat: -6.9773862, lng: 107.6316258 },
    { lat: -6.9761136 , lng: 107.6329293 },
    { lat: -6.9755705, lng: 107.6329615 },
    { lat: -6.9751605, lng: 107.6326343 },
    { lat: -6.9748144, lng: 107.6325163 },
    { lat: -6.9739251, lng: 107.6326182 },

  ];
  const batas = new google.maps.Polygon({
    paths: batasCoords,
    strokeColor: "#000000",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#000000",
    fillOpacity: 5,
  });

  batas.setMap(map);

  // parkiran motor gate4
  const parkiranmotorgate4Coords = [
    { lat: -6.9761466, lng: 107.6317364 },
    { lat: -6.9765087, lng: 107.6317377 },
    { lat: -6.9765047, lng: 107.6322433 },
    { lat: -6.9761453, lng: 107.6322459 },
    { lat: -6.9761466, lng: 107.6317364 },

  ];
  const parkiranmotor = new google.maps.Polygon({
    paths: parkiranmotorgate4Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

  parkiranmotor.setMap(map);

    // Bandung Techno Park
    const bandungtechnoparkCoords = [
    { lat: -6.9703106, lng: 107.6301736 },
    { lat: -6.9703159, lng: 107.6301454 },
    { lat: -6.9703252, lng: 107.6301253 },
    { lat: -6.9703505, lng: 107.6301052 },
    { lat: -6.9703758, lng: 107.6300958 },
    { lat: -6.9703998, lng: 107.6300985 },
    { lat: -6.970445, lng: 107.6301159 },
    { lat: -6.970473, lng: 107.6301387 },
    { lat: -6.9704983, lng: 107.6301642 },
    { lat: -6.9705143, lng: 107.6301991 },
    { lat: -6.9705289, lng: 107.6302339 },
    { lat: -6.9705316, lng: 107.6302702 },
    { lat: -6.9705223, lng: 107.630305 },
    { lat: -6.970501, lng: 107.6303238 },
    { lat: -6.9704823, lng: 107.6303345 },
    { lat: -6.9704477, lng: 107.6303386 },
    { lat: -6.9704184, lng: 107.6303318 },
    { lat: -6.9703945, lng: 107.6303171 },
    { lat: -6.9703585, lng: 107.6302916 },
    { lat: -6.9703279, lng: 107.6302474 },
    { lat: -6.9703106, lng: 107.6302058 },
    { lat: -6.9703106, lng: 107.6301736 },

  ];
  const bandungtechnopark = new google.maps.Polygon({
    paths: bandungtechnoparkCoords,
    strokeColor: "#00FFFF",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00FFFF",
    fillOpacity: 5,
  });

  bandungtechnopark.setMap(map);

  // RuangRiung
  const ruangriungCoords = [
    { lat:-6.974332, lng: 107.6289569 },
    { lat: -6.9745596, lng: 107.6289596 },
    { lat: -6.9745583, lng: 107.6290266 },
    { lat: -6.9743346, lng: 107.629024 },
    { lat: -6.974332, lng: 107.6289569 },

  ];
  const ruangriung = new google.maps.Polygon({
    paths: ruangriungCoords,
    strokeColor: "#FFA500",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFA500",
    fillOpacity: 5,
  });

  ruangriung.setMap(map);

// sporthall
const sporthallCoords = [
    { lat: -6.9717365, lng:  107.6285497 },
    { lat: -6.9717392, lng: 107.628893 },
    { lat: -6.9713744, lng: 107.6288904 },
    { lat: -6.9713744, lng: 107.6286892 },
    { lat: -6.9713478, lng: 107.6286892 },
    { lat: -6.9713478, lng: 107.6285712 },
    { lat: -6.9713744, lng: 107.6285685 },
    { lat: -6.9713771, lng: 107.6285497 },
    { lat: -6.9717365, lng: 107.6285497 },

  ];
  const sporthall = new google.maps.Polygon({
    paths: sporthallCoords,
    strokeColor: "#008000",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#008000",
    fillOpacity: 5,
  });

  sporthall.setMap(map);

  // kantincewek
  const kantincewekCoords = [
    { lat: -6.974091, lng: 107.6291878 },
    { lat: -6.9743306, lng: 107.6291476 },
    { lat: -6.9743466, lng: 107.6292495 },
    { lat: -6.9741163, lng: 107.6292898 },
    { lat: -6.9741203, lng: 107.6293032 },
    { lat: -6.9740644, lng: 107.6293126 }, 
    { lat: -6.9740577, lng: 107.6292562 },
    { lat: -6.974103, lng: 107.6292482 },
    { lat: -6.974091, lng: 107.6291878 },

  ];
  const kantincewek = new google.maps.Polygon({
    paths: kantincewekCoords,
    strokeColor: "#FFA500",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFA500",
    fillOpacity: 5,
  });

  kantincewek.setMap(map);

  // pascasarjana
  const pascasarjanaCoords = [
    { lat: -6.9762562, lng: 107.6305857 },
    { lat: -6.9764013, lng: 107.6305857 },
    { lat: -6.9764026, lng: 107.6309706 },
    { lat: -6.9764932, lng: 107.6309706 },
    { lat: -6.9764932, lng: 107.6313997 },
    { lat: -6.9763361, lng: 107.6313984 },
    { lat: -6.9763374, lng:  107.6314748 },
    { lat: -6.976207, lng: 107.6314762 },
    { lat: -6.976207, lng: 107.6310631 },
    { lat: -6.9762589, lng: 107.6310631 },
    { lat: -6.9762562, lng: 107.6305857 },

  ];
  const pascasarjana = new google.maps.Polygon({
    paths: pascasarjanaCoords,
    strokeColor: "#F6BE00",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#F6BE00",
    fillOpacity: 5,
  });

  pascasarjana.setMap(map);

  // TUCH
  const TUCHCoords = [
    { lat: -6.9712622, lng: 107.6308679 },
    { lat: -6.9716536, lng: 107.630656 },
    { lat: -6.9717122, lng: 107.6306534 },
    { lat: -6.9717202, lng: 107.6305944 },
    { lat: -6.9717574, lng:  107.63064},
    { lat: -6.9718346, lng: 107.6306239 },
    { lat: -6.9719278, lng: 107.6306346 },
    { lat: -6.9719864, lng:  107.6306587 },
    { lat: -6.9720237, lng:  107.6307177 },
    { lat: -6.972021, lng: 107.6308277 },
    { lat: -6.9719837, lng: 107.6309109 },
    { lat: -6.9720183, lng: 107.6309672 },
    { lat: -6.9719651, lng: 107.6309538 },
    { lat: -6.9716722, lng:107.6313588  },
    { lat: -6.9715418, lng: 107.6313427 },
    { lat: -6.9714513, lng:  107.6313078 },
    { lat: -6.971382, lng: 107.6312542 },
    { lat: -6.9713155, lng: 107.6311818 },
    { lat: -6.9712729, lng:  107.6310932 },
    { lat: -6.9712516, lng: 107.6309967 },
    { lat: -6.9712622, lng:107.6308679},


  ];
  const TUCH = new google.maps.Polygon({
    paths: TUCHCoords,
    strokeColor: "#893BFF",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#893BFF",
    fillOpacity: 5,
  });

  TUCH.setMap(map);


// gku
const gkuCoords = [
    { lat: -6.9726038, lng: 107.6293874 },
    { lat: -6.9726024, lng: 107.6293565 },
    { lat: -6.9726225, lng: 107.6293592 },
    { lat: -6.9732201, lng: 107.6293552 },
    { lat: -6.9732154, lng: 107.6295168 },
    { lat: -6.9732164, lng: 107.6295929 },
    { lat: -6.9732169, lng: 107.6296296 },
    { lat: -6.9732161, lng: 107.6296677 },
    { lat: -6.9732134, lng: 107.6298212 },
    { lat: -6.9732108, lng: 107.6299855 },
    { lat: -6.9730617, lng: 107.6299869 },  
    { lat: -6.9730604, lng: 107.6299118 },
    { lat: -6.9729499, lng: 107.6299131 },
    { lat: -6.972942, lng: 107.6299426 },  
    { lat: -6.9728994, lng: 107.6299613 },
    { lat: -6.9728647, lng:  107.6299533 },
    { lat: -6.9728328, lng: 107.6299211 },  
    { lat: -6.9727329, lng: 107.6299198 },
    { lat: -6.9727343, lng: 107.6299775 },
    { lat: -6.9726065, lng: 107.6299775 },
    { lat: -6.9726038, lng: 107.6293874 },

    

  ];
  const gku = new google.maps.Polygon({
    paths: gkuCoords,
    strokeColor: "#800000",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#800000",
    fillOpacity: 5,
  });

  gku.setMap(map);

  // FKB
const FKBCoords = [
    { lat:-6.9717707 , lng:107.6326982  },
    { lat:-6.9717468 , lng:107.63267 },
    { lat:-6.9719025 , lng:107.6325359  },
    { lat:-6.9721634 , lng:107.6328712 },
    { lat:-6.9723125 , lng: 107.6327532 },
    { lat:-6.9724563 , lng:107.6329329  },
    { lat:-6.9723125 , lng:107.6330348  },
    { lat:-6.972206 , lng:107.6331207  },
    { lat:-6.972049 , lng:107.6332387  },
    { lat:-6.9719158 , lng:  107.6330576 },
    { lat:-6.971997 , lng:107.6329919  },
    { lat:-6.9717707 , lng: 107.6326982 },
    
 
  ];
  const FKB = new google.maps.Polygon({
    paths: FKBCoords,
    strokeColor: "#7E354D",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#7E354D",
    fillOpacity: 5,
  });

  FKB.setMap(map);

// Fakultas Teknik Elektro
const fakultasteknikelektroCoords = [
    { lat: -6.9761074, lng: 107.6296316 },
    { lat: -6.9762299, lng: 107.6296315 },
    { lat: -6.9762352, lng: 107.6297389 },  
    { lat: -6.9762086, lng: 107.6297402 },
    { lat: -6.9762139, lng: 107.6299052 },
    { lat: -6.9762432, lng: 107.6299052 },
    { lat: -6.9762485, lng: 107.6300312 },
    { lat: -6.976134,  lng: 107.6300339 },
    { lat: -6.976134,  lng: 107.6299937 },
    { lat: -6.9760861, lng: 107.6299937 },
    { lat: -6.9760755, lng: 107.6296745 },
    { lat: -6.9761088, lng: 107.6296732 },
    { lat: -6.9761074, lng: 107.6296316 },



  ];
  const fakultasteknikelektro = new google.maps.Polygon({
    paths: fakultasteknikelektroCoords,
    strokeColor: "#F6BE00",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#F6BE00",
    fillOpacity: 5,
  });

  fakultasteknikelektro.setMap(map);

  // Student Center
  const studentcenterCoords = [
    { lat: -6.977231,  lng: 107.6292781 },
    { lat: -6.9773002, lng: 107.6292767 },
    { lat: -6.9773002, lng: 107.6292271 },  
    { lat: -6.9775757, lng: 107.6292231 },
    { lat: -6.9775744, lng: 107.6293062 },
    { lat: -6.9776583, lng: 107.6293049 },
    { lat: -6.9775651, lng: 107.629498  },
    { lat: -6.9775637, lng: 107.6295718 },
    { lat: -6.9772935, lng: 107.6295731 },
    { lat: -6.9772922, lng: 107.6295275 },
    { lat: -6.9772323, lng: 107.6295288 },
    { lat: -6.977231,  lng: 107.6292781 },
    


  ];
  const studentcenter = new google.maps.Polygon({
    paths: studentcenterCoords,
    strokeColor: "#FFEF00",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFEF00",
    fillOpacity: 5,
  });

  studentcenter.setMap(map);

  // Business Center
  const businesscenterCoords = [
    { lat: -6.9772565,  lng: 107.6305645 },
    { lat: -6.977395,   lng: 107.6305645 },
    { lat: -6.977395,   lng: 107.6306449 },
    { lat: -6.9774469,  lng: 107.6306476 },
    { lat: -6.9774495,  lng: 107.6307522 },
    { lat: -6.9773084,  lng: 107.6307496 },
    { lat: -6.9773084,  lng: 107.6307066 },
    { lat: -6.9772565,  lng: 107.6307053 },
    { lat: -6.9772565,  lng: 107.6305645 },



  ];
  const businesscenter = new google.maps.Polygon({
    paths: businesscenterCoords,
    strokeColor: "#D462FF",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#D462FF",
    fillOpacity: 5,
  });

 businesscenter.setMap(map);


 //Klinik Telkomedika
  const kliniktelkomedikaCoords = [
    { lat: -6.9772565,  lng: 107.6305672 },
    { lat: -6.9772581,  lng: 107.6303956 },
    { lat: -6.9773073,  lng: 107.6303956 },
    { lat: -6.9773087,  lng: 107.630346  },
    { lat: -6.9774418,  lng: 107.6303487 },
    { lat: -6.9774418,  lng: 107.6304533 },
    { lat: -6.9773939,  lng: 107.630450  },
    { lat: -6.977395,   lng: 107.6305672 },
    { lat: -6.9772565,  lng: 107.6305672 },



  ];
  const kliniktelkomedika = new google.maps.Polygon({
    paths: kliniktelkomedikaCoords,
    strokeColor: "#E238EC",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#E238EC",
    fillOpacity: 5,
  });

 kliniktelkomedika.setMap(map);


//Open Library
  const openlibraryCoords = [
    { lat: -6.9714513,  lng: 107.6322779 },
    { lat: -6.9715205,  lng: 107.632221  },
    { lat: -6.9716081,  lng: 107.6321472 },
    { lat: -6.9716616,  lng: 107.6322244 },
    { lat: -6.9717575,  lng: 107.6321533 },
    { lat: -6.971847,   lng: 107.6322646 },
    { lat: -6.9719206,  lng: 107.6322096 },
    { lat: -6.9719883,  lng: 107.6322904 },
    { lat: -6.9719176,  lng: 107.6323444 },
    { lat: -6.9719532,  lng: 107.6324    },
    { lat: -6.9719751,  lng: 107.632449  },
    { lat: -6.9719452,  lng: 107.6324698 },
    { lat: -6.9719578,  lng: 107.6324921 },
    { lat: -6.9719025,  lng: 107.6325346 },
    { lat: -6.9717468,  lng: 107.6326687 },
    { lat: -6.9717055,  lng: 107.6326704 },
    { lat: -6.9714799,  lng: 107.6323762 },
    { lat: -6.9715069,  lng: 107.6323552 },
    { lat: -6.9714513,  lng: 107.6322779 },
 

  ];
  const openlibrary = new google.maps.Polygon({
    paths: openlibraryCoords,
    strokeColor: "#7D0541",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#7D0541",
    fillOpacity: 5,
  });

 openlibrary.setMap(map);
  

 // Gedung Serba Guna
  const gedungserbagunaCoords = [
    { lat: -6.9761806,  lng: 107.6300549  },
    { lat: -6.9764122,  lng: 107.6300576  },
    { lat: -6.9764122,  lng: 107.6301247  },
    { lat: -6.9769127,  lng: 107.6301233  },
    { lat: -6.9769127,  lng: 107.6302293  },
    { lat: -6.9769487,  lng: 107.6302306  },
    { lat: -6.9769487,  lng: 107.6303352  },
    { lat: -6.9769087,  lng: 107.6303352  },
    { lat: -6.9769101,  lng: 107.6304774  },
    { lat: -6.9764575,  lng: 107.6304747  },
    { lat: -6.9764029,  lng: 107.6304734  },
    { lat: -6.9764029,  lng: 107.6305458  },
    { lat: -6.9761846,  lng: 107.6305444  },
    { lat: -6.9761819,  lng: 107.6304023  },
    { lat: -6.9761939,  lng: 107.6304009  },
    { lat: -6.9761925,  lng: 107.6303205  },
    { lat: -6.9761673,  lng: 107.6302977  },
    { lat: -6.9761912,  lng: 107.6302749  },
    { lat: -6.9761912,  lng: 107.6302212  },
    { lat: -6.9762019,  lng: 107.6302212  },
    { lat: -6.9762019,  lng: 107.6301931  },
    { lat: -6.9761832,  lng: 107.6301931  },
    { lat: -6.9761806,  lng: 107.6300549  },
    
  
  ];
  const gedungserbaguna = new google.maps.Polygon({
    paths: gedungserbagunaCoords,
    strokeColor: "#43302E",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#43302E",
    fillOpacity: 5,
  });

 gedungserbaguna.setMap(map);

  // Fakultas Ekonomi Bisnis
  const fakultasekonomibisnisCoords = [
    { lat: -6.9713658,  lng:107.6316268  },
    { lat: -6.9714704,  lng:107.6315525  },
    { lat: -6.9714871,  lng:  107.6315559},
    { lat: -6.9715152,  lng:107.6315387  },
    { lat: -6.971579,   lng: 107.6316141 },
    { lat: -6.9715795,  lng: 107.6316364 },
    { lat: -6.9715429,  lng: 107.6316364 },
    { lat: -6.9715868,  lng: 107.6316593 },
    { lat: -6.9715282,  lng:107.6317133  },
    { lat: -6.9715522,  lng:107.6317703  },
    { lat: -6.9715203,  lng:107.63182    },
    { lat: -6.9714058,  lng: 107.6319098 },
    { lat: -6.9716081,  lng: 107.6321485 },
    { lat: -6.971444,   lng:  107.632288 },
    { lat: -6.97125,    lng: 107.6320171 },
    { lat: -6.9711648,  lng:  107.6320761},
    { lat: -6.9710264,  lng: 107.6318857 },
    { lat: -6.9713658,  lng: 107.6316268 },


  ];
  const fakultasekonomibisnis = new google.maps.Polygon({
    paths: fakultasekonomibisnisCoords,
    strokeColor: "#550A35",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#550A35",
    fillOpacity: 5,
  });

fakultasekonomibisnis.setMap(map);


   // Fakultas Rekayasa Industri
  const fakultasrekayasaindustriCoords = [
    { lat: -6.9754064,  lng: 107.6309473 },
    { lat: -6.975642,   lng: 107.6309459 },
    { lat: -6.9756446,  lng: 107.6312557 },
    { lat: -6.9760959,  lng: 107.6312464 },
    { lat: -6.9760919,  lng: 107.6314824 },
    { lat: -6.9755089,  lng: 107.6314891 },
    { lat: -6.9755076,  lng: 107.6314408 },
    { lat: -6.9754543,  lng: 107.6314381 },
    { lat: -6.9754517,  lng: 107.6313871 },
    { lat: -6.9754143,  lng: 107.6313818 },
    { lat: -6.9754064,  lng: 107.6309473 },
   

  ];
  const fakultasrekayasaindustri = new google.maps.Polygon({
    paths: fakultasrekayasaindustriCoords,
    strokeColor: "#342D7E",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#342D7E",
    fillOpacity: 5,
  });

fakultasrekayasaindustri.setMap(map);

// Mart
const martCoords = [
    { lat: -6.9772406, lng: 107.6310048 },
    { lat: -6.9773512, lng: 107.6310021 },
    { lat: -6.9773512, lng: 107.6312153 },
    { lat: -6.9772434, lng: 107.6312153 },
    { lat: -6.9772406, lng: 107.6310048 },

  ];
  const mart = new google.maps.Polygon({
    paths: martCoords,
    strokeColor: "#BCE954",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#BCE954",
    fillOpacity: 5,
  });

  mart.setMap(map);
  
  // yamaha sentra
  const yamahasentraCoords = [
    { lat: -6.9744302, lng: 107.6292245 },
    { lat: -6.9744701, lng: 107.6292138 },
    { lat: -6.9744914, lng: 107.6292862 },
    { lat: -6.9744435, lng: 107.6292902 },
    { lat: -6.9744302, lng: 107.6292245 },

  ];
  const yamahasentra = new google.maps.Polygon({
    paths: yamahasentraCoords,
    strokeColor: "#BCE954",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#BCE954",
    fillOpacity: 5,
  });

  yamahasentra.setMap(map);

  // Fakultas Industri Kreatif
  const fakultasindustrikreatifCoords = [
    { lat: -6.9723071,  lng: 107.6308772 },
    { lat: -6.9723936,  lng: 107.6309777 },
    { lat: -6.9723337,  lng: 107.6310314 },
    { lat: -6.972347,   lng: 107.6310475 },
    { lat: -6.9717333,  lng: 107.6315759 },
    { lat: -6.9717214,  lng: 107.6315571 },
    { lat: -6.9716601,  lng: 107.6316081 },
    { lat: -6.9715683,  lng: 107.6315035 },
    { lat: -6.9716229,  lng: 107.6314592 },
    { lat: -6.9716082,  lng: 107.6314391 },
    { lat: -6.9722219,  lng: 107.6309107 },
    { lat: -6.9722405,  lng: 107.6309295 },
    { lat: -6.9723071,  lng: 107.6308772 },

  ];
  const fakultasindustrikreatif = new google.maps.Polygon({
    paths: fakultasindustrikreatifCoords,
    strokeColor: "#8B8000",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#8B8000",
    fillOpacity: 5,
  });

fakultasindustrikreatif.setMap(map);

// Gedung Rektorat
const gedungrektoratCoords = [
    { lat: -6.9737481,  lng: 107.6302428  },
    { lat: -6.9738253,  lng: 107.6302441  },
    { lat: -6.973836,   lng: 107.630232   },
    { lat: -6.9738706,  lng: 107.6302267  },
    { lat: -6.9738706,  lng: 107.6301784  },
    { lat: -6.973997,   lng: 107.630169   },
    { lat: -6.9741208,  lng: 107.6301757  },
    { lat: -6.9741208,  lng: 107.630232   },
    { lat: -6.9741981,  lng: 107.6302333  },
    { lat: -6.974202,   lng: 107.6302669  },
    { lat: -6.9742407,  lng: 107.6302696  },
    { lat: -6.9742566,  lng: 107.6302937  },
    { lat: -6.9742646,  lng: 107.6303299  },
    { lat: -6.974254,   lng: 107.6303957  },
    { lat: -6.974222,   lng: 107.6304252  },
    { lat: -6.9741847,  lng: 107.6304252  },
    { lat: -6.9741821,  lng: 107.6304574  },
    { lat: -6.9741421,  lng: 107.6304895  },
    { lat: -6.9740969,  lng: 107.6305244, },
    { lat: -6.974009,   lng: 107.6305378  },
    { lat: -6.9739398,  lng: 107.6305325  },
    { lat: -6.9738866,  lng: 107.6305029  },
    { lat: -6.9738386,  lng: 107.6304574  },
    { lat: -6.9737614,  lng: 107.6304574  },
    { lat: -6.9737614,  lng: 107.6304278  },
    { lat: -6.9737375,  lng: 107.6304252  },
    { lat: -6.9737108,  lng: 107.6303769  },
    { lat: -6.9737162,  lng: 107.6303071  },
    { lat: -6.9737348,  lng: 107.630275   },
    { lat: -6.9737481,  lng: 107.6302428  },

  ];
  const  gedungrektorat = new google.maps.Polygon({
    paths:  gedungrektoratCoords,
    strokeColor: "#2B65EC",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#2B65EC",
    fillOpacity: 5,
  });

 gedungrektorat.setMap(map);

 // Lapangan Tenis
 const lapangantenisCoords = [
    { lat: -6.9772599,  lng: 107.6296393 },
    { lat: -6.9776007,  lng: 107.6296339 },
    { lat: -6.977598,   lng: 107.6300161 },
    { lat: -6.9772426,  lng: 107.6300135 },
    { lat: -6.9772386,  lng: 107.6296393 },
    { lat: -6.9772386,  lng: 107.6296393 },
    { lat: -6.9772599,  lng: 107.6296393 },



  ];
  const lapangantenis = new google.maps.Polygon({
    paths: lapangantenisCoords,
    strokeColor: "#008000",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#008000",
    fillOpacity: 5,
  });

lapangantenis.setMap(map);

// Kantin Teknik
const kantinteknikCoords = [
    { lat:-6.9773637 ,  lng: 107.6308677 },
    { lat: -6.9777125,  lng:  107.6308664 },
    { lat:-6.9777112 ,  lng: 107.6308449 },
    { lat: -6.977815,  lng:107.6308476  },
    { lat: -6.9778123,  lng:107.6310394  },
    { lat: -6.9777098,  lng: 107.6310354  },
    { lat:-6.9777098 ,  lng:  107.6310917 },
    { lat:-6.9777098 ,  lng: 107.6310917  },
    { lat:-6.977586 ,  lng: 107.6310917  },
    { lat:-6.9775874 ,  lng:107.6310421  },
    { lat: -6.9773637,  lng:107.6310421  },
    { lat:-6.9773637 ,  lng:107.6308677  },
   

  ];
  const kantinteknik = new google.maps.Polygon({
    paths: kantinteknikCoords,
    strokeColor: "#FFA500",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFA500",
    fillOpacity: 5,
  });

kantinteknik.setMap(map);

// Fakultas Teknik Elektro  (Gd Deli)
const FTEdeliCoords = [
    { lat:-6.9755355 , lng:107.6291316  },
    { lat:-6.9757378 , lng:107.6291316 },
    { lat:-6.9757405 , lng:107.6291826  },
    { lat:-6.9757645 , lng:107.6291879  },
    { lat:-6.9757645 , lng:107.6293194 },
    { lat:-6.9757112 , lng:107.629322 },
    { lat:-6.9757059 , lng:107.6292791 },
    { lat:-6.9755941 , lng:107.6292818  },
    { lat:-6.9755941 , lng:107.629306  },
    { lat:-6.9755648 , lng:107.6293086  },
    { lat:-6.9755648 , lng:107.6295313  },
    { lat:-6.9755887 , lng:107.6295339  },
    { lat:-6.9755861 , lng:107.6297297  },
    { lat:-6.9755621 , lng:107.6297297  },
    { lat:-6.9755648 , lng: 107.6299443  },
    { lat:-6.9755941 , lng:107.6299443  },
    { lat:-6.9757165 , lng:107.6299792  },
    { lat:-6.9757778 , lng:107.6299282  },
    { lat:-6.9757804 , lng:107.6300623  },
    { lat:-6.9757538 , lng:107.6300677  },
    { lat:-6.9755408 , lng:107.6300999  },
    { lat:-6.9755382 , lng:107.6301026  },
    { lat:-6.975453 , lng:107.6300758  },
    { lat:-6.9754556 , lng:107.6300758  },
    { lat:-6.9754237 , lng:107.6299899  },
    { lat:-6.9754237 , lng:107.6292577  },
    { lat:-6.9754503 , lng:107.6292577  },
    { lat:-6.9754503 , lng:107.6291638  },
    { lat:-6.9755302 , lng:107.6291665  },
    { lat:-6.9755355 , lng:107.6291316  },

  ];
  const FTEdeli= new google.maps.Polygon({
    paths: FTEdeliCoords,
    strokeColor: "#F6BE00",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#F6BE00",
    fillOpacity: 5,
  });

  FTEdeli.setMap(map);

  // Fakultas Ilmu Terapan
  const fakultasilmuterapanCoords = [
    { lat:-6.972805 ,  lng:107.6324079  },
    { lat:-6.9729221 ,  lng:107.6322791  },
    { lat: -6.9729155,  lng: 107.6322389  },
    { lat:-6.9729381 ,  lng: 107.632208  },
    { lat:-6.9729647 ,  lng: 107.6322308  },
    { lat:-6.9729794 ,  lng:  107.6322174 },
    { lat:-6.9730167 ,  lng:107.6322349  },
    { lat:-6.9730579 ,  lng: 107.6322442 },
    { lat:-6.9730912 ,  lng:  107.6322416 },
    { lat:-6.9731711 ,  lng:  107.6322161 },
    { lat:-6.9732696 ,  lng:107.6321262  },
    { lat:-6.9734493 ,  lng: 107.632082  },
    { lat: -6.9734559,  lng: 107.6322147 },
    { lat: -6.9734919,  lng: 107.6322429  },
    { lat: -6.9735318,  lng:107.6322805  },
    { lat: -6.9735584,  lng: 107.6323153  },
    { lat: -6.9735891,  lng:107.6323649  },
    { lat: -6.9736104,  lng:  107.6324105 },
    { lat: -6.9736277,  lng: 107.6324628  },
    { lat:-6.9736343 ,  lng:107.6325138  },
    { lat: -6.9736383,  lng:107.6325849  },
    { lat: -6.9735332,  lng:107.6327016  },
    { lat: -6.973408,  lng:107.632837  },
    { lat: -6.9733175,  lng:107.6329336  },
    { lat: -6.9730792,  lng: 107.632719  },
    { lat: -6.9730459,  lng:107.6326774  },
    { lat: -6.973014,  lng:107.6326332  },
    { lat: -6.9729714,  lng:107.632554  },
    { lat: -6.9729235,  lng: 107.6325688  },
    { lat:-6.9728662 ,  lng: 107.6325165  },
    { lat: -6.9728782,  lng:  107.6324669 },
    { lat: -6.9728542,  lng:107.6324374  },
    { lat: -6.972805,  lng:  107.6324079 },
   

  ];
  const fakultasilmuterapan = new google.maps.Polygon({
    paths: fakultasilmuterapanCoords,
    strokeColor: "#045F5F",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#045F5F",
    fillOpacity: 5,
  });

fakultasilmuterapan.setMap(map);

// Auditorium Gd K
const auditoriumgdkCoords = [
    { lat:-6.9747873 ,  lng:107.6297996 },
    { lat: -6.9748152,  lng:107.6298063 },
    { lat:-6.9748185 ,  lng: 107.6297929 },
    { lat: -6.9750029,  lng:107.6297929 },
    { lat:-6.9750049 ,  lng:107.629803 },
    { lat:-6.9750355 ,  lng:107.629803 },
    { lat: -6.9750362,  lng: 107.6298332 },
    { lat: -6.9750675,  lng: 107.6298338 },
    { lat: -6.9750655,  lng:107.6298922 },
    { lat:-6.9750435,  lng:107.6298922 },
    { lat:-6.9750448 ,  lng: 107.6300746 },
    { lat:-6.9750329,  lng:107.6300752 },
    { lat: -6.9750329,  lng: 107.6300886 },
    { lat: -6.9750635,  lng: 107.6300906 },
    { lat: -6.9750628,  lng: 107.6301289 },
    { lat: -6.9750129,  lng:107.6301282 },
    { lat: -6.9750116,  lng: 107.6301027 },
    { lat:-6.9747999 ,  lng: 107.6301014 },
    { lat: -6.9747999,  lng: 107.6300839 },
    { lat:-6.9747893 ,  lng:107.6300846 },
    { lat:-6.9747893 ,  lng: 107.6300564 },
    { lat:-6.9747999 ,  lng:107.6300551 },
    { lat: -6.9747966,  lng: 107.6298895 },
    { lat: -6.9747806,  lng:107.6298888 },
    { lat: -6.9747813,  lng:107.6298305 },
    { lat:-6.9747859 ,  lng: 107.6298305 },
    { lat:-6.9747873 ,  lng:107.6297996 },
  
  ];
  const auditoriumgdk = new google.maps.Polygon({
    paths: auditoriumgdkCoords,
    strokeColor: "#006400",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#006400",
    fillOpacity: 5,
  });

auditoriumgdk.setMap(map);

// FTEbarung
const FTEbarungCoords = [
    { lat:-6.9762282 , lng:107.6292777  },
    { lat:-6.9763826 , lng: 107.6292724  },
    { lat:-6.9763852 , lng:107.6292348  },
    { lat:-6.9763852 , lng:107.6292321  },
    { lat:-6.9768219 , lng:107.6292643  },
    { lat:-6.976931 , lng:107.6292643  },
    { lat:-6.9769363 , lng:107.6298356  },
    { lat:-6.9768405 , lng:107.629841  },
    { lat:-6.9768458 , lng:107.6299778  },
    { lat:-6.9768033 , lng:107.6299804  },
    { lat:-6.9767952 , lng:107.6293985  },
    { lat:-6.9764065 , lng:107.6294011  },
    { lat:-6.9764252 , lng:107.62979  },
    { lat:-6.9764678 , lng:107.62979  },
    { lat:-6.9764704 , lng:107.6299966  },
    { lat:-6.9764438 , lng:107.6299993  },
    { lat:-6.9764438 , lng:107.6298356  },
    { lat:-6.9762495 , lng:107.6298356  },
    { lat:-6.9762282 , lng:107.6292777  },
   
  ];
  const FTEbarung = new google.maps.Polygon({
    paths: FTEbarungCoords,
    strokeColor: "#F6BE00",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#F6BE00",
    fillOpacity: 5,
  });

  FTEbarung.setMap(map);

//Danau Galau
const danaugalauCoords = [
    { lat:-6.9729394 ,  lng:107.6307329 },
    { lat: -6.9730206,  lng:107.630745 },
    { lat:-6.9730486 ,  lng: 107.6307544 },
    { lat:-6.9730858 ,  lng: 107.6307718 },
    { lat: -6.9731204,  lng:  107.6307866 },
    { lat: -6.9731377,  lng:107.6308094  },
    { lat: -6.9731577,  lng:107.630855  },
    { lat: -6.9731617,  lng: 107.6309019 },
    { lat: -6.9731417,  lng: 107.6309475  },
    { lat:-6.9731071 ,  lng: 107.6309797  },
    { lat: -6.9730858,  lng:  107.6310159 },
    { lat:-6.9731164 ,  lng:  107.6310119 },
    { lat:-6.973155 ,  lng:107.6310078  },
    { lat: -6.973187,  lng:  107.6310186 },
    { lat:-6.9732189 ,  lng:  107.6310441 },
    { lat:-6.9732402 ,  lng:  107.6310762 },
    { lat:-6.9732509,  lng:107.6311111  },
    { lat:-6.9732509 ,  lng: 107.6311621  },
    { lat: -6.9732123,  lng: 107.6312211  },
    { lat: -6.9731657,  lng:107.6312452  },
    { lat:-6.9731763 ,  lng: 107.6312586  },
    { lat:-6.9732136 ,  lng:107.6313123  },
    { lat: -6.9732536,  lng: 107.6313753 },
    { lat: -6.9732868,  lng:107.6314276  },
    { lat:-6.9733015 ,  lng:107.6314705  },
    { lat: -6.9733001,  lng: 107.6315577  },
    { lat:-6.9732855 ,  lng:107.6316274  },
    { lat: -6.9732509,  lng: 107.6316999  },
    { lat: -6.973203,  lng: 107.6317481  },
    { lat: -6.9731244,  lng: 107.631779  },
    { lat: -6.9729594,  lng: 107.6318058 },
    { lat: -6.9728089,  lng:107.6317548  },
    { lat:-6.9727397 ,  lng:107.6317012  },
    { lat:-6.9726971 ,  lng: 107.6316154  },
    { lat:-6.9726838 ,  lng: 107.6315322  },
    { lat: -6.9727078,  lng:107.631445  },
    { lat: -6.9727517,  lng:107.631319  },
    { lat: -6.9727783,  lng: 107.6312036  },
    { lat: -6.972781,  lng: 107.6310816  },
    { lat: -6.9727783,  lng: 107.6310078  },
    { lat:-6.9727717 ,  lng:107.6309435  },
    { lat:-6.972777 ,  lng: 107.6308831 },
    { lat: -6.9728143,  lng:107.6308067  },
    { lat: -6.9728675,  lng: 107.6307544  },
    { lat: -6.9729287,  lng: 107.6307329  },
    { lat: -6.9729394,  lng:107.6307329  },
  
  ];
  const danaugalau = new google.maps.Polygon({
    paths: danaugalauCoords,
    strokeColor: "#43C6DB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#43C6DB",
    fillOpacity: 5,
  });

danaugalau.setMap(map);

// Graha wiyata cacuk
const cacuk2Coords = [
    { lat:-6.9746764 , lng:107.6306754  },
    { lat:-6.9748202 , lng:107.6306781  },
    { lat:-6.9748228 , lng:107.6309141  },
    { lat:-6.9748734 , lng:107.6309141  },
    { lat:-6.9748708 , lng:107.6306781  },
    { lat:-6.9750371 , lng:107.6306794  },
    { lat:-6.9750465 , lng:107.6310335  },
    { lat:-6.9749852 , lng:107.6310348  },
    { lat:-6.9749879 , lng:107.6310938  },
    { lat:-6.9750465 , lng:107.6310938  },
    { lat:-6.9750452 , lng:107.6312829  },
    { lat:-6.9750412 , lng:107.6314667  },
    { lat:-6.9748761 , lng:107.631464  },
    { lat:-6.9748788 , lng:107.631244  },
    { lat:-6.9748388 , lng:107.6312414  },
    { lat:-6.9748362 , lng:107.6314694  },
    { lat:-6.9746817 , lng:107.6314694  },
    { lat:-6.9746817 , lng:107.6310938  },
    { lat:-6.974763 , lng:107.6310938  },
    { lat:-6.9747669 , lng:107.6310402  },
    { lat:-6.9746817 , lng:107.6310389  },
    { lat:-6.9746764 , lng:107.6306754  },
   
   
  ];
  const cacuk2 = new google.maps.Polygon({
    paths: cacuk2Coords,
    strokeColor: "#7FE817",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#7FE817",
    fillOpacity: 5,
  });

  cacuk2.setMap(map);

// Masjid Syamsul Ulum
const masjidsyamsululumCoords = [
    { lat: -6.9757972,  lng:107.6318776 },
    { lat:-6.9758025 ,  lng:107.6319017 },
    { lat: -6.9758264,  lng:  107.6318924 },
    { lat: -6.975929,  lng:107.6321431 },
    { lat: -6.9759157,  lng: 107.6321485 },
    { lat:-6.9759263 ,  lng: 107.6321659 },
    { lat: -6.975933,  lng:107.632178 },
    { lat: -6.9759369,  lng: 107.6321873},
    { lat: -6.9760042,  lng:107.6323315 },
    { lat:-6.9759516 ,  lng: 107.6323604 },
    { lat: -6.9759716,  lng: 107.6324073 },
    { lat:-6.9758185 ,  lng: 107.632473 },
    { lat: -6.9757946,  lng:107.6324167 },
    { lat: -6.9757679,  lng:107.6324301 },
    { lat:-6.9757093 ,  lng:107.6322859 },
    { lat: -6.9756787,  lng:107.6322973 },
    { lat:-6.9756681 ,  lng:107.6322826 },
    { lat: -6.9756441,  lng: 107.6322933 },
    { lat:-6.9756348 ,  lng: 107.6322732 },
    { lat:-6.9756202 ,  lng: 107.6322826 },
    { lat:-6.9756055 ,  lng: 107.6322464 },
    { lat: -6.9755749,  lng: 107.6321833 },
    { lat: -6.9755483,  lng: 107.6321243 },
    { lat:-6.9755416 ,  lng: 107.6321149 },
    { lat: -6.975505,  lng: 107.6320439 },
    { lat: -6.9755097,  lng:107.6320103 },
    { lat: -6.9756841,  lng: 107.6319285 },
    { lat: -6.9757972,  lng:107.6318776 },
   
  ];
  const masjidsyamsululum = new google.maps.Polygon({
    paths: masjidsyamsululumCoords,
    strokeColor: "#FF0000",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FF0000",
    fillOpacity: 5,
  });

masjidsyamsululum.setMap(map);

// GrahaWiyataCacuk1
const GrahaWiyataCacuk1Coords = [
    { lat:-6.974351, lng:107.6306702  },
    { lat:-6.9743523, lng: 107.6306702  },
    { lat:-6.9744016, lng:107.6308982  },
    { lat:-6.9743976, lng:107.6306688  },
    { lat:-6.9745427, lng:107.6306688  },
    { lat:-6.974544, lng:107.6310229  },
    { lat:-6.9744908, lng:107.6310242  },
    { lat:-6.9744894, lng:107.631098  },
    { lat:-6.974544, lng:107.631098  },
    { lat:-6.9745374, lng:107.6314614  },
    { lat:-6.9743923, lng:107.6314574  },
    { lat:-6.9743936, lng:107.6312281  },
    { lat:-6.974351, lng:107.6312281  },
    { lat:-6.974347, lng:107.6314587  },
    { lat:-6.9742019, lng:107.6314547  },
    { lat:-6.9742046, lng:107.6310913  },
    { lat:-6.9742844, lng:107.6310913  },
    { lat:-6.9742844, lng:107.6310296  },
    { lat:-6.9742046, lng:107.6310296  },
    { lat:-6.9741979, lng:107.6306702  },
   
  ];
  const GrahaWiyataCacuk1 = new google.maps.Polygon({
    paths: GrahaWiyataCacuk1Coords,
    strokeColor: "#7FE817",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#7FE817",
    fillOpacity: 5,
  });
  GrahaWiyataCacuk1.setMap(map);

  //Ruang Riung Belakang
  const ruangriungbelakangCoords = [
    { lat: -6.9743027,  lng:107.6286162 },
    { lat: -6.974308,  lng:107.6286028 },
    { lat:-6.9744012 ,  lng:107.6286015 },
    { lat: -6.9744012,  lng: 107.6286136 },
    { lat: -6.9745183,  lng: 107.6286149 },
    { lat: -6.9745183,  lng:107.6286457 },
    { lat:-6.9745556 ,  lng:107.6286444 },
    { lat:-6.9745556 ,  lng:107.628694 },
    { lat:-6.9745383 ,  lng: 107.628694 },
    { lat:-6.9745383 ,  lng: 107.6287745 },
    { lat: -6.9745716,  lng:107.6287745 },
    { lat: -6.9745755,  lng:107.628914 },
    { lat: -6.9743187 ,  lng:  107.628914},
    { lat: -6.974292,  lng:107.6286565 },
    { lat:-6.9742907 ,  lng:107.6286162 },
    { lat:-6.9743027 ,  lng:107.6286162 },
   
  ];
  const  ruangriungbelakang = new google.maps.Polygon({
    paths: ruangriungbelakangCoords,
    strokeColor: "#FFA500",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFA500",
    fillOpacity: 5,
  });

 ruangriungbelakang.setMap(map);

// Gedung L
const gedunglCoords = [
    { lat:-6.9737061 , lng:107.6294398  },
    { lat:-6.9737061 , lng:107.6297563  },
    { lat:-6.9737274 , lng:107.6297791  },
    { lat:-6.9737274 , lng:107.6298502  },
    { lat:-6.9736995 , lng:107.6298717  },
    { lat:-6.9736302 , lng:107.629873  },
    { lat:-6.9736169 , lng:107.6298502  },
    { lat:-6.9734825 , lng:107.6298502  },
    { lat:-6.9734146 , lng:107.6297791  },
    { lat:-6.9734146 , lng:107.6294613  },
    { lat:-6.9734 , lng:107.6294385  },
    { lat:-6.9734 , lng:107.6293634  },
    { lat:-6.9734133 , lng:107.629346  },
    { lat:-6.9734985 , lng:107.6293419  },
    { lat:-6.9735118 , lng:107.6293527  },
    { lat:-6.9736289 , lng:107.6293513  },
    { lat:-6.9737061 , lng:107.6294398  },

   
  ];
  const gedungl = new google.maps.Polygon({
    paths: gedunglCoords,
    strokeColor: "#0041C2",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#0041C2",
    fillOpacity: 5,
  });

  gedungl.setMap(map);

//Parkiran Mobil 1 DEPAN CACUK
const parkiranmobil1Coords = [
    { lat:-6.9748251 ,  lng: 107.6316596 },
    { lat: -6.9749715,  lng:107.6316515 },
    { lat: -6.9749835,  lng:107.6320766 },
    { lat:-6.9749676 ,  lng:107.6320887 },
    { lat:-6.974869 ,  lng:107.6321785 },
    { lat:-6.9748251 ,  lng:107.6316596 },
   
  ];
  const  parkiranmobil1 = new google.maps.Polygon({
    paths: parkiranmobil1Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmobil1.setMap(map);

 //Parkiran Mobil 2 DEPAN CACUK
 const parkiranmobil2Coords = [
    { lat:-6.9750142 ,  lng:107.6316716 },
    { lat: -6.9751207,  lng:107.6316689 },
    { lat: -6.9751247,  lng: 107.6318003 },
    { lat:-6.9750994 ,  lng: 107.6319384 },
    { lat:-6.9750248 ,  lng: 107.6320296 },
    { lat:-6.9750142 ,  lng: 107.6316716 },
   
  ];
  const  parkiranmobil2 = new google.maps.Polygon({
    paths: parkiranmobil2Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmobil2.setMap(map);

//Parkir mobil gku
const parkirmobilgkuCoords = [
    { lat:-6.9720742 ,  lng:107.6290517 },
    { lat:-6.9725307 ,  lng:107.6290396 },
    { lat:-6.9725294 ,  lng:107.6301501 },
    { lat:-6.9721154 ,  lng:107.6301501 },
    { lat:-6.9721114 ,  lng:107.6299449 },
    { lat:-6.9721021 ,  lng:107.6297384 },
    { lat:-6.9720914 ,  lng:107.6294581 },
    { lat:-6.9720841 ,  lng:107.6292763 },
    { lat:-6.9720742 ,  lng:107.6290517 },
    
  ];
  const parkirmobilgku = new google.maps.Polygon({
    paths: parkirmobilgkuCoords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkirmobilgku.setMap(map)

 //Parkiran Mobil 3 DEPAN TUCH
 const parkiranmobil3Coords = [
    { lat:-6.9705883 ,  lng:107.6312245 },
    { lat: -6.9710063,  lng:107.6309563 },
    { lat: -6.9713631,  lng: 107.6314418 },
    { lat:-6.9709397 ,  lng: 107.6317529 },
    { lat:-6.9705883 ,  lng:  107.6312245 },
   
  ];
  const  parkiranmobil3 = new google.maps.Polygon({
    paths: parkiranmobil3Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmobil3.setMap(map);

 //Parkiran Motor 2 sebelah ruang riung
  const parkiranmotor2Coords = [
    { lat:-6.9746717 ,  lng:107.6286942 },
    { lat: -6.9749858,  lng: 107.6289677 },
    { lat: -6.9746184,  lng: 107.6289597 },
    { lat:-6.9746104 ,  lng:  107.6286351 },
    { lat:-6.9746717 ,  lng:   107.6286942 },
   
  ];
  const  parkiranmotor2 = new google.maps.Polygon({
    paths: parkiranmotor2Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmotor2.setMap(map);

 //Laundry Asrama
 const laundryasramaCoords = [
    { lat:-6.9737275 ,  lng:107.6280999 },
    { lat: -6.9739911,  lng:107.6281039 },
    { lat: -6.9739911,  lng: 107.6282098 },
    { lat: -6.9739365,  lng:107.6282098 },
    { lat: -6.9739352,  lng: 107.6283211 },
    { lat: -6.9739352,  lng:107.6283211 },
    { lat:-6.9738899 ,  lng:107.6283211 },
    { lat:-6.9738899 ,  lng: 107.6283547 },
    { lat: -6.973842,  lng: 107.628356 },
    { lat: -6.9738434,  lng: 107.6283265 },
    { lat:-6.9737968 ,  lng:107.6283238 },
    { lat:-6.9737981 ,  lng: 107.6282085},
    { lat:-6.9737315 ,  lng:107.6282085},
    { lat:-6.9737275 ,  lng:107.6280999 },
   
  ];
  const  laundryasrama = new google.maps.Polygon({
    paths: laundryasramaCoords,
    strokeColor: "#C48189",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#C48189",
    fillOpacity: 5,
  });

 laundryasrama.setMap(map);

//TJ mart asrama putra
const tjCoords = [
    { lat:-6.9712098 ,  lng:107.6281092 },
    { lat: -6.9713323,  lng: 107.6281052 },
    { lat: -6.9713376,  lng: 107.628694 },
    { lat:-6.9712124 ,  lng:  107.6286994 },
    { lat:-6.9712098 ,  lng:   107.6281092 },
   
  ];
  const  tj = new google.maps.Polygon({
    paths: tjCoords,
    strokeColor: "#BCE954",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#BCE954",
    fillOpacity: 5,
  });

 tj.setMap(map);

 //Parkiran Mobil 4 depan fik
 const parkiranmobil4Coords = [
    { lat:-6.9717645 ,  lng:107.6317107 },
    { lat: -6.9722384,  lng:  107.6312869 },
    { lat:-6.9723529,  lng: 107.6313996 },
    { lat:-6.971863 ,  lng:   107.6318261 },
    { lat:-6.9717645,  lng:   107.6317107 },
   
  ];
  const  parkiranmobil4 = new google.maps.Polygon({
    paths: parkiranmobil4Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmobil4.setMap(map);

 //kantin cowok
const kancowCoords = [
    { lat:-6.9699259 ,  lng:107.6271263 },
    { lat: -6.9700697,  lng: 107.6272524 },
    { lat: -6.9699871,  lng: 107.6273557 },
    { lat:-6.9699046 ,  lng:  107.6274374 },
    { lat:-6.9697742 ,  lng:   107.6273167 },
    { lat:-6.9699259 ,  lng:   107.6271263 },
   
  ];
  const  kancow = new google.maps.Polygon({
    paths: kancowCoords,
    strokeColor: "#FFA500",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFA500",
    fillOpacity: 5,
  });

  kancow.setMap(map);

  //Tmart
const tmartCoords = [
    { lat:-6.9701175 ,  lng:107.6269303 },
    { lat: -6.9701841,  lng: 107.626996 },
    { lat: -6.9700563,  lng: 107.6271476 },
    { lat:-6.9699897 ,  lng:  107.6270792 },
    { lat:-6.9701175 ,  lng:   107.6269303 },
   
  ];
  const  tmart = new google.maps.Polygon({
    paths: tmartCoords,
    strokeColor: "#BCE954",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#BCE954",
    fillOpacity: 5,
  });

  tmart.setMap(map);

  //Parkiran Motor 3//depan fik
  const parkiranmotor3Coords = [
    { lat:-6.9724247 ,  lng:107.6314666 },
    { lat: -6.9726217,  lng: 107.6317214 },
    { lat: -6.9721399,  lng: 107.632121 },
    { lat:-6.9719455,  lng:   107.6318877 },
    { lat:-6.9724247 ,  lng:  107.6314666 },
   
  ];
  const  parkiranmotor3 = new google.maps.Polygon({
    paths: parkiranmotor3Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmotor3.setMap(map);

//Parkiran Mobil 5// depan BTP
const parkiranmobil5Coords = [
    { lat:-6.9706736 ,  lng: 107.6306816 },
    { lat: -6.9707961,  lng: 107.6308265 },
    { lat: -6.9704978,  lng: 107.6310893 },
    { lat:-6.9703967,  lng:   107.6309472 },
    { lat:-6.9706736 ,  lng: 107.6306816 },
   
  ];
  const  parkiranmobil5 = new google.maps.Polygon({
    paths: parkiranmobil5Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmobil5.setMap(map);

 //Parkiran Mobil 6//sebelah fkb
 const parkiranmobil6Coords = [
    { lat: -6.9725587,  lng:  107.6329897},
    { lat: -6.972612,  lng: 107.6330702  },
    { lat: -6.9722632, lng: 107.6333518  },
    { lat: -6.9722366, lng: 107.6333626  },
    { lat: -6.97221,   lng:  107.6333491 },
    { lat: -6.972194,  lng: 107.633317   },
    { lat: -6.9722126, lng:107.6332928   },
    { lat: -6.9725587, lng:107.6329897   },
  
  ];
  const  parkiranmobil6 = new google.maps.Polygon({
    paths: parkiranmobil6Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmobil6.setMap(map);

 //Parkiran Motor 4
 const parkiranmotor4Coords = [
    { lat:-6.9716508 ,  lng:107.6296189 },
    
  ];
  const  parkiranmotor4 = new google.maps.Polygon({
    paths: parkiranmotor4Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmotor4.setMap(map);

 //Parkiran Mobil 7
 const parkiranmobil7Coords = [
    { lat:-6.9716508 ,  lng:107.6296189 },
    
    107.6313145,-6.9709343
  ];
  const  parkiranmobil7 = new google.maps.Polygon({
    paths: parkiranmobil7Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmobil7.setMap(map);

 //Parkiran Motor 5
 const parkiranmotor5Coords = [
    { lat:-6.9762992 ,  lng:107.6319808 },
    
  ];
  const  parkiranmotor5 = new google.maps.Polygon({
    paths: parkiranmotor5Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmotor5.setMap(map);

 //Parkiran Mobil 8
 const parkiranmobil8Coords = [
    { lat:-6.9749787 ,  lng:107.6318521 },
    
    107.6313145,-6.9709343
  ];
  const  parkiranmobil8 = new google.maps.Polygon({
    paths: parkiranmobil8Coords,
    strokeColor: "#c0c0c0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#c0c0c0",
    fillOpacity: 5,
  });

 parkiranmobil8.setMap(map);

 //Fakultas Informatika
 const fakultasinformatikaCoords = [
    { lat:-6.975631 ,  lng:107.6305372 },
    { lat:-6.9760504 ,  lng:107.6305318 },
    { lat:-6.976053 ,  lng:107.630733 },
    { lat:-6.975631 ,  lng:107.6307397 },
    { lat:-6.9756317 ,  lng:107.6306478 },
    { lat:-6.975631 ,  lng:107.6305372 },
    
  ];
  const  fakultasinformatika = new google.maps.Polygon({
    paths:fakultasinformatikaCoords,
    strokeColor: "#C34A2C",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#C34A2C",
    fillOpacity: 5,
  });

 fakultasinformatika.setMap(map);

 // LandmarkTower
const LandmarkTowerCoords = [
    { lat:-6.968769 , lng: 107.627825 },
    { lat: -6.9691191, lng: 107.6278236 },
    { lat: -6.9691191, lng: 107.6282863 },
    { lat: -6.9687724, lng: 107.6282836 },
    { lat: -6.968769, lng: 107.627825 },

  ];
  const LandmarkTower = new google.maps.Polygon({
    paths: LandmarkTowerCoords,
    strokeColor: "#6495ED",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#6495ED",
    fillOpacity: 5,
  });

  LandmarkTower.setMap(map);

  // BandungTechnoPark
const BandungTechnoParkCoords = [
    { lat:-6.9698098 , lng: 107.6299639 },
    { lat: -6.9700654, lng: 107.629921 },
    { lat: -6.9701985, lng: 107.629925 },
    { lat: -6.9702051, lng: 107.6301047 },
    { lat: -6.9700614, lng: 107.6301034 },
     { lat:-6.9698164 , lng: 107.6301409 },
    { lat: -6.9698098, lng: 107.6299639 },
    

  ];
  const BandungTechnoPark = new google.maps.Polygon({
    paths: BandungTechnoParkCoords,
    strokeColor: "#00FFFF",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00FFFF",
    fillOpacity: 5,
  });

  BandungTechnoPark.setMap(map);

  // Anon1
const Anon1Coords = [
    { lat:-6.9697964 , lng: 107.6294959 },
    { lat:-6.969857 , lng: 107.6294721 },
    { lat: -6.9699375, lng: 107.6294603 },
    { lat: -6.970064, lng: 107.6294529 },
    { lat: -6.9701771, lng: 107.6294569 },
    { lat: -6.9701945, lng: 107.6298432 },
     { lat:-6.9698177 , lng: 107.6298539 },
    { lat: -6.9697964, lng: 107.6294959 },
    

  ];
  const Anon1 = new google.maps.Polygon({
    paths: Anon1Coords,
    strokeColor: "#00FFFF",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00FFFF",
    fillOpacity: 5,
  });

  Anon1.setMap(map);

  // Anon2
const Anon2Coords = [
    { lat:-6.9702432 , lng: 107.6278951 },
    { lat:-6.9702978 , lng: 107.6278924 },
    { lat: -6.9703031, lng: 107.6279675 },
    { lat: -6.9704482, lng: 107.6279608 },
    { lat: -6.9704468, lng: 107.6278589 },
    { lat: -6.9705267, lng: 107.6278576 },
     { lat:-6.970536 , lng: 107.6280627 },
    { lat: -6.9702605, lng: 107.6280681 },
    { lat: -6.9702432, lng: 107.6278951 },


  ];
  const Anon2 = new google.maps.Polygon({
    paths: Anon2Coords,
    strokeColor: "#7F5A58",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#7F5A58",
    fillOpacity: 5,
  });

  Anon2.setMap(map);

  // FakultasInformatika
const FakultasInformatikaCoords = [
    { lat:-6.9767574 , lng: 107.6305971 },
    { lat:-6.9768985 , lng: 107.6305971 },
    { lat: -6.9768971, lng: 107.6307433 },
    { lat: -6.9769131, lng: 107.6307433 },
    { lat: -6.9769131, lng: 107.6308855 },
    { lat: -6.9768985, lng: 107.6308908 },
     { lat:-6.9769011 , lng: 107.6310236 },
    { lat: -6.9768079, lng: 107.6310263 },
    { lat: -6.9768079, lng: 107.6311363 },
    { lat:-6.9768266 , lng: 107.6311376 },
    { lat:-6.9768292 , lng: 107.6312985 },
    { lat: -6.9768079, lng: 107.6312972 },
    { lat: -6.9768079, lng: 107.6313991 },
    { lat: -6.976776, lng: 107.6313991 },
    { lat: -6.976776, lng: 107.6314165 },
     { lat:-6.9766668 , lng: 107.6314179 },
    { lat: -6.9766682, lng: 107.6310102 },
    { lat: -6.9766841, lng: 107.6310102 },
    { lat: -6.9766841, lng: 107.6309753 },
    { lat: -6.97676, lng: 107.630978 },
    { lat: -6.9767574, lng: 107.6305971 },
   

  ];
  const FakultasInformatika = new google.maps.Polygon({
    paths: FakultasInformatikaCoords,
    strokeColor: "#C34A2C",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#C34A2C",
    fillOpacity: 5,
  });

  FakultasInformatika.setMap(map);

  //IF2
  const IF2Coords = [
    { lat:-6.9757894 ,  lng:107.6308639 },
    { lat:-6.9760717 ,  lng:107.6308639 },
    { lat:-6.9760783 ,  lng:107.6311442 },
    { lat:-6.9757948 ,  lng:107.6311483 },
    { lat:-6.9757894 ,  lng:107.6308639 },
    
  ];
  const   IF2 = new google.maps.Polygon({
    paths: IF2Coords,
    strokeColor: "#C34A2C",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#C34A2C",
    fillOpacity: 5,
  });

 IF2.setMap(map);

  // parkir motor gku
const motorgkuCoords = [
    { lat:-6.9713468 , lng: 107.6290158 },
    { lat:-6.9717941 , lng: 107.6289997 },
    { lat: -6.9718713, lng: 107.6290265 },
    { lat: -6.9719432, lng: 107.62904 },
    { lat: -6.9719432, lng: 107.6301558 },
    { lat: -6.9718873, lng: 107.6301906 },
    { lat:-6.9718766 , lng: 107.6302604 },
    { lat: -6.9718713, lng: 107.6303677 },
    { lat: -6.9718527, lng: 107.6304159 },
    { lat: -6.9715625, lng: 107.630491 },
    { lat:-6.9714134 , lng: 107.6305769 },
    { lat: -6.9713468, lng: 107.6290158 },
    

  ];
  const motorgku = new google.maps.Polygon({
    paths: motorgkuCoords,
    strokeColor: "#C0C0C0",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#C0C0C0",
    fillOpacity: 5,
  });

  motorgku.setMap(map);
  

 // ASRAMA PUTRI
 // AsramaPutri  gd 12
const AsramaPutri1Coords = [
    { lat:-6.9696637 , lng:107.6282292  },
    { lat:-6.969902 , lng: 107.6282198  },
    { lat:-6.9699259 , lng:107.628779  },
    { lat:-6.969689 , lng:107.6287803  },
    { lat:-6.9696637 , lng:107.6282292  },
   
   
  ];
  const AsramaPutri1 = new google.maps.Polygon({
    paths: AsramaPutri1Coords,
    strokeColor: "#FFC0CB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFC0CB",
    fillOpacity: 5,
  });
  AsramaPutri1.setMap(map);

  // AsramaPutri gd 11
const AsramaPutri2Coords = [
    { lat:-6.9699547 , lng:107.6282111  },
    { lat:-6.970213 , lng: 107.6282071  },
    { lat:-6.9702529 , lng:107.6287878  },
    { lat:-6.969984 , lng:107.6287851  },
    { lat:-6.9699547 , lng:107.6282111  },
   
  ];
  const AsramaPutri2= new google.maps.Polygon({
    paths: AsramaPutri2Coords,
    strokeColor: "#FFC0CB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFC0CB",
    fillOpacity: 5,
  });
  AsramaPutri2.setMap(map);

  // AsramaPutri3 gd. E
const AsramaPutri3Coords = [
    { lat:-6.972481 , lng:107.6289444  },
    { lat:-6.972481 , lng: 107.6287379  },
    { lat:-6.9724804 , lng:107.6284864  },
    { lat:-6.9724877 , lng:107.6284864  },
    { lat:-6.9724884 , lng:107.628406  },
    { lat:-6.9726301 , lng:107.6284033  },
    { lat:-6.9726301 , lng:107.6289451  },
    { lat:-6.9725949 , lng:107.6289458  },
    { lat:-6.9725955 , lng:107.6289619  },
    { lat:-6.9725183 , lng:107.6289625  },
    { lat:-6.9725176 , lng:107.6289478  },
    { lat:-6.972481 , lng:107.6289444  },
 
  ];
  const AsramaPutri3= new google.maps.Polygon({
    paths: AsramaPutri3Coords,
    strokeColor: "#FFC0CB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFC0CB",
    fillOpacity: 5,
  });
  AsramaPutri3.setMap(map);

  // AsramaPutri4 gd. D
const AsramaPutri4Coords = [
    { lat:-6.972836 , lng:107.6285335  },
    { lat:-6.9728433 , lng: 107.6285329  },
    { lat:-6.9728407 , lng:107.6284524  },
    { lat:-6.9729997 , lng:107.6284504  },
    { lat:-6.9729991 , lng:107.6287193  },
    { lat:-6.9730377 , lng:107.6287199  },
    { lat:-6.9730363 , lng:107.6288044  },
    { lat:-6.9729984 , lng:107.6288044  },
    { lat:-6.9729997 , lng:107.6289955  },
    { lat:-6.9729558 , lng:107.6289949  },
    { lat:-6.9729558 , lng:107.6290076  },
    { lat:-6.9728819 , lng:107.6290063  },
    { lat:-6.9728813 , lng:107.6289949  },
    { lat:-6.972838 , lng:107.6289955  },
    { lat:-6.972836 , lng:107.6285335  },
    
  ];
  const AsramaPutri4= new google.maps.Polygon({
    paths: AsramaPutri4Coords,
    strokeColor: "#FFC0CB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFC0CB",
    fillOpacity: 5,
  });
  AsramaPutri4.setMap(map);

  // AsramaPutri5 gd. C
const AsramaPutri5Coords= [
    { lat:-6.9732561 , lng:107.6284788  },
    { lat:-6.9734152 , lng: 107.6284734  },
    { lat:-6.9734178 , lng:107.6287464  },
    { lat:-6.9734558 , lng:107.628747  },
    { lat:-6.9734564 , lng:107.6288302  },
    { lat:-6.9734205 , lng:107.6288302  },
    { lat:-6.9734231 , lng:107.6290233  },
    { lat:-6.9733752 , lng:107.629024  },
    { lat:-6.9733752 , lng:107.6290394  },
    { lat:-6.9732987 , lng:107.6290414  },
    { lat:-6.973298 , lng:107.6290233  },
    { lat:-6.9732601 , lng:107.6290213  },
    { lat:-6.9732514 , lng:107.6285626  },
    { lat:-6.9732594 , lng:107.6285619  },
    { lat:-6.9732561 , lng:107.6284788  },
    
    
  ];
  const AsramaPutri5= new google.maps.Polygon({
    paths: AsramaPutri5Coords,
    strokeColor: "#FFC0CB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFC0CB",
    fillOpacity: 5,
  });
  AsramaPutri5.setMap(map);

  // AsramaPutri6 Gd. B
const AsramaPutri6Coords= [
    { lat:-6.9736196 , lng:107.6289551  },
    { lat:-6.9736196 , lng: 107.6287788  },
    { lat:-6.9735869 , lng:107.6287801  },
    { lat:-6.9735883 , lng:107.628699  },
    { lat:-6.9736216 , lng:107.6286977  },
    { lat:-6.9736202 , lng:107.62852  },
    { lat:-6.9736275 , lng:107.62852  },
    { lat:-6.9736289 , lng:107.6284435  },
    { lat:-6.9738026 , lng:107.6284428  },
    { lat:-6.9738013 , lng:107.6289578  },
    { lat:-6.9737507 , lng:107.6289585  },
    { lat:-6.9737507 , lng:107.6289779  },
    { lat:-6.9736781 , lng:107.6289779  },
    { lat:-6.9736755 , lng:107.6289585  },
    { lat:-6.9736196 , lng:107.6289551  },

    
  ];
  const AsramaPutri6= new google.maps.Polygon({
    paths: AsramaPutri6Coords,
    strokeColor: "#FFC0CB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFC0CB",
    fillOpacity: 5,
  });
  AsramaPutri6.setMap(map);

  // AsramaPutri7 gd. A
const AsramaPutri7Coords= [
    { lat:-6.9740026 , lng:107.6284191  },
    { lat:-6.9741717 , lng: 107.6284238  },
    { lat:-6.9742116 , lng:107.6286733  },
    { lat:-6.9742083 , lng:107.6286753  },
    { lat:-6.974169 , lng:107.6287531  },
    { lat:-6.9741664 , lng:107.6287531  },
    { lat:-6.9741284 , lng:107.6289368  },
    { lat:-6.9741291 , lng:107.6289355  },
    { lat:-6.9740492 , lng:107.6289589  },
    { lat:-6.9740492 , lng:107.6289536  },
    { lat:-6.9740499 , lng:107.6289355  },
    { lat:-6.9739853 , lng:107.6289328  },
    { lat:-6.9739933 , lng:107.6284942  },
    { lat:-6.9740013 , lng:107.6284942  },
    { lat:-6.9740026 , lng:107.6284191  },
   
  ];
  const AsramaPutri7= new google.maps.Polygon({
    paths: AsramaPutri7Coords,
    strokeColor: "#FFC0CB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFC0CB",
    fillOpacity: 5,
  });
  AsramaPutri7.setMap(map);

  // AsramaPutri8
const AsramaPutri8Coords= [
    { lat:-6.972032 , lng:107.6284157  },
    { lat:-6.9721785 , lng: 107.6284184  },
    { lat:-6.9721811 , lng:107.6286571  },
    { lat:-6.9722157 , lng:107.6286597  },
    { lat:-6.9722184 , lng:107.6287295  },
    { lat:-6.9721865 , lng:107.6287375  },
    { lat:-6.9721865 , lng:107.6289521  },
    { lat:-6.9721518 , lng:107.6289548  },
    { lat:-6.9721492 , lng:107.6289736  },
    { lat:-6.9720853 , lng:107.6289763  },
    { lat:-6.9720773 , lng:107.6289548  },
    { lat:-6.9720427 , lng:107.6289521  },
    { lat:-6.972032 , lng:107.6284157  },
    
   
  ];
  const AsramaPutri8= new google.maps.Polygon({
    paths: AsramaPutri8Coords,
    strokeColor: "#FFC0CB",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#FFC0CB",
    fillOpacity: 5,
  });
  AsramaPutri8.setMap(map);

  

  // ASRAMA PUTRA
  //asrama putra gd1
  const gd1Coords = [
    { lat: -6.9708883, lng:  107.628193 },
    { lat: -6.9711172, lng: 107.6281876 },
    { lat: -6.9711465, lng: 107.6287509 },
    { lat: -6.9709282, lng: 107.6287616 },
    { lat: -6.9708883, lng:  107.628193 },

  ];
  const gd1 = new google.maps.Polygon({
    paths: gd1Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd1.setMap(map);

  // Asrama putra gd.2
  const gd2Coords = [
    { lat: -6.9706064, lng: 107.628194 },
    { lat: -6.9708327, lng: 107.628194 },
    { lat: -6.9708739, lng: 107.6287734 },
    { lat: -6.970645, lng:107.6287841  },
    { lat: -6.9706064, lng: 107.628194 },

  ];
  const gd2 = new google.maps.Polygon({
    paths: gd2Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd2.setMap(map);

  // Asrama Putra gd. 3
  const gd3Coords = [
    { lat: -6.9702677, lng: 107.628201 },
    { lat: -6.9705539, lng: 107.6281983 },
    { lat: -6.9705992, lng: 107.6287884 },
    { lat: -6.9703036, lng: 107.6287884 },
    { lat: -6.9702677, lng: 107.628201 },

  ];
  const gd3 = new google.maps.Polygon({
    paths: gd3Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd3.setMap(map);

  // Asrama putra gd.4
  const gd4Coords = [
    { lat: -6.9708567, lng: 107.6275932 },
    { lat: -6.9710963, lng: 107.6275798 },
    { lat: -6.9711149, lng: 107.6281296 },
    { lat: -6.970886, lng: 107.628135 },
    { lat: -6.9708567, lng: 107.6275932 },

  ];
  const gd4 = new google.maps.Polygon({
    paths: gd4Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd4.setMap(map);

  // Asrama putra gd.5
  const gd5Coords = [
    { lat: -6.9705641, lng: 107.6276066 },
    { lat: -6.9708024, lng: 107.6275999 },
    { lat: -6.9708317, lng: 107.6281391 },
    { lat: -6.9706001, lng:  107.6281458 },
    { lat: -6.9705641, lng: 107.6276066 },

  ];
  const gd5 = new google.maps.Polygon({
    paths: gd5Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd5.setMap(map);

// asrama putra gd.6
const gd6Coords = [
    { lat:-6.9708525 , lng: 107.6269948 },
    { lat: -6.9710788, lng: 107.6269828 },
    { lat: -6.9711027, lng: 107.6275138 },
    { lat: -6.9708498, lng: 107.627546 },
    { lat: -6.9708525, lng: 107.6269948 },

  ];
  const gd6 = new google.maps.Polygon({
    paths: gd6Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd6.setMap(map);

  // asrama putra gd.7
const gd7Coords = [
    { lat: -6.9705603, lng: 107.6270067 },
    { lat:-6.9708026, lng:107.6270013 } ,
    { lat: -6.9707999, lng:  107.6275485 },
    { lat: -6.9705617, lng: 107.6275579 },
    { lat: -6.9705603, lng:107.6270067 },

  ];
  const gd7 = new google.maps.Polygon({
    paths: gd7Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd7.setMap(map);

// asrama putra gd.8
const gd8Coords = [
    { lat: -6.9702261, lng: 107.6270152 },
    { lat:-6.9705149, lng:107.6270126 } ,
    { lat: -6.9705136, lng:  107.6275597 },
    { lat: -6.9702247, lng:  107.6275651 },
    { lat: -6.9702261, lng:107.6270152 },

  ];
  const gd8 = new google.maps.Polygon({
    paths: gd8Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd8.setMap(map);

  // asrama putra gd.9
const gd9Coords = [
    { lat: -6.9699272, lng: 107.6276296 },
    { lat:-6.9701748, lng:107.6276189 } ,
    { lat: -6.970208, lng:  107.628154 },
    { lat: -6.9699511, lng:   107.6281607 },
    { lat: -6.9699272, lng:107.6276296 },

  ];
  const gd9 = new google.maps.Polygon({
    paths: gd9Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd9.setMap(map);

    // asrama putra gd.10
const gd10Coords = [
    { lat: -6.9696612, lng: 107.627645 },
    { lat:-6.9698822, lng: 107.6276329 } ,
    { lat: -6.9698995, lng: 107.6281599 },
    { lat: -6.9696799, lng: 107.628172 },
    { lat: -6.9696612, lng: 107.627645 },

  ];
  const gd10 = new google.maps.Polygon({
    paths: gd10Coords,
    strokeColor: "#00008B",
    strokeOpacity: 5,
    strokeWeight: 2,
    fillColor: "#00008B",
    fillOpacity: 5,
  });

  gd10.setMap(map);



  //JALAN
  
  const JalanTelekomunikasiCoords = [
    { lat: -6.975227, lng: 107.6290389 },
    { lat: -6.974203, lng: 107.6290429 },
    { lat: -6.9741338, lng: 107.6290455 },
    { lat: -6.9740593, lng: 107.629067 },
    { lat: -6.9740114, lng: 107.6291126 },
    { lat: -6.9739688, lng: 107.6291582 },
    { lat: -6.9739528, lng: 107.6292226 },
    { lat: -6.9739528, lng: 107.6292735 },
    { lat: -6.9739475, lng: 107.6298502 },
  ];
  const Jalan = new google.maps.Polyline({
    path: JalanTelekomunikasiCoords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan.setMap(map);

  const Jalan1Coords = [
    { lat: -6.9771086, lng: 107.6292588 },
    { lat: -6.9769463, lng: 107.6291417 },
    { lat: -6.9768478, lng: 107.6290934 },
    { lat: -6.9767227, lng: 107.6290746 },
    { lat: -6.975227, lng: 107.6290389 },
    
  ];
  const Jalan1 = new google.maps.Polyline({
    path: Jalan1Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan1.setMap(map);

  const JalanFakultasTeknikSelatanCoords = [
    { lat: -6.9752828, lng: 107.6316169 },
    { lat: -6.9768536, lng: 107.6315579 },
    { lat: -6.9769894, lng: 107.6314855 },
    { lat: -6.9770879, lng: 107.631397 },
    { lat: -6.9771597, lng: 107.6312656 },
    { lat: -6.9771784, lng: 107.6310939 },
    { lat: -6.9771591, lng: 107.6294337 },
    
  ];
  const JalanFakultasTeknikSelatan = new google.maps.Polyline({
    path: JalanFakultasTeknikSelatanCoords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  JalanFakultasTeknikSelatan.setMap(map);

  const Jalan3Coords = [
    { lat: -6.9762896, lng: 107.6315807 },
    { lat: -6.9762949, lng: 107.631684 },
    
  ];
  const Jalan3 = new google.maps.Polyline({
    path: Jalan3Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan3.setMap(map);

  const Jalan4Coords = [
    { lat: -6.9739501, lng: 107.6316478 },
    { lat: -6.9752828, lng: 107.6316169 },
    
  ];
  const Jalan4 = new google.maps.Polyline({
    path: Jalan4Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan4.setMap(map);

  const Jalan5Coords = [
    { lat: -6.976113, lng: 107.6318259 },
    { lat: -6.9761085, lng: 107.6316934 },
    { lat: -6.9764653, lng: 107.6316826 },
    
  ];
  const Jalan5 = new google.maps.Polyline({
    path: Jalan5Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan5.setMap(map);

  const Jalan6Coords = [
    { lat: -6.976097, lng: 107.6328773 },
    { lat: -6.976113, lng: 107.6318259 },
    { lat: -6.9764967, lng: 107.6318151 },
    
  ];
  const Jalan6 = new google.maps.Polyline({
    path: Jalan6Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan6.setMap(map);

  const Jalan7Coords = [
    { lat: -6.9718642, lng: 107.631876 },
    { lat: -6.9724074, lng: 107.6314173 },
    { lat: -6.9722423, lng: 107.6312349 },
    { lat: -6.9716944, lng: 107.6317016 },
    
  ];
  const Jalan7 = new google.maps.Polyline({
    path: Jalan7Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan7.setMap(map);

  const Jalan8Coords = [
    { lat: -6.9732039, lng: 107.6333378 },
    { lat: -6.9727833, lng: 107.632973 },
    { lat: -6.9722801, lng: 107.6324178 },
    { lat: -6.9721337, lng: 107.6322542 },
    { lat: -6.9719819, lng: 107.6320047 },
    { lat: -6.9716944, lng: 107.6317016 },
    { lat: -6.9710314, lng: 107.6308727 },
    
  ];
  const Jalan8 = new google.maps.Polyline({
    path: Jalan8Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan8.setMap(map);

  const Jalan9Coords = [
    { lat: -6.9725854, lng: 107.6329936 },
    { lat: -6.9723616, lng: 107.6326953 },
    { lat: -6.9724566, lng: 107.632621 },
    
  ];
  const Jalan9 = new google.maps.Polyline({
    path: Jalan9Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan9.setMap(map);

  const Jalan10Coords = [
    { lat: -6.9725611, lng: 107.632965 },
    { lat: -6.9721818, lng: 107.6332908 },
    { lat: -6.9721751, lng: 107.6333324 },
    { lat: -6.9722017, lng: 107.633374 },
    { lat: -6.9722363, lng: 107.6333861 },
    { lat: -6.9722563, lng: 107.6333874 },
    { lat: -6.9726424, lng: 107.6330749 },
    
  ];
  const Jalan10 = new google.maps.Polyline({
    path: Jalan10Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan10.setMap(map);

  const Jalan11Coords = [
    { lat: -6.9725854, lng: 107.6329936 },
    { lat: -6.9727409, lng: 107.6332144 },
    
  ];
  const Jalan11 = new google.maps.Polyline({
    path: Jalan11Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan11.setMap(map);

  const Jalan12Coords = [
    { lat: -6.9752893, lng: 107.6302963 },
    { lat: -6.9753944, lng: 107.6302976 },
    { lat: -6.9754064, lng: 107.6302735 },
    { lat: -6.9754743, lng: 107.6302118 },
    { lat: -6.9758271, lng: 107.6302091 },
    { lat: -6.9761252, lng: 107.6302077 },
    { lat: -6.9761279, lng: 107.6303834 },
    { lat: -6.9754836, lng: 107.6303928 },
    { lat: -6.9754557, lng: 107.6303714 },
    { lat: -6.9754264, lng: 107.6303472 },
    { lat: -6.9753931, lng: 107.6303016 },
    
  ];
  const Jalan12 = new google.maps.Polyline({
    path: Jalan12Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan12.setMap(map);

  const Jalan13Coords = [
    { lat: -6.9752828, lng: 107.6316169 },
    { lat: -6.9752946, lng: 107.6290383 },
    
  ];
  const Jalan13 = new google.maps.Polyline({
    path: Jalan13Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan13.setMap(map);

  const Jalan14Coords = [
    { lat: -6.9771086, lng: 107.6292588 },
    { lat: -6.9771591, lng: 107.6294337 },
    
  ];
  const Jalan14 = new google.maps.Polyline({
    path: Jalan14Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan14.setMap(map);

  const Jalan15Coords = [
    { lat: -6.974369, lng: 107.6303067 },
    { lat: -6.9744109, lng: 107.630312 },
    
  ];
  const Jalan15 = new google.maps.Polyline({
    path: Jalan15Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan15.setMap(map);

  const Jalan16Coords = [
    { lat: -6.9739585, lng: 107.6291961 },
    { lat: -6.972795, lng: 107.6291862 },
    { lat: -6.9727538, lng: 107.6291527 },
    { lat: -6.9726526, lng: 107.6290267 },
    { lat: -6.9726113, lng: 107.6290092 },
    { lat: -6.9725647, lng: 107.6290012 },
    { lat: -6.9720376, lng: 107.6290213 },
    
  ];
  const Jalan16 = new google.maps.Polyline({
    path: Jalan16Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan16.setMap(map);

  const Jalan17Coords = [
    { lat: -6.9713466, lng: 107.6306542 },
    { lat: -6.9713666, lng: 107.6305255 },
    { lat: -6.9713107, lng: 107.6289805 },
    { lat: -6.9717899, lng: 107.6289618 },
    { lat: -6.9718857, lng: 107.6289966 },
    { lat: -6.9720428, lng: 107.6290208 },
    { lat: -6.9720848, lng: 107.6302144 },
    
  ];
  const Jalan17 = new google.maps.Polyline({
    path: Jalan17Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan17.setMap(map);

  const Jalan18Coords = [
    { lat: -6.975205, lng: 107.6316158 },
    { lat: -6.975227, lng: 107.6290389 },
    
  ];
  const Jalan18 = new google.maps.Polyline({
    path: Jalan18Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan18.setMap(map);

  const Jalan19Coords = [
    { lat: -6.975209, lng: 107.6297465 },
    { lat: -6.9750985, lng: 107.6297465 },
    { lat: -6.9750972, lng: 107.6301261 },
    { lat: -6.9752037, lng: 107.6301287 },
    
  ];
  const Jalan19 = new google.maps.Polyline({
    path: Jalan19Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan19.setMap(map);

  const Jalan20Coords = [
    { lat: -6.9752103, lng: 107.6302469 },
    { lat: -6.9744116, lng: 107.6302577 },
    { lat: -6.9744116, lng: 107.6303623 },
    { lat: -6.9752103, lng: 107.6303596 },
    
  ];
  const Jalan20 = new google.maps.Polyline({
    path: Jalan20Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan20.setMap(map);

  const Jalan21Coords = [
    { lat: -6.9723563, lng: 107.6326953 },
    { lat: -6.9722831, lng: 107.6326605 },
    { lat: -6.9722152, lng: 107.6326859 },
    { lat: -6.9721526, lng: 107.6326511 },
    { lat: -6.9720275, lng: 107.6324794 },
    { lat: -6.9720355, lng: 107.6323118 },
    { lat: -6.9719822, lng: 107.6322098 },
    { lat: -6.971897, lng: 107.6321401 },
    { lat: -6.9717106, lng: 107.6320784 },
    { lat: -6.971495, lng: 107.6318558 },
    { lat: -6.971676, lng: 107.6316761 },
    
  ];
  const Jalan21 = new google.maps.Polyline({
    path: Jalan21Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan21.setMap(map);

  const Jalan22Coords = [
    { lat: -6.9728742, lng: 107.632699 },
    { lat: -6.9726971, lng: 107.632876 },
    
  ];
  const Jalan22 = new google.maps.Polyline({
    path: Jalan22Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan22.setMap(map);

  const Jalan23Coords = [
    { lat: -6.9728059, lng: 107.6326155 },
    { lat: -6.9726368, lng: 107.6327992 },
    
  ];
  const Jalan23 = new google.maps.Polyline({
    path: Jalan23Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan23.setMap(map);

  const Jalan24Coords = [
    { lat: -6.9724822, lng: 107.6319196 },
    { lat: -6.9723677, lng: 107.6320832 },
    { lat: -6.9723012, lng: 107.6321181 },
    { lat: -6.9727271, lng: 107.6325177 },
    { lat: -6.9729162, lng: 107.6327431 },
    { lat: -6.9732995, lng: 107.6330596 },
    { lat: -6.9733767, lng: 107.6329684 },
    
  ];
  const Jalan24 = new google.maps.Polyline({
    path: Jalan24Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan24.setMap(map);

  const Jalan25Coords = [
    { lat: -6.9713107, lng: 107.6289805 },
    { lat: -6.971272, lng: 107.6288316 },
    { lat: -6.9712074, lng: 107.6287813 },
    { lat: -6.9711705, lng: 107.628775 },
    { lat: -6.9708984, lng: 107.62879 },
    { lat: -6.9706197, lng: 107.6288064 },
    { lat: -6.9702835, lng: 107.6288231 },
    { lat: -6.9699603, lng: 107.6288104 },
    { lat: -6.9696822, lng: 107.6288263 },
    
  ];
  const Jalan25 = new google.maps.Polyline({
    path: Jalan25Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan25.setMap(map);

  const Jalan26Coords = [
    { lat: -6.9729716, lng: 107.632791 },
    { lat: -6.972897, lng: 107.6328715 },
    { lat: -6.972901, lng: 107.6329023 },
    { lat: -6.9731925, lng: 107.6331504 },
    { lat: -6.9732604, lng: 107.6331477 },
    { lat: -6.9732937, lng: 107.6331035 },
    { lat: -6.9732995, lng: 107.6330596 },
    
  ];
  const Jalan26 = new google.maps.Polyline({
    path: Jalan26Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan26.setMap(map);

  const Jalan27Coords = [
    { lat: -6.9720845, lng: 107.633436 },
    { lat: -6.9703699, lng: 107.6309703 },
    { lat: -6.9702767, lng: 107.6309147 },
    { lat: -6.9697602, lng: 107.6307189 },
    { lat: -6.9694221, lng: 107.629233 },

  ];
  const Jalan27 = new google.maps.Polyline({
    path: Jalan27Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan27.setMap(map);

  const Jalan28Coords = [
    { lat: -6.9710314, lng: 107.6308727 },
    { lat: -6.9715461, lng: 107.6305248 },
    { lat: -6.9717911, lng: 107.6304551 },
    { lat: -6.9718976, lng: 107.6304551 },
    { lat: -6.9719295, lng: 107.630219 },
    { lat: -6.9735926, lng: 107.6301834 },

  ];
  const Jalan28 = new google.maps.Polyline({
    path: Jalan28Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan28.setMap(map);

  const Jalan29Coords = [
    { lat: -6.9740171, lng: 107.6306875 },
    { lat: -6.9739501, lng: 107.6316478 },
    { lat: -6.9739666, lng: 107.6325932 },

  ];
  const Jalan29 = new google.maps.Polyline({
    path: Jalan29Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan29.setMap(map);

  const Jalan30Coords = [
    { lat: -6.9711702, lng: 107.6287718 },
    { lat: -6.971109, lng: 107.6269707 },
    { lat: -6.9702025, lng: 107.6270029 },
    { lat: -6.9701998, lng: 107.6275957 },
    { lat: -6.9696474, lng: 107.6276198 },
    { lat: -6.9696673, lng: 107.6281911 },
    { lat: -6.9702411, lng: 107.6281751 },
    { lat: -6.9711436, lng: 107.628159 },
    { lat: -6.971113, lng: 107.6281603 },

  ];
  const Jalan30 = new google.maps.Polyline({
    path: Jalan30Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan30.setMap(map);

  const Jalan31Coords = [
    { lat: -6.9711242, lng: 107.6275361 },
    { lat: -6.9708266, lng: 107.6275723 },
    { lat: -6.9701998, lng: 107.6275957 },

  ];
  const Jalan31 = new google.maps.Polyline({
    path: Jalan31Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan31.setMap(map);

  const Jalan32Coords = [
    { lat: -6.9708252, lng: 107.6269808 },
    { lat: -6.9708266, lng: 107.6275723 },
    { lat: -6.9708984, lng: 107.62879 },

  ];
  const Jalan32 = new google.maps.Polyline({
    path: Jalan32Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan32.setMap(map);

  const Jalan33Coords = [
    { lat: -6.9705345, lng: 107.6269905 },
    { lat: -6.9705411, lng: 107.6275806 },
    { lat: -6.9706197, lng: 107.6288064 },

  ];
  const Jalan33 = new google.maps.Polyline({
    path: Jalan33Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan33.setMap(map);

  const Jalan34Coords = [
    { lat: -6.9701998, lng: 107.6275957 },
    { lat: -6.9702835, lng: 107.6288231 },

  ];
  const Jalan34 = new google.maps.Polyline({
    path: Jalan34Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan34.setMap(map);

  const Jalan35Coords = [
    { lat: -6.9699022, lng: 107.6276085 },
    { lat: -6.9699603, lng: 107.6288104 },

  ];
  const Jalan35 = new google.maps.Polyline({
    path: Jalan35Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  Jalan35.setMap(map);

  const Jalan36Coords = [
    { lat:-6.9735926 , lng:107.6301834  },
    { lat:-6.9736009 , lng: 107.6301873  },
    { lat:-6.9735936 , lng:107.630252  },
    { lat:-6.9735876 , lng:107.6303181  },
    { lat:-6.9735989 , lng:107.6303912  },
    { lat:-6.9736229 , lng:107.6304582  },
    { lat:-6.9736621 , lng:107.6305213  },
    { lat:-6.9737081 , lng:107.6305736  },
    { lat:-6.9737527 , lng:107.6306091  },
    { lat:-6.9738265 , lng:107.63065  },
    { lat:-6.9738825 , lng:107.6306688  },
    { lat:-6.9739444 , lng:107.6306768  },
    { lat:-6.9740122 , lng:107.6306788  },
    { lat:-6.9740741 , lng:107.6306674  },
    { lat:-6.9741347 , lng:107.630644  },
    { lat:-6.9741826 , lng:107.6306185  },
    { lat:-6.9742306 , lng:107.6305836  },
    { lat:-6.9742838 , lng:107.6305253  },
    { lat:-6.9743104 , lng:107.6304871  },
    { lat:-6.9743497 , lng:107.63041  },
    { lat:-6.9743597 , lng:107.6303717  },
    { lat:-6.9743697 , lng:107.630298  },
    { lat:-6.974369 , lng:107.6302276  },
    { lat:-6.9743487 , lng:107.6301568  },
    { lat:-6.9743221 , lng:107.6300965  },
    { lat:-6.9742838 , lng:107.6300388  },
    { lat:-6.9742359 , lng:107.6299882  },
    { lat:-6.9741793 , lng:107.6299469  },
    { lat:-6.9741164 , lng:107.6299161  },
    { lat:-6.9740512 , lng:107.629898  },
    { lat:-6.9739843 , lng:107.6298913  },
    { lat:-6.9739144 , lng:107.6298966  },
    { lat:-6.9738379 , lng:107.6299174  },
    { lat:-6.9737916 , lng:107.6299406  },
    { lat:-6.9737417 , lng:107.6299734  },
    { lat:-6.9737017 , lng:107.630009  },
    { lat:-6.9736625 , lng:107.6300542 },
    { lat:-6.9736378 , lng:107.6300951  },
    { lat:-6.9736192 , lng:107.6301323  },
    { lat:-6.9736056 , lng:107.6301699  },
    { lat:-6.9736016 , lng:107.6301873  },

  ];
  const Jalan36 = new google.maps.Polyline({
    path: Jalan36Coords,
    geodesic: true,
    strokeColor: "#808080",
    strokeOpacity: 1.0,
    strokeWeight: 2,
  });

  //Fakultas Industri kreatif
  {  const contentString =
     '<div id="content">' +
     '<div id="siteNotice">' +
     "</div>" + '<img src="FIK.jpg" width="160" height="90" alt="logo">'+
     '<h1 id="firstHeading" class="firstHeading">Fakultas Industri Kreatif</h1>' +
     '<div id="bodyContent">' +
     "<p><b>Fakultas Industri Kreatif</b>, atau FIK memiliki satu gedung berlantai 5 yaitu Gedung Sebatik yang berfungsi sebagai gedung kuliah sekaligus administrasi Fakultas Industri Kreatif dengan total luas 6,295.30 m2.</p>" +
     '<p>website: <a href="http://sci.telkomuniversity.ac.id/">' +
     "http://sci.telkomuniversity.ac.id/</a> " +
     "</div>" +
     "</div>";
  
     const infowindow = new google.maps.InfoWindow({
     content: contentString,
     });
     const marker = new google.maps.Marker({
     position: {lat: -6.972066745491242, lng : 107.63125208423992},
     map,
     title: "Fakultas Industri Kreatif",animation: google.maps.Animation.DROP,
     });

     marker.addListener("click", () => {
     infowindow.open({
      anchor: marker,
      map,
      shouldFocus: false,
     });});
     function toggleBounce() {
      if (marker.getAnimation() !== null) {marker.setAnimation(null);}
      else {marker.setAnimation(google.maps.Animation.BOUNCE)};}
    }

    //Fakultas Ekonomi Bisnis
  {  const contentString =
     '<div id="content">' +
     '<div id="siteNotice">' +
     "</div>" + '<img src="FEB.jpg" width="160" height="90" alt="logo">'+
     '<h1 id="firstHeading" class="firstHeading">Fakultas Ekonomi </h1>' +
     '<div id="bodyContent">' +
     "<p><b>Fakultas Ekonomi Business</b>, Bisnis (FEB) terdiri dari 6 (enam) gedung yaitu Gedung Miossu memiliki 5 lantai dengan total luas 2,503.17 m2 dan Gedung Maratua memiliki 5 lantai dengan total luas 2366.70 m2, keduanya berfungsi yang berfungsi sebagai gedung kuliah dan administrasi Fakultas Ekonomi Bisnis. Berikutnya Gedung Marore memiliki 4 lantai dengan total luas 3,379.00 m2 yang berfungsi sebagai gedung kuliah dan administrasi pascasarjana-MM (S-2 Manajemen). Selanjutnya Gedung Miagas satu lantai dengan total luas 192.25 m2 berfungsi sebagai TPCC, Gedung Marampit satu lantai dengan total luas 192.25 m2 berfungsi sebagai entrepreneurship program, dan yang terakhir adalah Gedung Mantewaru memiliki 5 lantai dengan total luas 14,617.28 m2 yang berfungsi sebagai gedung dekanat FEB</p>" +
     '<p>website: <a href="http://seb.telkomuniversity.ac.id/">' +
     "http://seb.telkomuniversity.ac.id/</a> " +
     "</div>" +
     "</div>";
  
     const infowindow = new google.maps.InfoWindow({
     content: contentString,
     });
     const marker = new google.maps.Marker({
     position: {lat: -6.971326030003865, lng: 107.63174894092275},
     map,
     title: "Fakultas Ekonomi Bisnis",animation: google.maps.Animation.DROP,
     });

     marker.addListener("click", () => {
     infowindow.open({
      anchor: marker,
      map,
      shouldFocus: false,
     });});
     function toggleBounce() {
      if (marker.getAnimation() !== null) {marker.setAnimation(null);}
      else {marker.setAnimation(google.maps.Animation.BOUNCE)};}
    }

    
  
  






  

}
  





</script>
  

    <!-- Async script executes immediately and must be after any DOM elements used in callback. -->
    <script
      src="https://maps.googleapis.com/maps/api/"
      async
    ></script>
  </body>
</html>

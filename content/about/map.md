---
title: "오시는 길"
---

<div id="map" style="height: 400px; width: 100%;"></div>
<script>
  function initMap() 
    var location = { lat: 35.8460469, lng: 127.1346038 };  // 전북대학교 좌표
    var map = new google.maps.Map(document.getElementById('map'), {
      zoom: 15,  // 줌 레벨
      center: location
    });

    var marker = new google.maps.Marker({
      position: location,
      map: map,
      title: "전북대학교"  // 마커 타이틀
    });

</script>

<script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDAWMtlLomWV9QjZ7321283Y5JQi3fsFdg&callback=initMap">
</script>

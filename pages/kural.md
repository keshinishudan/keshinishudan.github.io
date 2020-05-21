---
layout: page
title: Thirukkural Search
permalink: /kural/
---


<style>

#myInput {
  background-image: url('/assets/images/searchicon.png');
  background-position: 10px 10px;
  background-repeat: no-repeat;
  width: 80%;
  font-size: 16px;
  padding: 12px 20px 12px 40px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
}

#akhil {
  border-collapse: collapse;
  width: 100%;
  border: 1px solid #ddd;
  font-size: 18px;
}

#akhil th, #akhil td {
  text-align: left;
  padding: 12px;
}

#akhil tr {
  border-bottom: 1px solid #ddd;
}

#akhil tr.header, #akhil tr:hover {
  background-color: #00ffff;
}
</style>



<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for kurals.." title="Type in a name">


<table id="akhil">

{% assign seetharam = site.kural | sort: "abskno" %}
{% for kural in seetharam %}

<tr>
  <td><a href="{{ kural.url }}">{{ kural.kuralno }} - {{ kural.athinameen }} - {{ kural.athinametr }} - {{ kural.athiname }}</a></td>
<!---
<td><a href="{{ kural.url }}">{{ kural.athinameen }}</a></td>
  <td><a href="{{ kural.url }}">{{ kural.athinametr }}</a></td>
--> 
</tr>

{% endfor %}

</table>



<script>
function myFunction() {
  var input, filter, table, tr, td, i, txtValue;
  input = document.getElementById("myInput");
  filter = input.value.toUpperCase();
  table = document.getElementById("akhil");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[0];
    if (td) {
      txtValue = td.textContent || td.innerText;
      if (txtValue.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
</script>



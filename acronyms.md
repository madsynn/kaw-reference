<link href="//github.com/madsynn/kaw-reference/assets/css/acronyms.css" media="all" rel="stylesheet" type="text/css">
# kaw-reference
My Kingdoms at War Reference Guide

<style>
* {
  box-sizing: border-box;
}

#myInput {
  background-image: url('/css/searchicon.png');
  background-position: 10px 10px;
  background-repeat: no-repeat;
  width: 100%;
  font-size: 16px;
  padding: 12px 20px 12px 40px;
  border: 1px solid #ddd;
  margin-bottom: 12px;
}

#myTable {
  border-collapse: collapse;
  width: 100%;
  border: 1px solid #ddd;
  font-size: 18px;
}

#myTable th, #myTable td {
  text-align: left;
  padding: 2px;
}

#myTable tr {
  border-bottom: 1px solid #ddd;
}

#myTable tr.header, #myTable tr:hover {
  background-color: #f1f1f1;
}
</style>

 <input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for names..">

<table id="myTable">
  <tr class="header">
    <th style="width:30%;">Acronym / Abbreviation</th>
    <th style="width:70%;">Definition</th>
  </tr>
<tr><td>Def</td><td>Defense</td></tr>

<tr><td>Scout Bomb</td><td>To scout someone a lot</td></tr>
<tr><td>Assa</td><td>To Assassinate someone</td></tr>
<tr><td>Keep</td><td>Owning an ally</td></tr>
<tr><td>BL</td><td>Battle List</td></tr>
<tr><td>SC or “Circle”</td><td>Summoning Circle</td></tr>
<tr><td>WA or “Aviary”</td><td>War Aviary</td></tr>
<tr><td>sos</td><td>Stronghold of Shadows</td></tr>
<tr><td>toc</td><td>Temple of Clarity</td></tr>
<tr><td>coe</td><td>Circle Of Elements</td></tr>
<tr><td>tor</td><td>Temple Of Reckoning</td></tr>
<tr><td>Hybrid Build 15/1/5/3</td><td>5 Circle Of Elements, 1 Temple Of Reckoning, 5 Stronghold Of Shadows, 3 Temple Of Clarity</td></tr>
<tr><td>lvl</td><td>Level</td></tr>
<tr><td>Plunder</td><td>The gold you earn from an attack</td></tr>
<tr><td>Ally Plunder</td><td>The gold your allies give you</td></tr>
<tr><td>Tax</td><td>The amount of gold taken away in war</td></tr>
<tr><td>BTA</td><td>Bonus To Allies</td></tr>
<tr><td>K</td><td>Thousand</td></tr>
<tr><td>M/Mil</td><td>Million</td></tr>
<tr><td>Bil/B</td><td>Billion</td></tr>
<tr><td>Strip</td><td>Hire allies and farm a player</td></tr>
<tr><td>OSW</td><td>Off system war</td></tr>
<tr><td>BUMP</td><td>Bring Up My Post (On Forums)</td></tr>
<tr><td>Devs</td><td>People who made Kingdoms at War</td></tr>
<tr><td>ToS</td><td>Terms of Service</td></tr>
<tr><td>Bypassing</td><td>Avoiding the profanity filter</td></tr>
<tr><td>Stats</td><td>Your bonus to allies</td></tr>
<tr><td>HC</td><td>Health Crystal</td></tr>
<tr><td>Nob</td><td>Nobility Points</td></tr>
<tr><td>Maxed</td><td>LC with all fully upgraded buildings</td></tr>
<tr><td>Regen</td><td>To get more soldiers/spies</td></tr>
<tr><td>Full</td><td>To have all of your soldiers/spies</td></tr>
<tr><td>Lurking</td><td>Being in a chat but not talking</td></tr>
<tr><td>Sub</td><td>A Subterranean Factory</td></tr>
<tr><td>T1, T2, T3</td><td>Teir 1, Teir 2, Teir 3</td></tr>
<tr><td>Attk</td><td>Attack</td></tr>
<tr><td>zs sz</td><td>Zero Spies</td></tr>
<tr><td>zt tz</td><td>Zero Troops</td></tr>
<tr><td>LB</td><td>LeaderBoard</td></tr>
<tr><td>WC</td><td>World Chat</td></tr>
<tr><td>CC</td><td>Clan Chat</td></tr>
<tr><td>AC</td><td>Ally Chat</td></tr>
<tr><td>Pinned</td><td>to keep a defender Too Weak</td></tr>
<tr><td>Volley</td><td>Hiring 1 person back and forth</td></tr>
<tr><td>Farming</td><td>To hit 1 person over 5x daily</td></tr>
<tr><td>OSF</td><td>Open Secret Farm</td></tr>
<tr><td>Pots</td><td>Items from The Marketplace</td></tr>
<tr><td>LC</td><td>Land Complete (Buying all land)</td></tr>
<tr><td>DTW</td><td>Defender Too Weak</td></tr>
<tr><td>PM</td><td>Private Message </td></tr>
<tr><td>SKO</td><td>Self Knock Out</td></tr>
<tr><td>ADT</td><td>Attack Defense Tower</td></tr>
<tr><td>Kotfe</td><td>Knights of the fire emblem</td></tr>
<tr><td>AoW</td><td>Art Of War</td></tr>

</table>

<script>
function myFunction() {
  var input, filter, table, tr, td, i;
  input = document.getElementById("myInput");
  filter = input.value.toUpperCase();
  table = document.getElementById("myTable");
  tr = table.getElementsByTagName("tr");
  for (i = 0; i < tr.length; i++) {
    td = tr[i].getElementsByTagName("td")[0];
    if (td) {
      if (td.innerHTML.toUpperCase().indexOf(filter) > -1) {
        tr[i].style.display = "";
      } else {
        tr[i].style.display = "none";
      }
    }       
  }
}
</script>

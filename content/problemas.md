+++
date = '2026-04-10T15:37:33-03:00'
title = 'Problemas da Maratona Fase Regional'
toc= false
+++

<!-- DataTables CSS -->
<link rel="stylesheet" href="https://cdn.datatables.net/1.13.8/css/jquery.dataTables.min.css">

bla 
<!-- Tabela -->
<table id="tabela-problemas">
  <thead>
    <tr>
      <th>Ano</th>
      <th>Problema</th>
      <th>Submissões</th>
      <th>Aceitos</th>
      <th>%</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>2024</td><td>A</td><td>1791</td><td>813</td><td>45</td></tr>
    <tr><td>2024</td><td>B</td><td>185</td><td>42</td><td>23</td></tr>
    <tr><td>2024</td><td>C</td><td>91</td><td>15</td><td>16</td></tr>
    <tr><td>2024</td><td>D</td><td>14</td><td>3</td><td>21</td></tr>
    <tr><td>2024</td><td>E</td><td>994</td><td>704</td><td>71</td></tr>
    <tr><td>2024</td><td>F</td><td>956</td><td>631</td><td>66</td></tr>
    <tr><td>2024</td><td>G</td><td>199</td><td>0</td><td>0</td></tr>
    <tr><td>2024</td><td>H</td><td>613</td><td>83</td><td>14</td></tr>
    <tr><td>2024</td><td>I</td><td>583</td><td>37</td><td>6</td></tr>
    <tr><td>2024</td><td>J</td><td>22</td><td>0</td><td>0</td></tr>
    <tr><td>2024</td><td>K</td><td>814</td><td>113</td><td>14</td></tr>
    <tr><td>2024</td><td>L</td><td>1349</td><td>288</td><td>21</td></tr>
  </tbody>
</table>

<!-- Scripts -->
<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
<script src="https://cdn.datatables.net/1.13.8/js/jquery.dataTables.min.js"></script>

<script>
document.addEventListener("DOMContentLoaded", function() {
  if (window.jQuery) {
    $('#tabela-problemas').DataTable({
      pageLength: 25,
      order: [[0, 'desc']]
    });
  }
});
</script>

<!DOCTYPE html>
<html>
<head>
<style>

  table {
    border-collapse: collapse;
    width: 300px;
  }
  th, td {
    border: 1px solid black;
    padding: 8px;
    text-align: left;
  }
  
  th {
    background-color: #808080;
    color: white;
  }
  
  tr:nth-child(odd) td {
    background-color: #ffff00;
  }
  tr:nth-child(even) td {
    background-color: #ffffff;
  }

  
  .fixed-div {
    position: fixed;
    top: 10px;
    right: 10px;
    width: 150px;
    padding: 10px;
    border: 3px solid #7eb65d; 
    background-color: white;
  }
</style>
</head>
<body>

  <table>
    <tr>
      <th>Firstname</th>
      <th>Lastname</th>
    </tr>
    <tr>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <td>3</td>
      <td>3</td>
    </tr>
  </table>

  <div class="fixed-div">
    This div element has position: fixed;
  </div>

</body>
</html>

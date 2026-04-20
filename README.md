<!DOCTYPE html>
<html>
<head>
<style>
  /* 移除預設邊距，確保最左最右 */
  body {
    margin: 0;
    padding: 0;
    font-family: sans-serif;
  }

  /* 表格樣式 */
  table {
    border-collapse: collapse;
    margin: 0; /* 確保貼齊最左 */
  }

  th, td {
    border: 1px solid #999;
    padding: 12px 25px;
    font-size: 20px;
    text-align: left;
  }

  /* 標題列：深灰色背景、白色文字 */
  th {
    background-color: #717171;
    color: white;
  }

  /* 內容顏色：黃 -> 白 -> 黃 (對照題目截圖) */
  tr:nth-child(2) td { background-color: #ffff00; } /* 數字 1 那行 */
  tr:nth-child(3) td { background-color: #ffffff; } /* 數字 2 那行 */
  tr:nth-child(4) td { background-color: #ffff00; } /* 數字 3 那行 */

  /* 固定在最右側的 Div */
  .fixed-div {
    position: fixed;
    top: 20px;
    right: 20px;
    width: 200px;
    height: 150px;
    border: 4px solid #82b34a; /* 綠色粗框 */
    background-color: white;
    padding: 15px;
    box-sizing: border-box; /* 確保框線不撐開寬度 */
    display: flex;
    align-items: center;
    font-size: 18px;
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

<!DOCTYPE html>
<html>
<head>
<style>
  body {
    font-family: serif;
    margin: 20px;
  }

  /* 表格樣式設定 */
  table {
    border-collapse: collapse;
    width: 350px; /* 設定寬度 */
    float: left;  /* 讓表格靠左 */
  }

  th, td {
    border: 2px solid #444; /* 較粗的深色邊框 */
    padding: 10px;
    font-size: 20px;
  }

  /* 標題列：深灰色背景、白色文字 */
  th {
    background-color: #717171;
    color: white;
    text-align: left;
  }

  /* 依照圖片：內容第 1、3 列為黃色，第 2 列為白色 */
  tr:nth-child(2) td, tr:nth-child(4) td {
    background-color: #ffff00;
  }
  
  tr:nth-child(3) td {
    background-color: #ffffff;
  }

  /* 綠色方塊：固定在視窗最右上方 */
  .fixed-div {
    position: fixed;
    top: 50px;    /* 距離頂部距離 */
    right: 50px;  /* 距離右側距離 */
    width: 160px;
    height: 140px;
    border: 5px solid #82b34a; /* 圖片中的綠色粗框 */
    background-color: white;
    padding: 10px;
    font-size: 18px;
    display: flex;
    align-items: center;
  }
</style>
</head>
<body>

  <table>
    <thead>
      <tr>
        <th>Firstname</th>
        <th>Lastname</th>
      </tr>
    </thead>
    <tbody>
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
    </tbody>
  </table>

  <div class="fixed-div">
    This div element has position: fixed;
  </div>

</body>
</html>

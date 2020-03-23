<!DOCTYPE html>
<html>
<head>
    <title>Project 3</title>

    <script>
    </script>
    	<style>
      * {
        text-align: center;
      }

      #submit{
        margin: auto;
      }
     
      #analyze{
        margin: auto;
      }
     
      #data{
        width: 100%;
      }
      #data td{
        border: black solid;
        height: 20px;
        width: 20vw;
      }
        </style>
</head>
<body>
  <h1>Class Marksheet</h1>

        <form>
          <table id="submit">
            <tr>
              <td>Họ tên</td>
              <td><input  name="username" id="username" /></td>
            </tr>
            <tr>
              <td>Điểm toán</td>
              <td><input type="math" name="math" id="math"/></td>
            </tr>
            <tr>
              <td>Điểm lý</td>
              <td><input  name="physics" id="physics"/></td>
            </tr>
            <tr>
              <td >Điểm hóa</td>
              <td><input type="chemistry" name="chemistry" id="chemistry"/></td>
            </tr>
            <tr></tr>
            <tr>
              <td><br><br></td>
              <td>
                <input type="button" value="Nhập" id="submit" onclick="validate()"/>
              </td>
            </tr>
          </table>
          <table id="data">
            <tr>
              <td>STT</td>
              <td>Họ tên</td>
              <td>Toán</td>
              <td>Lý</td>
              <td>Hóa</td>
              <td>Trung bình</td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
          </table>
          <table id="analyze">
            <tr>
              <td>
                <input type="button" value="Tính điểm trung bình" id="submit" onclick="validate()"/>
              </td>
              <td>
                <input type="button" value="Xác định học sinh giỏi" id="submit" onclick="validate()"/>
              </td>
          </table>
        </form>
    </script>
</body>
</html>

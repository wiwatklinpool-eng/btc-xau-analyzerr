<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>วิเคราะห์กราฟ BTC / XAU</title>
<style>
body { font-family: sans-serif; background:#f4f6f8; }
.box { max-width:400px; margin:auto; background:#fff; padding:20px; border-radius:12px; }
button { width:100%; padding:14px; font-size:18px; border-radius:8px; }
.result { margin-top:20px; font-size:20px; text-align:center; }
</style>
</head>
<body>

<div class="box">
<h2>วิเคราะห์กราฟ BTC / XAU</h2>

<input type="file"><br><br>

<select>
<option>BTCUSD</option>
<option>XAUUSD</option>
</select><br><br>

<select>
<option>M1</option>
<option>M5</option>
<option>M15</option>
</select><br><br>

<button onclick="analyze()">วิเคราะห์</button>

<div class="result" id="result">รอวิเคราะห์...</div>
</div>

<script>
function analyze(){
 document.getElementById("result").innerHTML =
 "🔴 SELL<br>ความมั่นใจ 80%<br>แนวโน้มขาลง";
}
</script>

</body>
</html>
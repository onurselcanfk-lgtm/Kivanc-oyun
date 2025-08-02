

<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <title>Kıvanç'ın Hikayesi - Demo</title>
  <style>
    body {
      background: #222;
      color: white;
      font-family: Arial, sans-serif;
      padding: 20px;
      max-width: 600px;
      margin: auto;
    }
    button {
      margin-top: 10px;
      padding: 10px 20px;
      background: #ff5f5f;
      border: none;
      border-radius: 5px;
      color: white;
      cursor: pointer;
    }
    button:hover {
      background: #ff3f3f;
    }
    #result {
      margin-top: 20px;
      padding: 15px;
      background: #333;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <h1>Kıvanç'ın Hikayesi</h1>
  <p>Nurten mesaj attı: "Kıvanç, biz İzmir’deyiz, sen neredesin? Sana uğrayalım."</p>
  <p>Ne yapmak istersin?</p>
  <button onclick="choose('Konum attın, kızlar birazdan kafenin önünde olacaklar.')">Konum at</button>
  <button onclick="choose('Erdoğan’a haber verdin, kızlar geliyor dedin.')">Erdoğan’a haber ver</button>
  <button onclick="choose('Araban Mustang’i yıkatmaya götürmeye karar verdin.')">Arabayı yıkamaya götür</button>

  <div id="result"></div>

  <script>
    function choose(message) {
      const resultDiv = document.getElementById('result');
      resultDiv.textContent = message;
    }
  </script>
</body>
</html>




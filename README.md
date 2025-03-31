<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nala's Sharpening Service Inc.</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5faff;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #2a2a72; /* Lighter blue for better contrast */
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
      max-width: 800px;
      margin: auto;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      overflow-x: auto; /* Ensure the table is responsive */
    }
    th, td {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
    }
    th {
      background-color: #c0d8ff;
    }
    .contact, .waiver {
      background: #eef5ff;
      padding: 15px;
      margin-top: 30px;
      border-left: 5px solid #1e1e50;
    }
  </style>
</head>
<body>
  <header>
    <h1>Nala's Sharpening Service Inc.</h1>
    <p>Professional Knife Sharpening – Reliable, Precise, Fast</p>
  </header>
  <section>
    <h2>Price Catalog</h2>
    <table>
      <tr>
        <th>Knife Type</th>
        <th>Blade Length</th>
        <th>Price</th>
      </tr>
      <tr>
        <td>Small Knives</td>
        <td>Up to 4 inches</td>
        <td>$5</td>
      </tr>
      <tr>
        <td>Medium Knives</td>
        <td>4.1 to 7 inches</td>
        <td>$7</td>
      </tr>
      <tr>
        <td>Large Knives</td>
        <td>7.1 to 10 inches</td>
        <td>$10</td>
      </tr>
      <tr>
        <td>Specialty Knives</td>
        <td>Serrated, cleavers, etc</td>
        <td>$12</td>
      </tr>
      <tr>
        <td>Damaged Knives</td>
        <td>Tip repair / chips</td>
        <td>+$3-$5 extra</td>
      </tr>
      <tr>
        <td>Rush Service</td>
        <td>Same-day turnaround</td>
        <td>+$5</td>
      </tr>
    </table>
    <div class="contact">
      <h3>Contact Us</h3>
      <p>Phone: (323) 245-4237</p>
      <p>Email: <span id="email"></span></p>
    </div>
    <div class="waiver">
      <h3>Disclaimer & Liability Waiver</h3>
      <p>By submitting a knife for sharpening, the client agrees that Nala's Sharpening Service Inc. is not responsible for damage caused by pre-existing blade conditions or poor-quality steel. The client waives all liability and affirms they are the legal owner of the blades submitted for service.</p>
    </div>
  </section>
  <script>
    document.addEventListener('DOMContentLoaded', function() {
      var email = 'otto.estradagarrido' + '@' + 'gmail.com';
      document.getElementById('email').innerText = email;
    });
  </script>
</body>
</html>

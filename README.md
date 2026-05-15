
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saurabh Bhati Portfolio</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:#0f172a;
      color:white;
      display:flex;
      justify-content:center;
      align-items:center;
      height:100vh;
    }

    .card{
      background:#1e293b;
      padding:30px;
      border-radius:20px;
      text-align:center;
      width:320px;
      box-shadow:0 0 20px rgba(0,0,0,0.5);
    }

    .profile-img{
      width:120px;
      height:120px;
      border-radius:50%;
      border:4px solid #38bdf8;
      object-fit:cover;
      margin-bottom:15px;
    }

    h1{
      font-size:28px;
      margin-bottom:10px;
    }

    p{
      color:#cbd5e1;
      margin-bottom:20px;
    }

    .btn{
      display:inline-block;
      padding:12px 25px;
      background:#38bdf8;
      color:black;
      text-decoration:none;
      border-radius:10px;
      font-weight:bold;
      transition:0.3s;
    }

    .btn:hover{
      background:white;
      transform:scale(1.05);
    }

    .socials{
      margin-top:20px;
    }

    .socials a{
      color:white;
      text-decoration:none;
      margin:0 10px;
      font-size:18px;
    }
  </style>
</head>
<body>

  <div class="card">

    <img src="your-image.jpg" alt="Profile" class="profile-img">

    <h1>Saurabh Bhati</h1>

    <p>
      Video Editor • Developer • Creator
    </p>

    <a href="https://instagram.com/saurabhbhatiportfolio" class="btn">
      Follow Me
    </a>

    <div class="socials">
      <a href="#">Instagram</a>
      <a href="#">YouTube</a>
      <a href="#">LinkedIn</a>
    </div>

  </div>

</body>
</html>

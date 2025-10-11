<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>YourGoatViper | Official Links</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap" rel="stylesheet">

  <style>
    /* --- Global Styles --- */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #4f46e5, #7c3aed);
      background-size: 400% 400%;
      animation: gradientMove 12s ease infinite;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      text-align: center;
      padding: 20px;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* --- Card --- */
    .card {
      background: rgba(255, 255, 255, 0.08);
      border: 1px solid rgba(255, 255, 255, 0.15);
      border-radius: 20px;
      padding: 40px 30px;
      backdrop-filter: blur(12px);
      box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
      max-width: 400px;
      width: 100%;
      animation: fadeUp 1s ease forwards;
      transform: translateY(10px);
      opacity: 0;
    }

    @keyframes fadeUp {
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    /* --- Logo --- */
    .logo {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      overflow: hidden;
      border: 3px solid rgba(255, 255, 255, 0.25);
      margin: 0 auto 15px;
      box-shadow: 0 5px 20px rgba(0, 0, 0, 0.4);
      transition: transform 0.3s ease;
    }

    .logo:hover {
      transform: scale(1.05);
    }

    .logo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    /* --- Text --- */
    h1 {
      font-weight: 600;
      font-size: 1.8rem;
      margin-bottom: 6px;
    }

    p {
      font-weight: 400;
      color: rgba(255, 255, 255, 0.8);
      font-size: 0.95rem;
      margin-bottom: 25px;
    }

    /* --- Buttons --- */
    .links {
      display: flex;
      flex-direction: column;
      gap: 14px;
    }

    .btn {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      text-decoration: none;
      background: rgba(255, 255, 255, 0.1);
      border: 1px solid rgba(255, 255, 255, 0.15);
      color: white;
      padding: 12px;
      border-radius: 12px;
      font-weight: 500;
      font-size: 15px;
      transition: all 0.25s ease;
    }

    .btn:hover {
      background: rgba(255, 255, 255, 0.2);
      transform: translateY(-3px);
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
    }

    .btn svg {
      width: 22px;
      height: 22px;
    }

    /* --- Footer --- */
    .footer {
      margin-top: 25px;
      font-size: 13px;
      color: rgba(255, 255, 255, 0.7);
    }

    @media (max-width: 480px) {
      .card {
        padding: 30px 20px;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="logo">
      <img src="logo.png" alt="YourGoatViper Logo">
    </div>

    <h1>YourGoatViper</h1>
    <p>Creator • Streamer • Gamer</p>

    <div class="links">
      <!-- TikTok -->
      <a class="btn" href="https://www.tiktok.com/@yourgoatviper?_t=ZS-90S15LBVKrM&_r=1" target="_blank">
        <svg fill="currentColor" viewBox="0 0 24 24"><path d="M9 3v10.5A4.5 4.5 0 1 0 13.5 18V8h3.75A6.75 6.75 0 1 1 9 3z"/></svg>
        TikTok
      </a>

      <!-- YouTube -->
      <a class="btn" href="https://www.youtube.com/@YourGoatViper" target="_blank">
        <svg fill="currentColor" viewBox="0 0 24 24"><path d="M23.5 6.2s-.2-1.6-.8-2.3c-.8-.9-1.7-.9-2.1-1C17.6 2.5 12 2.5 12 2.5s-5.6 0-8.6.4c-.4.1-1.3.1-2.1 1C.7 4.6.6 6.2.6 6.2S.4 8.3.4 10.4v3.2c0 2.1.2 4.2.2 4.2s.2 1.6.8 2.3c.8.9 1.9.9 2.4 1 1.7.2 7.3.3 7.3.3s5.6 0 8.6-.4c.4-.1 1.3-.1 2.1-1 .6-.7.8-2.3.8-2.3s.2-2.1.2-4.2V10.4c0-2.1-.2-4.2-.2-4.2zM9.6 15.2V7.8l6.3 3.7-6.3 3.7z"/></svg>
        YouTube
      </a>

      <!-- Instagram -->
      <a class="btn" href="https://www.instagram.com/arham_arain333?igsh=NGhobDk1c29rd3oy&utm_source=qr" target="_blank">
        <svg fill="currentColor" viewBox="0 0 24 24"><path d="M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5zm5 6.5A3.5 3.5 0 1 0 15.5 12 3.5 3.5 0 0 0 12 8.5zm4.8-3.7a1.15 1.15 0 1 1-1.15 1.15 1.15 1.15 0 0 1 1.15-1.15z"/></svg>
        Instagram
      </a>

      <!-- WhatsApp -->
      <a class="btn" href="https://wa.me/923348666640" target="_blank">
        <svg fill="currentColor" viewBox="0 0 24 24"><path d="M20.52 3.48A11.93 11.93 0 0 0 12 0C5.373 0 .09 5.283.09 11.91c0 2.103.545 4.155 1.58 5.97L0 24l6.45-1.66A11.877 11.877 0 0 0 12 23.82c6.627 0 11.91-5.283 11.91-11.91 0-3.18-1.238-6.17-3.39-8.43zM12 21.21c-1.36 0-2.695-.35-3.86-.99l-.28-.15-3.83.98.99-3.74L4.6 15.35l-.12-.2A8.06 8.06 0 0 1 3 11.91c0-4.98 4.05-9.03 9.03-9.03 2.41 0 4.68.94 6.39 2.65 1.71 1.71 2.65 3.98 2.65 6.39 0 4.98-4.05 9.03-9.03 9.03z"/></svg>
        WhatsApp
      </a>
    </div>

    <div class="footer">
      © 2025 YourGoatViper — All rights reserved
    </div>
  </div>
</body>
</html>

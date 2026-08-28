# Aether-Trust-Bank
Financial Services
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aether Trust Bank</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      color: #1f2933;
    }

    .header {
      background: #123b5d;
      color: white;
      padding: 18px 25px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .brand h1 {
      margin: 0;
      font-size: 24px;
    }

    .brand p {
      margin: 4px 0 0;
      font-size: 12px;
      opacity: .85;
    }

    .menu-button {
      background: white;
      color: #123b5d;
      width: auto;
      padding: 9px 14px;
      border-radius: 7px;
      font-size: 20px;
    }

    .login {
      max-width: 400px;
      margin: 70px auto;
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,.08);
    }

    .login h2 {
      text-align: center;
    }

    input, textarea, select {
      width: 100%;
      padding: 13px;
      margin: 8px 0 15px;
      border: 1px solid #ccc;
      border-radius: 7px;
      font-size: 14px;
    }

    button {
      padding: 12px 18px;
      border: none;
      border-radius: 7px;
      background: #123b5d;
      color: white;
      font-size: 14px;
      cursor: pointer;
    }

    .dashboard {
      display: none;
      max-width: 950px;
      margin: 25px auto;
      padding: 20px;
    }

    .profile {
      background: white;
      padding: 20px;
      border-radius: 12px;
      display: flex;
      align-items: center;
      gap: 18px;
      margin-bottom: 20px;
      box-shadow: 0 3px 15px rgba(0,0,0,.07);
    }

    .profile img {
      width: 75px;
      height: 75px;
      border-radius: 50%;
      object-fit: cover;
      background: #ddd;
    }

    .profile h2 {
      margin: 0 0 5px;
    }

    .profile p {
      margin: 0;
      color: #666;
    }

    .card {
      background: white;
      padding: 25px;
      margin-bottom: 20px;
      border-radius: 12px;
      box-shadow: 0 3px 15px rgba(0,0,0,.07);
    }

    .balance {
      font-size: 38px;
      font-weight: bold;
      margin-top: 10px;
    }

    .menu {
      display: none;
      background: white;
      padding: 15px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 3px 15px rgba(0,0,0,.08);
    }

    .menu button {
      display: block;
      width: 100%;
      margin: 7px 0;
      text-align: left;
    }

    .transaction {
      padding: 15px 0;
      border-bottom: 1px solid #eee;
    }

    .status {
      color: #16803c;
      font-weight: bold;
      font-size: 13px;
    }

    .logout {
      background: #555;
      width: 100%;
    }

    .section {
      display: none;
    }

    .back {
      background: #666;
      margin-bottom: 15px;
    }

    .success-message {
      display: none;
      padding: 12px;
      background: #d1e7dd;
      color: #0f5132;
      border-radius: 7px;

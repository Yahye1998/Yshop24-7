<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yshop24/7 – Halal Shopping</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #009688;
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.5rem;
    }
    nav a {
      color: white;
      margin-left: 1rem;
      text-decoration: none;
    }
    .search-bar {
      margin: 1rem auto;
      max-width: 500px;
      display: flex;
    }
    .search-bar input {
      flex: 1;
      padding: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 5px 0 0 5px;
    }
    .search-bar button {
      padding: 0.5rem 1rem;
      border: none;
      background: #009688;
      color: white;
      border-radius: 0 5px 5px 0;
      cursor: pointer;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1rem;
      padding: 1rem;
    }
    .product {
      background: white;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    .product img {
      max-width: 100%;
      border-radius: 5px;
    }
    .halal-badge {
      display: inline-block;
      background: green;
      color: white;

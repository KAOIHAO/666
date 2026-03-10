<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>氣泡排序法 Bubble Sort 可視化</title>
  <style>
    body {
      font-family: "Segoe UI", sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: white;
      min-height: 100vh;
      margin: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }
    h1 {
      margin: 20px 0 10px;
      text-shadow: 0 2px 8px rgba(0,0,0,0.4);
    }
    .controls {
      margin: 20px 0;
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      justify-content: center;
    }
    button {
      padding: 12px 24px;
      font-size: 1.1rem;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      background: #ff6b6b;
      color: white;
      transition: all 0.2s;
      box-shadow: 0 4px 15px rgba(0,0,0,0.3);
    }
    button:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(0,0,0,0.4);
    }
    button:disabled {
      background: #777;
      cursor: not-allowed;
      transform: none;
      box-shadow: none;
    }
    .array-container {
      display: flex;
      gap: 8px;
      margin: 30px 0;
      flex-wrap: wrap;
      justify-content: center;
      max-width: 95%;
    }
    .bar {
      width:
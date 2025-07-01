<!DOCTYPE html><html lang="en"><head>  
  <meta charset="UTF-8" />  
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>  
  <meta name="description" content="Mashatho - a free space to reflect, share, and heal through deep thoughts, diary writing and soulful confusion." />
  <title>Thoughts for the Lost</title>  
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      transition: background 0.4s, color 0.4s;
    }
    body.calm {
      background: #f0f8ff;
      color: #333;
    }
    body.dark {
      background: #121212;
      color: #eee;
    }
    body.dark .thought-card, body.dark section {
      background-color: #1e1e1e;
      color: #eee;
      border-left: 4px solid #444;
    }
    body.emotional {
      background: #fef6fb;
      color: #4b0082;
    }
    body.emotional .thought-card, body.emotional section {
      background-color: #fff0f5;
      border-left: 4px solid #c71585;
    }
    body.motivated {
      background: #fff9ec;
      color: #b22222;
    }
    body.motivated .thought-card, body.motivated section {
      background-color: #ffefd5;
      border-left: 4px solid #ff4500;
    }
    header {
      text-align: center;
      background: #2e8b57;
      color: white;
      padding: 2rem;
    }
    header select, header input {
      margin-top: 1rem;
      padding: 0.5rem;
      border-radius: 8px;
      border: none;
      font-size: 1rem;
    }
    main {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }
    .thought-card {
      background: white;
      border-radius: 10px;
      padding: 1.5rem;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    section {
      padding: 2rem;
      background-color: #fff;
      margin: 2rem;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    input, textarea {
      padding: 10px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }
    button {
      padding: 10px;
      border: none;
      border-radius: 8px;
      background-color: #2e8b57;
      color: white;
      cursor: pointer;
    }
    .review, .user-message {
      background-color: #f9f9f9;
      border-left: 4px solid #2e8b57;
      padding: 1rem;
      margin-bottom: 1rem;
      border-radius: 8px;
    }
    .diary-entry {
      background: #fefefe;
      padding:

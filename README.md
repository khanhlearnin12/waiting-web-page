# Waiting-web-page
Humor-CLassic-Dessign  
### 題目: 

<img src="https://github.com/user-attachments/assets/8bbda675-c993-46d9-a083-cbc4fbfcec3a" width="500">
<img src="https://github.com/user-attachments/assets/33d44293-73e2-4516-b61f-c7ee2d8d2cba" width="500">

# HTML
<img src="https://github.com/user-attachments/assets/5d7eca9c-63b9-4b97-bc6c-4d48556ed245" width="200" align='right'>

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Waiting web page</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
<div class="container">
  <p class="small-text">DADDY, CHILL!</p>
  <h1 class="brokenpage">THE PAGE IS <br>BROKEN</h1>
  <p class="promise">(We will be back soon)</p>
  <img src="image/download.jpg" alt="pandameme" class="panda">
</div>
</body>
</html>
```
# CSS 
<img src="https://github.com/user-attachments/assets/396c3484-b54e-4291-8ba9-0b5767a7350a" width="200" align='right'>

```css
/* General Styles */
  body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #952a2a; /* Red background */
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
  }

  /* Container */
  .container {
      display: flex;
      flex-direction: column;
      align-items: center;
  }

  /* Small Text */
  .small-text {
      font-size: 15px;
      letter-spacing: 1px;
      text-transform: uppercase;
      font-weight: bold;
      font-family: 'Popins', sans-serif;
      margin-bottom: 10px;
      animation: dance 1s infinite;
  }

  /* Coming Soon Text */
  .brokenpage {
      font-size: 50px;
      font-weight: bold;
      text-transform: uppercase;
      line-height: 1;
      text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3);
      font-family:'Peace Sans', sans-serif;
      margin-top: 0;
      position: relative;
  }
  .panda {
      width: 500px;
      height: 500px;
      position: relative;
  }
  .promise{
      font-size: 10px;
      font-weight: bold;
      font-family: 'Popins', sans-serif;
      margin-top: -1px;
      position: relative;
  }
```

# Animation
## Dancing word
- Tranformed : 上下的動作
- 0% 100%: 循環的環境
```css
    @keyframes dance {
                0%, 100% {
                    transform: translateY(0);
                }
                25% {
                    transform: translateY(-10px);
                }
                50% {
                    transform: translateY(10px);
                }
                75% {
                    transform: translateY(-10px);
                }
            }
```
# Picture
<img src="image/download.jpg" width="200%" height="200%">

# Commit



# 36popitka
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="MarkStore.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MarkStore.com</title>
</head>
<body>
  <style>
    body {
      background-image: url('https://xakep.ru/wp-content/uploads/2018/03/160322/MOSQUITO.jpg');
    }

  .registration-form {
  position: fixed; /* Экранға бекіту */
  top: 100px; /* Жоғарғы шеттен 10px */
  right: 600px; /* Оң жақ шеттен 10px */
  background-color: black; /* Жартылай мөлдір ақ түс */
  border: 1px solid #ccc; /* Жиек түсі */
  border-radius: 35px; /* Бұрыштарын жұмырлау */
  padding: 15px; /* Ішкі шекара */
  width: 400px; /* Ені */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Көлеңке */
  z-index: 1000; /* Ең үстіңгі қабатта көрсету */
}

.registration-form  {
  margin-bottom: 10px;
  font-size: 18px;
  text-align: center;
}

.registration-form label {
  font-size: 14px;
  margin-bottom: 5px;
  display: block;
}

.registration-form input,
.registration-form select {
  width: 95%; /* Ені толық */
  padding: 8px;
  margin-bottom: 10px;
  border: 1px solid #ccc;
  border-radius: 15px;
  font-size: 15px;
}
.tus {
  text-decoration: none;
    color: white;
    background-color: #007BFF;
    padding: 10px 40px;
    border-radius: 5px;
    font-size: 18px;
    font-weight: bold;
    transition: background-color 0.3s ease;
}

.tus:hover {
  background-color: blue;
}
label{
  color: white;
}
.registration-form {
    text-align: center;
    animation: slideIn 2s ease-out forwards; /* Анимация */
    opacity: 0; /* Алғашында көрінбейді */
}

/* Анимация */
@keyframes slideIn {
    0% {
        transform: translateY(-100%); /* Экранның үстінен кіреді */
        opacity: 0; /* Толығымен көрінбейді */
    }
    50% {
        transform: translateY(10%); /* Экранның ортасына жақындайды */
        opacity: 0.5;
    }
    100% {
        transform: translateY(0); /* Тоқтайды */
        opacity: 1; /* Толығымен көрінеді */
    }
}
  </style>
  <div class="registration-form">
  <h3>Тіркелу</h3>
  <h3>Кіру</h3>
  <form>
    <label for="username">Пайдаланушы аты:</label>
    <input type="text" id="username" name="username" required>

    <label for="phone">Телефон нөмірі:</label>
    <input type="tel" id="phone" name="phone" required>

    <label for="password">Құпия сөз:</label>
    <input type="password" id="password" name="password" required>

    <label for="age">Жасы:</label>
    <input type="number" id="age" name="age" required>

    <label for="gender">Жынысы:</label>
    <select id="gender" name="gender" required>
      <option value="male">Ер</option>
      <option value="female">Әйел</option>
    </select>

  <button type="submit" class="tus"> <a href="markstore.html">Тіркелу</a></button>
    <br> <br><br>
  <button type="submit" class="tus"> <a href="markstore.html">Кіру</a></button>
  </form>
</div> 
</body>
</html>

!doctype html>
<html lang="en">

<head>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<title>Document</title>
</head>
<section>
	<h1 style="background-color: blueviolet;
               color: white;
               border: 3px solid black;">
		Воды сегодня нет
	</h1>
</section>
<style>
	link rel
</style>

<body>
	Привет, Костя и Арина. Оля
</body>
<iframe
	src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d42451.66354588046!2d35.478200259706604!3d48.31767867171964!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40dc02b70ecaa0a7%3A0x78f8232871025dc!2z0KHQuNC90LXQu9GM0L3QuNC60L7QstC-LCDQlNC90LXQv9GA0L7Qv9C10YLRgNC-0LLRgdC60LDRjyDQvtCx0LvQsNGB0YLRjA!5e0!3m2!1sru!2sua!4v1795011191650!5m2!1sru!2sua"
	width="600" height="450" style="border: 0" allowfullscreen="" loading="lazy"
	referrerpolicy="strict-origin-when-cross-origin"></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyZSCqWpatg?si=OOU2v2v_9gDkt8Y6"
	title="YouTube video player" frameborder="0"
	allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
	referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
</iframe>

<body>
	<audio controls source src="./Дорога к мечте.mp3"></audio>
</body>
<main>
	<a href="#contacts">Контакты</a>

	<section id="contacts">
		<h2>Мои контакты</h2>
		<p>Телефон: +380 00 000 00 00</p>
		<p>Email: example@gmail.com</p>
		<p>Telegram: @example</p>
	</section>
	<section>
		<h1 style="color: blueviolet;">Торт на ужин</h1>
	</section>
</main>
<!DOCTYPE html>
<html lang="ru">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Оформление заказа</title>

	<style>
		body {
			font-family: Arial, sans-serif;
			background-color: #f2f2f2;
			padding: 20px;
		}

		.order-form {
			max-width: 500px;
			margin: auto;
			background-color: white;
			padding: 20px;
			border: 2px solid blueviolet;
			border-radius: 12px;
		}

		h1 {
			text-align: center;
			color: blueviolet;
		}

		label {
			display: block;
			margin-top: 15px;
			font-weight: bold;
		}

		input,
		select,
		textarea {
			width: 100%;
			box-sizing: border-box;
			padding: 10px;
			margin-top: 5px;
			border: 1px solid #aaa;
			border-radius: 6px;
			font-size: 16px;
		}

		button {
			width: 100%;
			padding: 12px;
			margin-top: 20px;
			background-color: blueviolet;
			color: white;
			border: none;
			border-radius: 6px;
			font-size: 17px;
			cursor: pointer;
		}

		button:hover {
			background-color: purple;
		}

		.order-result {
			max-width: 500px;
			margin: 25px auto;
			padding: 20px;
			background-color: #eee5ff;
			border: 3px solid blueviolet;
			border-radius: 12px;
			display: none;
		}

		.order-result h2 {
			color: blueviolet;
		}

		/* Подсветка полей при наведении мышкой */
		input:hover,
		select:hover,
		textarea:hover {
			background-color: #f0e5ff;
			border: 1px solid blueviolet;
		}

		/* Подсветка поля при нажатии */
		input:focus,
		select:focus,
		textarea:focus {
			background-color: #eee0ff;
			border: 2px solid blueviolet;
			outline: none;
		}

		/* Цвет текста, который вводит покупатель */
		input,
		select,
		textarea {
			color: #4b237a;
			transition: 0.3s;
		}

		/* Цвет подсказок внутри пустых полей */
		input::placeholder,
		textarea::placeholder {
			color: #999999;
		}
	</style>
</head>

<body>

	<div class="order-form">

		<h1>Оформление заказа</h1>

		<form id="orderForm">

			<label>Фамилия:</label>
			<input type="text" id="surname" required>

			<label>Имя:</label>
			<input type="text" id="name" required>

			<label>Телефон:</label>
			<input type="tel" id="phone" placeholder="+380..." required>

			<label>Служба доставки:</label>
			<select id="delivery" required>
				<option value="">Выберите доставку</option>
				<option value="Новая почта">Новая почта</option>
				<option value="Укрпочта">Укрпочта</option>
			</select>

			<label>Город:</label>
			<input type="text" id="city" required>

			<label>Отделение или почтовый индекс:</label>
			<input type="text" id="branch" required placeholder="Номер отделения или индекс">

			<label>Адрес доставки (улица, дом):</label>
			<input type="text" id="address" placeholder="Если требуется">

			<label>Дополнительная заметка:</label>
			<textarea id="note" rows="4" placeholder="Ваши пожелания..."></textarea>

			<button type="submit">Оформить заказ</button>

		</form>
	</div>

	<div class="order-result" id="orderResult">

		<h2>Ваш заказ</h2>

		<p><b>Фамилия:</b> <span id="resultSurname"></span></p>
		<p><b>Имя:</b> <span id="resultName"></span></p>
		<p><b>Телефон:</b> <span id="resultPhone"></span></p>
		<p><b>Доставка:</b> <span id="resultDelivery"></span></p>
		<p><b>Город:</b> <span id="resultCity"></span></p>
		<p><b>Отделение / индекс:</b> <span id="resultBranch"></span></p>
		<p><b>Адрес:</b> <span id="resultAddress"></span></p>
		<p><b>Заметка:</b> <span id="resultNote"></span></p>

	</div>

	<script>
		document.getElementById("orderForm")
			.addEventListener("submit", function (event) {

				event.preventDefault();

				document.getElementById("resultSurname").textContent =
					document.getElementById("surname").value;

				document.getElementById("resultName").textContent =
					document.getElementById("name").value;

				document.getElementById("resultPhone").textContent =
					document.getElementById("phone").value;

				document.getElementById("resultDelivery").textContent =
					document.getElementById("delivery").value;

				document.getElementById("resultCity").textContent =
					document.getElementById("city").value;

				document.getElementById("resultBranch").textContent =
					document.getElementById("branch").value;

				document.getElementById("resultAddress").textContent =
					document.getElementById("address").value || "Не указан";

				document.getElementById("resultNote").textContent =
					document.getElementById("note").value || "Нет заметки";

				document.getElementById("orderResult").style.display = "block";

			});
	</script>

</body>

</html>

</html>

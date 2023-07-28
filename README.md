# idade-avalia-o-
<!DOCTYPE html>
<html>
<head>
	<title>Fases da Vida</title>
	<meta charset="UTF-8">
	<style>
		body {
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: center;
			height: 100vh;
			margin: 0;
			padding: 0;
			background-color: #f0f0f0; /* Light gray background */
			font-family: Arial, sans-serif;
			color: #333; /* Dark gray text color */
		}

		h1 {
			margin-bottom: 20px;
			color: #004080; /* Navy blue header color */
		}

		label {
			margin-bottom: 5px;
			color: #006600; /* Dark green label color */
		}

		input {
			margin-bottom: 10px;
			padding: 5px;
			border: 1px solid #ccc; /* Light gray border */
			border-radius: 4px;
		}

		button {
			padding: 10px 20px;
			font-size: 16px;
			cursor: pointer;
			background-color: #0066cc; /* Blue button background color */
			color: #fff; /* White button text color */
			border: none;
			border-radius: 4px;
		}

		#resultado {
			margin-top: 20px;
			font-size: 18px;
			font-weight: bold;
		}
	</style>
	<script>
		function verificarFaseDaVida() {
			var nome = document.getElementById("nome").value;
			var idade = parseInt(document.getElementById("idade").value);

			var fase;

			if (idade <= 11) {
				fase = "Criança";
			} else if (idade <= 18) {
				fase = "Adolescente";
			} else if (idade <= 65) {
				fase = "Adulto";
			} else {
				fase = "Idoso";
			}

			document.getElementById("resultado").innerHTML = "Olá " + nome + ", você é " + fase + ".";
		}
	</script>
</head>
<body>
	<h1>Verificar Fases da Vida</h1>
	<label for="nome">Seu nome:</label>
	<input type="text" id="nome"><br>
	<label for="idade">Sua idade:</label>
	<input type="number" id="idade"><br>
	<button onclick="verificarFaseDaVida()">Verificar</button>
	<div id="resultado"></div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
	
css:
/* Custom CSS for the provided HTML code */
body {
    background-color: #f0f0f0; /* Light gray background */
    font-family: Arial, sans-serif;
    color: #333; /* Dark gray text color */
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0px;
    padding: 0;
    margin-top: 12px;
    border-right: 12px #0066cc;

  }
  
  h1 {
    margin-bottom: 20px;
    color: #004080; /* Navy blue header color */
  }
  
  label {
    margin-bottom: 5px;
    color: #006600; /* Dark green label color */
  }
  
  input {
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #bf1c1c; /* Light gray border */
    border-radius: 4px;
    outline: none;
  }
  
  button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    background-color: #0066cc; /* Blue button background color */
    color: #fff; /* White button text color */
    border: none;
    border-radius: 4px;
    outline: none;
    transition: background-color 0.2s ease-in-out;
  }
  
  button:hover {
    background-color: #004080; /* Darker blue button background color on hover */
  }
  
  #resultado {
    margin-top: 20px;
    font-size: 18px;
    font-weight: bold;
    text-align: center;
  }
  /* styles.css */

/* Reset default margin and padding for the body */
body {
	margin: 0;
	padding: 0;
}

/* Create a blue-colored bar */
.blue-bar {
	width: 100%;
	height: 50px;
	background-color: #007BFF; /* Blue color */
}

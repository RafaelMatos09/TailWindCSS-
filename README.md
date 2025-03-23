Solução de configuração:

npm install tailwindcss@latest postcss@latest autoprefixer@latest
npx tailwindcss init

apos ocorrer o erro, irá trocar as configurações do config.json


  "dependencies": {
    "autoprefixer": "^10.2.1",
    "postcss": "^8.2.4",
    "tailwindcss": "^2.0.2"
  }
}
Solucão:
	npm install -y
	npx tailwind -init
	
	apos gerar o arquivo config, irá reverter a instalação ...
		
	npm uninstall tailwindcss postcss autoprefixer
	npm install tailwindcss@latest postcss@latest autoprefixer@latest
	npx tailwindcss-cli@latest build -o src/css/build.css	


Exemplo de index: 

<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="/dist/styles.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>


Estrutura de pasta:

/projeto
  -> src
  -> css
	  -> styles.css
		-> build.css
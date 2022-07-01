Aula 1
	Oque o js faz? Ele pode fazer de tudo.
	
	Empreas que usam o JS
		Facebook
		Google
		Linkedin
		Netflix
		Dentre outras.	
	
	Conceito Client X Server
		Cliente: Dispositvo do usuario.
		Servidor: Banco de dados, onde está localizado o arquivo que um usuario quer.
		Navegador: Intermedia o Cliente e o Servidor.
		
	Conceito de Client Side
		HTML: Conteudo do site, como textos, vídeos e imagens.
		CSS: Para customizar o site, fazendo com que fique bonito.
		JS: Interação do usuario com o site.

Aula 2
	
	Evolução do JS
		1970-Surgimento da internet
		1993-Criação do HTML, do WWW, e do HTTP. Nascimento do mosaic.
		1994-Fundação do Netscape com base no mosaic.
		1995-Criação do CSS, JS. Lançamento do Internet Explorer, e Windowns 95.
		1997-Netscape sede JS para o ECMA.
		2002-Surgimento do Mozilla.
		2008-Surgimento do Google Chrome.
		2009-Surgimento do V8.
		2010-Criação do NODE.JS.

	Ecma script
		Versão padronizada do JS, tendo seu primeira lançamento em 1997 com a versão 1.0.
		Versão 2.0 em 1998.
		Versão 3.0 em 1999
		ES5 2009
		ES6 2015
		Após isso as atualizações passaram a ser feitas anualmente.

	Framewoks
		JQuerry
		Angular
		React
		Veu
		Electron

	Utilização nos jogos
		Phaser
		Pixi JS
		Impact
		Melon.js
		Craft.js

Aula 3

	Requisitos para o curso
		Conta github
		Utilizar o code pen
		Chrome

	Ambiente em casa
		Conta github
		Visual studio code
		Node.js

	Livros
		Java Script Guia Definitivo
		Java Script Guia do Programador
		Guia de referencia da Mozilla
		Guida de referencia da ecma

Aula 4-Inicio das práticas
	
	Códigos básicos
		Alert, gera uma mensagem com um botão de ok
		Confirm, gera uma janela com um botão de ok e cancel
		Prompt, gera uma pergunta que pode ser respondida

Módulo B-Expcativa: Aprender comandos básicos, como armazenar dados, tratamento e operações com dados

Aula 5
	
	Inicio
		Utilizar // para comentarios em uma linha, ou /* e */ para utilizar em mais de uma linha.
		Sinal de = não significa igual, e sim receber.
		Null significa nulo.
		Variavel é chamado de var

	Regras dos identificadores
		Podem começar com letras, $ ou _
		Não odem começar com números
		É possivel usar números
		É possivel usar acentos e simbolos
		Não podem ser palavras reservadas
		Não pode conter espaços

	Dicas
		Maisculas e minusculas são diferentes
		Utilizar nomes coerentes
		Evitar se tonar um programador alfabeto, ou um programador contador

	Data types
		number
			Infinity
			NaN
		string
		boolean
		null
		undefined
		object
			Array
		function

Aula 6

	Alguns comandos importantes
		window.alert('Uma mensagem do site para o usuário.')
		window.confirm('Gera uma janela com uma mensagem do site, e uma escolha para o usuário.')
		window.promtp('Gera uma caixa de diálogo para o usuario preencher com oque quiser, é importante lembrar que neste comando, os dados salvos são string como padrão.')
		document.write('Escreve no documento.')
		Para criar uma variavel deve-se utilizar o código:
			var nome_da_variavel = comando_em_seguida
		Para converter uma string para number de um prompt, pode se usar:
			Number.parseInt(window.promtp('Este não permite o uso de casas decimais.'))
			Number.Float(window.prompt('Este permite o uso de casas decimais.'))
			Number(window.prompt('Neste aqui o JS irá decidir qual usar.'))
		Para conver de number para string:
			String(n)
			n.toString()
		Em casos de colocar várias variaveis em uma mensagem pode usar o ${}, portando deve se usar a `` em vez das '' ou ""
				 Exemplo
				var n = João
				var ida = 15
				window.alert(`Seu nome é ${}, e sua idade é ${}.`)
				A mensagem deve ficar assim:
				Seu nome é João, e sua idade é 15.
		Formatando Strings
			s.length Este comando conta quantos letras tem sua string.
			s.toUpperCase() Deixa sua string com letras maisculas.
			s.toLowerCase() Deixa sua string com letras minusculas.

Aula 7

	Operadores focados no curso
		aritméticos-Usados para fazer contas, seus simbolos são: +, -, *, /, %, **.
		atribuições
		relacionais
		lógicos
		ternário
		É importante ressaltar que estes não são os unicos operadores em JS.

		Aritméticos
			+ Adição
			- Subtração
			* Multiplicação
			/ Divisão real 
			% Divisão Inteira 
			** Potencia
	Auto-atrubuições
		var n = 3 Utiliza uma variavel simples
		n = n + 4 Irá somar 4 ao valor da variavel, fazendo com que ela passe a valer 7.
		n = n - 5 Irá subtrair o valor da variavel, fazendo com ela passe a valer 2.
		n = n * 4 Irá multiplicar por quatro, fazendo com que a variavel passe a valer 8.
		n = n / 2 Irá dividir a variavel por 2, fazendo com que ela passe a valer 4.
		n = n ** 2 Irá elevar a varia ao quadrado, fazendo ela valer 16.
		n = n % 5 Irá fazer uma fração inteira fazendo que a variavel passe a valer 1.

			Forma simplificada
				Há também uma forma simplificada que o JS consegue entender, aqui estão os exemplos:
					n += 4
					n -= 5
					n *=4
					n /=2
					n **=2
					n %=2
		Incrementos
			Caso queira adicionar ou subtrair apenas o número 1, pode se usar:
				x++
				x--
			

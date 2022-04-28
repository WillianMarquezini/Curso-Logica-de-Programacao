# Curso de lógica da programação

## 1. Aula -- Porque um software é criado?
		
1.1 - Para criar soluções para problemas do dia a dia.
		
1.2 - Automação e otimização de processos.
			    
* Automatizar tarefas na web(interagir, preencher ou buscar informações em sites).
			    
* Automatizar criação, preenchimento, duplicação, e envio de arquivos(planilhas, docs, textos, pdf, imagens, etc...).

* Criação leitura e envio de e-mails.
			    
* Tarefas que use seu teclado e mouse.
			    
* Praticamente qualquer processo que é feito em um dispositivo pode ser automatizado parcial ou totalmente usando a programação.

## 2. Aula -- Ciclo de desencolvimento de Software
		  |
		Estágio 1 - Idealização.
		  |
		Estágio 2 - Especificação de Requisitos.
		  |
		Estágio 3 - Validação da Solução.	
		  |
		Estágio 4 - Desenvolvimento e Testes.
		  |
		Estágio 5 - Implantação e Entrega.

## Aula 3 -- O problema que todo iniciante enfrenta
		  |
		  Erro #1 - ir direto ao código.
		  Normal #1 - vai escrever código lentamente.
		  Normal #2 - Vai resolver os mesmos problemas em situações.
		  Normal #3 - Vai se achar incapaz/insuficiente. 
		  Normal #4 - Vai gradualmente conseguir solucionar problemas mais facilmente.

## Aula 4 -- Aprenda resolver problemas através da análise crítica
		|
		"Saber analisar e resolver um problema é mais importante que decorar os comando de uma linguagem de programação!"
		|
		"Quanto mais experiente se tornar, mais óbvio ficam os caminhos que levam a uma solução"
		|
		Problema #2 - Meu salário por hora
		Escreva um programa que retorne o valor hora de um funcionário com base no seu salário mensal e horas trabalhadas por mês.
		SálarioTOT / total de horas trabahadas

		Solução
		 Sálario mensal: 2500,00
		 horas trabalhadas: 176
		2500/176 = 14,60

## Aula 5 -- O que são algoritmos e como montar algoritimos do zero
		| 
		.1 O que são algoritimos?
		"Um algoritmo é simplesmente uma série de instruções a serem seguidas, para resolver um problema."
		|
		.2 Quando algoritimos devem ser criados?
		Sempre que queremos montar uma sequência de passos necessários para solucionar um problema.
		|
		.3 Qual é a estratégia para montar um algoritimo?
				Independente se:
			.3.1 Quando alguém te apresenta um problema a ser resolvido.
			|
			.3.2 Quando você encontra um problema a ser resolvido.
				
				Método 5Q's para montar um algoritimo:
				Analise criticamente o problema e descubra:
				(tente explicar este problema para você mesmo em voz alta e peça mais informações/investigue mais até você compreender completamente o problema.)
				
				1. Quais são os dados de entrada necessários?
				2. O que devo dazer com estes dado  s?
				3. Quais são as restrições deste problema?
				4. Qual é o resultado esperado?
				5. Qual a é a sequencia de passos a ser feitas para chegar ao resultado esperado?

		    Problema 1 - Ligar para alguém
			1. Quais são os dados de entrada necessários
				Um telefone
				Um numero de telefone
                
			2. O que devo fazer com estes dados?
				Usar o celular para discar o número do meu amigo

            3. Monte um algoritimo necessário para ligar para um amigo
                .1 Pegar o telefone
                .2 Se estiver travado por senha, destrave o celular
                .3 verifique se há sinal da operadora 
                .4 navegue até o discador do celular
                .5 digite o número do seu amigo 
                .6 aperte no motão de "Ligar"
                .7 aguardo a ligação completar
                .8 se a ligação completar, conversar com ele 
                .9 se a ligação não completar, deixar uma mensagem dizendo "me ligue de volta"
### Problema 2 - Valor por hora
4. Escreva um programa que retorna o valor hora de um funcinário com base no seu salário mensal e horas trabalhadas por mês.
    * perguntar quanto a pessoa ganha por mês 
    * guardar essa informação
    * perguntar quantas horas ele trabalha por mês 
    * guardar essa informação
    * calcular o valor hora da pessoa (salário mensal / horas trabalhadas)
    * exibir valor hora daquela pessoa

### Problema 3 - Chute o número 
3. 1. Quais são os dados de entrada necessários?

    #### Escreva um programa que, ao iniciar geraum valor aleatório de _1 a 10_ e permite que o usuário chute um numero até que o valor aleatório gerado no início do programa seja chutado corretamente.

    O programa deve informar se o chute foi **_acima, abaixo ou igual_** ao valor aleatório gerado.

    * um valor aleatório de 1 a 10
    * um chute do usuário
    
3. 2. O que devo fazer com estes dados

    * devo pegar o valor aleátorio de _1 a 10_ que foi gerado e comparar com o valor que foi chutado pelo usuário.

    * se o chute for maior ou menos que o valor gerado, alertar o usuário sobre isso e deixar jogar novamente até que acerte o numero que foi gerado.

3. 3. Restrições:

    * O Programa não deve ser finalizado até que um valor seja chutado corretamente.

    * O usuário deverá ser capaz de jogar quantas vezes quiser.

3. 4. resultado esperado:

    * O programa deve informar se o chute foi acima ou abaixo do valor aleatório no início do programa.
                                    

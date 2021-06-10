# My-first-repository
Meu repositório com projetos iniciais de aprendizagem
programa
{
	
	funcao inicio()
	{
		real janeiro,fevereiro,marco,abril,media
		cadeia funcionario

		escreva("Digite o nome do Funcionário: ")
		leia(funcionario)
		escreva("Digite o valor de vendas do mês de Janeiro: ") 
		leia(janeiro)
		escreva("Digite o valor de vendas do mês de Fevereiro: ")
		leia(fevereiro)
		escreva("Digite o valor de vendas do mês de Março: ") 
		leia(marco)
		escreva("Digite o valor de vendas do mês de Abril: ") 
		leia(abril)

		media = (janeiro + fevereiro + marco + abril)/4

		se (media >= 6000)
		escreva ("Parabéns!!" + funcionario + " você receberá um bônus de 10%")
		se (media <= 6000)
		escreva (funcionario + " sua bonificação será a de 3%")
		
		
	}
}

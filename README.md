# PE

/******************************************************************************

Elabore um programa que receba as fichas de até 10 pessoas, deverá
utilizar o conceito de Struct (Pessoa, Endereco, Veiculo), destacando que
Pessoa terá (Endereco e Veiculo).
 
Utilize #define para dimensionar a qtd de fichas.

Após ler as fichas, deverá retornar (nome, cep, veiculos (placas e
modelos)) do usuário mais novo e do usuário mais velho.

*******************************************************************************/

#include <stdio.h>

#define TAMAMANHO 100

		struct Endereco{
			char endereco[50], complemento[50], bairro[10], estado[10], cidade [20];
			int numero, cep;
		};
		
		
		struct Veiculo{
			char placa, modelo, cor;
			int ano;
		};
	
		struct Pessoa{
			char nome[50];
			int cpf, num_tel, num_tel, ddd_tel, num_cel, ddd_cel, ins_est, ins_mun, cnae, dataNas, email, boleto, telComer, contRespon, data, idade;
			struct endereco;
			struct veiculo;
			};

int main() {

		struct Pessoa pessoa1;
		estudante_diego.end.numero = 100;
		

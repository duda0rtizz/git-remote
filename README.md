# git-remote
Projeto conta bancaria 
package conta;

import java.util.Scanner;

public class Menu {

	public static void main(String[] args) {
	
		Scanner leia = new Scanner(System.in);
		
		int opcao;
		
		while (true) {
			
			System.out.println("***************************************************");
			System.out.println("                                                   ");
			System.out.println("                Banco do Brazil Com Z              ");
			System.out.println("                                                   ");
			System.out.println("***************************************************");
			System.out.println("                                                   ");
			System.out.println("             1 - Criar conta                       "); 
			System.out.println("             2 - Listar todas as Contas            ");
			System.out.println("             3 - Buscar Conta do Número            ");
			System.out.println("             4 - Atualizar dados da Conta          ");
			System.out.println("             5 - Apagar a Conta                    ");
			System.out.println("             6 - Sacar                             ");
			System.out.println("             7 - Depositar                         ");
			System.out.println("             8 - Tranferir valores entre Contas    ");
			System.out.println("             9 - Sair                              ");
			System.out.println("                                                   ");
			System.out.println("***************************************************");
			System.out.println("Entre com a opção desejada:                        ");
			System.out.println("                                                   ");
			
			opcao = leia.nextInt();
			if (opcao == 9) {
			   System.out.println("/nBanco do Brazil com Z - O seu Futuro começa aqui");
				sobre();
		leia.close();
				System.exit(0); 
			}
			
			switch (opcao) {
			case 1: 
				System.out.println("Criar conta/n/n");
				
				break;
			case 2: 
				System.out.println("Listar todas as contas/n/n");
				
				break;
			case 3: 
				System.out.println("Consultar dados da conta - por número/n/n");
				
				break;
				
			case 4:
				System.out.println("Atualizar dados da Conta - por números/n/n");
				
				break;
			case 5: 
				System.out.println("Apagar a Conta/n/n");
				
				break;
				
			case 6:
				System.out.println("Saquei/n/n");
				
				break;
				
			case 7:
				System.out.println("Depósito/n/n");
				
				break;
				
			case 8:
				System.out.println("Transferencia entre Conta/n/n");
				
				break;
				
			default:
				System.out.println("/nOpcao Inválida!/n");
				break;
			}
		}
   }
		public static void sobre() {
			System.out.println("/n******************************************");
			System.out.println("Projeto desenvolvido por: Layane Eduarda    ");
			System.out.println("Generation Brasil - layaneduarda129gmail.com");
			System.out.println("github.com/conteudoGeneration");
			System.out.println("*********************************************");

		}
	  }
			


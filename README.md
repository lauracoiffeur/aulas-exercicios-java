# aulas-exercicios-java
package contaBancaria;

import java.util.Scanner;

public class contaTerminal {

	public static void main(String[] args) {
		
	 try (Scanner scan = new Scanner(System.in)) {
		int numero = 0;
		String agencia = "";
		String nome = "" ;
		double saldo = 0;
		System.out.println("informe o número da conta:");
		numero = scan.nextInt();
		System.out.println("informe o nùmero da agencia:");
		agencia = scan.nextLine();		
		System.out.println("nome do cliente:");		
		nome = scan.nextLine();
		System.out.println("informe o saldo:");
		saldo = scan.nextDouble();			
		System.out.println("obrigado por criar sua conta em nossa agencia" + "sua conta É: " +   numero + " sua agência é:" + agencia + " seu nome é:" + nome + " e o seu saldo é:" + saldo);
	}
		}
		
       }

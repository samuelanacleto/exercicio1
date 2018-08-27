package aula20;

import java.util.Scanner;

public class exercicio1 {

	public static void main(String[] args) {
		
		float n1,n2,Média;
		Scanner  sc = new Scanner (System.in);
		System.out.print("Nota 1:");
		n1=sc.nextFloat();
		System.out.print("Nota 2:");
		n2=sc.nextFloat();
		Média =(n1*2+n2*3)/5;
		System.out.println("Média: "+Média);
		if (Média>=5)
			System.out.println("aprovado");
		else
			System.out.println("reprovado");
		sc.close();
		System.exit(0);
		

	}

package menu;

import java.util.Scanner;

public class Menu {
	public static void main(String[] args) {
	  Scanner scan = new Scanner(System.in);

		System.out.println("Informe a quntidade de palavras que serão inseridas:");

		int qtd = scan.nextInt();
 
		String plv[];
         
		 //aula
		
// aula
		// teste se está criando corretamente
/*
		String teste = "teste";

		for (int i = 0; i < qtd; i++) {

			plv[i] = teste;

			System.out.println(plv[i]);

		}
*/
		while (true) {

			System.out.println("/*--------------------*/");

			System.out.println("");

			System.out.println("a-Adicionar palavra");

			System.out.println("b-Alterar palavra");

			System.out.println("c-Excluir palavra");

			System.out.println("d-Listar palavra");

			System.out.println("e-Sair");

			System.out.println("");

			System.out.println("/*--------------------*/");

			System.out.println("selecione uma opcao:");

			char op;

			op = scan.next().charAt(0);

			op = Character.toLowerCase(op);

			switch (op) {

			case 'a':

			case 'b':
				alterarPalavra(plv,scan);
                break;
			case 'c':

			case 'd':

			case 'e':

				return;

			}

		}

	}
	
       public static void alterarPalavra(String[]plv,Scanner scan) {
    	   System.out.println("Qual palavra quer adicionar?");
    	   String plvUser=scan.next();
    	   int indice = verificarIdice(plv,plvUser);
    	   if (indice==-1) {
    		   System.out.println("Essa palavra nao existe!");
    		   return;
    	    
    	   }
    	   System.out.println("Qual a palavra que queira trocar ?");
    	   plv[indice]=scan.next();
    	   System.out.println("A palavra foi trocada!");
   }
        public static int verificarIdice(String[]plv,String plvUser) {
    	   for (int i=0;i<plv.length;i++) {
    		   if (plv[i]!=null && plv[i].equals(plvUser)){
    			   return i;
    		   
               }
          }
    	   return -1;
        }
     	
}
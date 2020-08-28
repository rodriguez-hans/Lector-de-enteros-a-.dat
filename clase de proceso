

import java.io.BufferedWriter;
import java.io.File;
import java.io.FileWriter;
import java.io.PrintWriter;
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public class PuntoDat {
	Scanner reader = new Scanner(System.in);
	File F;
	FileWriter W;
	BufferedWriter bw;
	PrintWriter wr;
	
	public void Archivo(String nombre) {

		
		List lista = new ArrayList();
		int numeros= 0;
		System.out.println("Ingrese numeros, detengase con -1");
		
		do {
		    numeros = reader.nextInt();
		    lista.add(numeros);
			
		    
		} while (numeros!=-1);
		
		String numerosos=lista.toString();
		
		
		
		try {
			

			
			F=new File(nombre);
			W=new FileWriter(F);
			bw=new BufferedWriter(W);
			wr= new PrintWriter(F);
			
			
			
			wr.write(numerosos);
			wr.close();
			bw.close();
			
			
		} catch (Exception e) {
			System.out.println("error");
		}
		
		
	}
	}


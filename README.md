package fundamentos.java;

public class Temperatura {
	
	public static void main(String[] args) {
		// (F - 32) x 5/9 = C
		
		final int X = 32;
		final double y = 5.0/9;
			
	        int F = 86;
	        double C = (F - X) * y;
	        System.out.println("O resultado é " + C + "°C");
	        
	        
	        
	        F = 77;
	        C = (F - X) * y;
	        System.out.println("O resultado é " + C + "°C");
	        
	       
		
			
		
	  
	}

}

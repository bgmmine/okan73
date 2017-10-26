public static void main(String[] args) {
		// TODO Auto-generated method stub
	  int n1, n2;
	  int eob = 1;
	  int number = 1;
	  Scanner input = new Scanner(System.in);
	  System.out.println("ilk sayiyi gir");
	  n1 = input.nextInt();
	  System.out.println("ikinci sayiyi gir");
	  n2 = input.nextInt();
	  
	  while(number < n1 && number < n2) {
	       if(n1 % number == 0 && n2 % number == 0) {
	    	  eob = number;
	    	  
	       }  
	       number++;
	  }
	  System.out.println("en buyuk ortak bolen=" + eob);
	  
	}

}

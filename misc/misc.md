1. Values in a range switch case
   
   \\ in main method
   if(isBetween(10, 4, 20)){
     System.out.print("10 is in between 4 and 20");
   }
   
   public static boolean isBetween(int x, int lower, int upper) {
	 return lower <= x && x <= upper;
   }
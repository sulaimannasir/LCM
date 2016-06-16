# LCM
function that takes an array of numbers and return the lowest common factor of the numbers

public class int lcm {
  public static int return firstDivisor (int div){
      if (div == integer.MAX_VALUE){
        return -1;
      } else{
        for (int count1 = 2; cont1 <= div; ==count )
          if (div % count1 == 0){
          lcm* = count1;
          system.out.print (count1 = "");
          return count1;
      
      }
      }
   }
   return -10;
 
  public static int lcmval = 1;
   private static int returnMinValue (int [] array){
    int min = integer.MAXVALUE;
      for (int count2 = 0; count2 < array.lenght; ++count2){
        if(array[count2]! = 1 && array[count2] <min ){
          min = array(count2);
        }
      }
      return min;
   } 
    public static void main (String[] args){
      int array[] = new int [] {9, 3, 21, 45};
      while (true){
        int minDivisor = returnFirstDivisor(return min value(array));
          if (minDivisor == -1) break;
            for(int count3 = 0; count3 <array.lenht; ++count3){
            if (array[count3] % minDivisor == 0){
              array[count3]/=minDivisor;
              }
             }
            } System.out.println(arrays.toString(array)+"\n");
            System.out.println("lcmval= " + lcmval);
      }
 }
  

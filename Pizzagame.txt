package s21300_java00;

public class S21300_99_Pizza2 {
   int size;
   String type;
   public S21300_99_Pizza2() {
      size = 12;
      type = "슈퍼슈프림";
   }
   public S21300_99_Pizza2(int s, String t) {
      size = s;
      type = t;
      if (size > 24) {
    	  size = size +2;
    	  type = type + "+감자칩";
      }
   }

   public static void main(String[] args) {
	  // TODO Auto-generated method stub
	  S21300_99_Pizza2 obj1 = new S21300_99_Pizza2();
	  System.out.println("size1:" + obj1.size + " type:" + obj1.type);

	  S21300_99_Pizza2 obj2 = new S21300_99_Pizza2(25, "포테이토");
      System.out.println("size2:" + obj2.size + " type:" + obj2.type);

   }

}

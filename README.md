- 👋 Hi, I’m Md. Sohanur Rahman jahin(sohan-99).
- 👀 I’m interested in Programing,web aplication & Problem solving.
-  I’m looking to collaborate on PUPC.
- 📫 How to reach me 
- sohan75632@gmail.com
<!---
sohan-99/sohan-99 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
public class StarPattern4 {
   public static void main(String[] args) {
      for (int i = 1; i <= 4; i++) {
         for (int j = 4; j >= i; j--) {
            System.out.print(" ");
         }
         for (int k = 1; k <= i; k++) {
            System.out.print("*");
         }
         System.out.println(); // Add this to move to the next line after each row
      }
   }
}

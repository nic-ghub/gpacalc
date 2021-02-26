# gpacalc
GPA Calculator



import java.util.Scanner;


public class GpaCalc {
    
public static void main(String[]args){

    String grade = "";
    double unit1;
    double unit2;
    double unit3;
    double unit4;
    double gradeScore = 0;
    double class1Score = 0;
    double class2Score = 0;
    double class3Score = 0;
    double class4Score = 0;
    double totalScore=0;
    double totalUnits=0;
    double gpa;
    
    Scanner gpaScanner = new Scanner(System.in);

    System.out.println("Welcome to GPA Calculator");
    
    
    System.out.println("Enter the amount of units from class one");
    
    unit1 = gpaScanner.nextDouble();
    
    System.out.println("Enter the letter grade for class one (Upper Case Letter)");
    
    grade = gpaScanner.next();
    
    if (grade.equals("A"))
    gradeScore = 4.00;
    else if (grade.equals("A-"))
    gradeScore = 3.67;
    else if (grade.equals("B+"))
    gradeScore = 3.33;
    else if (grade.equals("B"))
    gradeScore = 3.00;
    else if (grade.equals("B-"))
    gradeScore = 2.67;
    else if (grade.equals("C+"))
    gradeScore = 2.33;
    else if (grade.equals("C"))
    gradeScore = 2.00;
    else if (grade.equals("C-"))
    gradeScore = 1.67;
    else if (grade.equals("D+"))
    gradeScore = 1.33;
    else if (grade.equals("D"))
    gradeScore = 1.00;
    else if (grade.equals("D-"))
    gradeScore = 0.67;
    else if (grade.equals("F"))
    gradeScore = 0.00;
    else if (grade.equals("FX"))
    gradeScore = 0;
    
    else
        
    System.out.println("Invalid Grade");
    
    
    
    class1Score = gradeScore * unit1;
    
    //Class 2 input begins here
    System.out.println("Enter the amount of units from class two");
    unit2 = gpaScanner.nextDouble();
    System.out.println("Enter the letter grade for class two");
    grade = gpaScanner.next();
    
    if (grade.equals("A"))
    gradeScore = 4.00;
    else if (grade.equals("A-"))
    gradeScore = 3.67;
    else if (grade.equals("B+"))
    gradeScore = 3.33;
    else if (grade.equals("B"))
    gradeScore = 3.00;
    else if (grade.equals("B-"))
    gradeScore = 2.67;
    else if (grade.equals("C+"))
    gradeScore = 2.33;
    else if (grade.equals("C"))
    gradeScore = 2.00;
    else if (grade.equals("C-"))
    gradeScore = 1.67;
    else if (grade.equals("D+"))
    gradeScore = 1.33;
    else if (grade.equals("D"))
    gradeScore = 1.00;
    else if (grade.equals("D-"))
    gradeScore = 0.67;
    else if (grade.equals("F"))
    gradeScore = 0.00;
    else if (grade.equals("FX"))
    gradeScore = 0;
    
    else
        
    System.out.println("Invalid Grade");
    
    class2Score = gradeScore * unit2;
    
    //Class 3 input begins here
    System.out.println("Enter the amount of units from class three");
    unit3 = gpaScanner.nextDouble();
    System.out.println("Enter the letter grade for class three");
    grade = gpaScanner.next();
    
    if (grade.equals("A"))
    gradeScore = 4.00;
    else if (grade.equals("A-"))
    gradeScore = 3.67;
    else if (grade.equals("B+"))
    gradeScore = 3.33;
    else if (grade.equals("B"))
    gradeScore = 3.00;
    else if (grade.equals("B-"))
    gradeScore = 2.67;
    else if (grade.equals("C+"))
    gradeScore = 2.33;
    else if (grade.equals("C"))
    gradeScore = 2.00;
    else if (grade.equals("C-"))
    gradeScore = 1.67;
    else if (grade.equals("D+"))
    gradeScore = 1.33;
    else if (grade.equals("D"))
    gradeScore = 1.00;
    else if (grade.equals("D-"))
    gradeScore = 0.67;
    else if (grade.equals("F"))
    gradeScore = 0.00;
    else if (grade.equals("FX"))
    gradeScore = 0;
    
    else
        
    System.out.println("Invalid Grade");
    
    class3Score = gradeScore * unit3;
    
    //Class 4 input begins here
    System.out.println("Enter the amount of units from class four");
    unit4 = gpaScanner.nextDouble();
    System.out.println("Enter the letter grade for class four");
    grade = gpaScanner.next();
    
    if (grade.equals("A"))
    gradeScore = 4.00;
    else if (grade.equals("A-"))
    gradeScore = 3.67;
    else if (grade.equals("B+"))
    gradeScore = 3.33;
    else if (grade.equals("B"))
    gradeScore = 3.00;
    else if (grade.equals("B-"))
    gradeScore = 2.67;
    else if (grade.equals("C+"))
    gradeScore = 2.33;
    else if (grade.equals("C"))
    gradeScore = 2.00;
    else if (grade.equals("C-"))
    gradeScore = 1.67;
    else if (grade.equals("D+"))
    gradeScore = 1.33;
    else if (grade.equals("D"))
    gradeScore = 1.00;
    else if (grade.equals("D-"))
    gradeScore = 0.67;
    else if (grade.equals("F"))
    gradeScore = 0.00;
    else if (grade.equals("FX"))
    gradeScore = 0;
    
    else
        
    System.out.println("Invalid Grade");
    
    class4Score = gradeScore * unit4;
    
    
    
    
    
    totalScore = class1Score + class2Score + class3Score + class4Score;
    totalUnits = unit1+unit2+unit3+unit4;
    gpa = totalScore / totalUnits;
    
    System.out.printf("Congratulations, your GPA is: %.2f\n", + gpa);
    
    //System.out.println();
    //System.out.println("Would you like to increase your GPA?");
    
    
        while(gpa >=0){
        
        double newGpa = 0;
        
        System.out.println();
        System.out.println("Would you like to increase your GPA? 1 for Yes, 0 for No ");
        
        
       gpa = gpaScanner.nextDouble();
       gpaScanner.equals(0);
       
        
        
        if(gpa >=1)
        {
            
        newGpa = totalScore / 2;    
        System.out.println(newGpa);
            
            
            
        }
        else
                
        break;
        { 
         
         
    
        /* if(class1Score <=4.00)
         {
             class1Score++; 
             System.out.println(class1Score);
             
             
            // else if(class2Score >= 4.00)
             class2Score++;
             System.out.println(class2Score);
         //else if(class3Score >= 4.00)
             class3Score++;
             System.out.println(class3Score);
        // else if(class4Score >= 4.00)
             class4Score++;
             System.out.print(class4Score);
           
          
         }
        */
   
        
      
        
           
            
            }
            
    
        }
           
        
 

   }

}
    

    

    
   

        


    


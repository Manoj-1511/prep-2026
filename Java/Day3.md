<img width="861" height="1536" alt="Java Day 3 (6)" src="https://github.com/user-attachments/assets/a9422938-f243-46a3-952f-2f91624b9f7a" />
<img width="861" height="1536" alt="Java Day 3 (5)" src="https://github.com/user-attachments/assets/95c8daaf-b3fe-430e-8732-f5cc59fa00dc" />
<img width="861" height="1536" alt="Java Day 3 (4)" src="https://github.com/user-attachments/assets/aeb9bb02-2bab-4e6f-a18e-2bad550e088e" />
<img width="1536" height="861" alt="Java Day 3 (3)" src="https://github.com/user-attachments/assets/cb954b8b-f074-444e-a612-f32ea3e19869" />
<img width="1536" height="861" alt="Java Day 3 (2)" src="https://github.com/user-attachments/assets/7aa7b66a-24e1-4eb5-b3d2-1d51e659c393" />
<img width="1536" height="861" alt="Java Day 3 (1)" src="https://github.com/user-attachments/assets/ff4f5a2d-3abf-42ce-b2a7-833a7db3e8e7" />
#Sum of Two Numbers
class Main{
    public static int sum(int a,int b){
        return a+b;
        
    }
    public static void main(String args[]){
        System.out.println("Sum of Two Numberss is = "+sum(10,20));
        
    }
}
#Max of two numbers.
class Main{
    public static int findmax(int a,int b){
        if(a>b){
            return a;
        }
        else{
            return b;
        }
    }
    public static void main(String args[]){
        int a=30;
        int b=45;
        System.out.println("Maximum = "+findmax(a,b));
    }
}
#Even
class Main{
    public static boolean isEven(int a){
        if(a%2==0){
            return true;
        }
        else{
            return false;
        }
    }
    public static void main(String args[]){
        int a=44;
        System.out.println(isEven(a));
    }
}
#square of the  number.
class Main{
    public static int square(int n){
        return n*n;
    }
    public static void main(String args[]){
        int n=5;
        System.out.println(square(n));
    }
}
#Method overloading.
class Main{
    public static int area(int side){
        return side;
    }
    public static int area(int length,int breadth){
        return length*breadth;
    }
    public static void main(String args[]){
        int side=20;
        int length=3;
        int breadth=4;
        System.out.println(area(side));
        System.out.println(area(length,breadth));
    }
}
#factorial of a given number.
class Main{
    public static void fact(int n){
        int factorial=1;
        for(int i=1;i<=n;i++){
        factorial= factorial*i;
        }
        System.out.println( factorial);
    }
    public static void main(String args[]){
        int n=5;
        fact(n);
    }
}
#Multiplication of a table.
class Main{
    public static void table(int n){
        for(int i=1;i<11;i++){
            System.out.println(n + " x "+ i + " = "+(n*i));
        }
    }
    public static void main(String args[]){
        int n=6;
        table(n);
    }
}

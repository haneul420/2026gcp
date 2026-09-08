# 2026gcp
## homework1
```
public class Homework1{
  public static void homework1(String []args){
    int i, j;
    for(i=0; i<10; i++) {
      for(j=0; j<=i; j++) {
        System.out.print("#");
      }
      System.out.println("");
    }
  }
}
```

<img width="116" height="229" alt="Image" src="https://github.com/user-attachments/assets/59b9489f-2626-410e-aa08-824cc116ebf9" />

```
public class Homework1{
  public static void homework1(String []args){
    int i, j;
    for(i=0; i<10; i++) {
      for(j=0; j<10-i; j++) {
        System.out.print("#");
      }
      System.out.println("");
    }
  }
}
```

<img width="104" height="214" alt="Image" src="https://github.com/user-attachments/assets/1bb701a6-56c3-4acc-adea-ff76f036ebeb" />

```
public class Homework1{
  public static void homework1(String []args){
    int i, j;
    for(i=0; i<10; i++) {
      for(j=0; j<10-i; j++) {
        System.out.print(" ");
      }
        for (j=0; j<=i; j++) {
      System.out.print("#");
        }
        System.out.println();
    }
  }
}
```

<img width="141" height="239" alt="Image" src="https://github.com/user-attachments/assets/ca7c22e0-aa82-45ca-93db-675cc8e7153a" />

```
public class Homework1{
  public static void homework1(String []args){
    int i, j;
    for(i=0; i<10; i++) {
      for(j=0; j<i; j++) {
        System.out.print(" ");
      }
        for (j=0; j<10-i; j++) {
      System.out.print("#");
        }
        System.out.println();
    }
  }
}
```

<img width="120" height="227" alt="Image" src="https://github.com/user-attachments/assets/8370d7ea-1747-40b1-973e-2547f380b749" />

## homewrok2
```
public class Homework2 {
    public static void homework2(String[]args) {
        int[] fibonacci = new int[20];
        fibonacci[0] = 1;
        fibonacci[1] = 1;

        for (int i = 2; i < 20; i++) {
            fibonacci[i] = fibonacci[i - 1] + fibonacci[i - 2];
        }
        for (int i = 0; i < 20; i++) {
            System.out.print(fibonacci[i] + " ");
        }
    }
}
```

<img width="419" height="46" alt="Image" src="https://github.com/user-attachments/assets/eb304e99-b79c-4405-95c2-63663d103fda" />

## homework3
```
public class Homework3 {
  public static void homework3(String[] args) {
    int a = 1;
    int b = 1;
    for(int i = 1; i <= 20; i++) {
    int plus = a + b;
    
    System.out.printf("%d/%d = %.3f%n",plus,b , (double)plus/b);
    a = b;
    b = plus;
    }
  }
}
```
<img width="186" height="389" alt="Image" src="https://github.com/user-attachments/assets/637037ec-30bc-4f03-aeb5-b85660f17096" />

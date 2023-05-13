## Ex-2
## Java program to compare two numbers
### Aim:
To compare two numbers using java programming language.

### Procedure:
* Import required packages.
* Declare main method with the signature "public static void main(String[] args)".
* Get two numbers as input.
* Compare two numbers using else-if ladder.
* Dispaly the output accordingly.

### Code:
```
import java.util.Scanner;
public class Ex2 {
    public static void main(String[] args)
    {
        Scanner num = new Scanner(System.in);
        System.out.println("Enter two numbers:");
        int num1 = num.nextInt();
        int num2 = num.nextInt();
        if(num1 > num2)
        {
            System.out.println(num1 + " is greater than " + num2);
        }
        else if(num1 < num2)
        {
            System.out.println(num1 + " is less than " + num2);
        }
        else
        {
            System.out.println(num1 + " is equal to " + num2);
        }

    }
}
```

### Output:
<img width="143" alt="image" src="https://github.com/KeerthikaNagarajan/Java-Ex-2/assets/93427089/35ff9220-02bd-4913-b6b9-22a1a1fb22e1">
<img width="130" alt="image" src="https://github.com/KeerthikaNagarajan/Java-Ex-2/assets/93427089/2688009f-3108-4239-b38b-f9db29069349">
<img width="122" alt="image" src="https://github.com/KeerthikaNagarajan/Java-Ex-2/assets/93427089/d908f85f-fd9c-4a09-b338-f761e5aca6bf">

### Result:
To compare two numbers using java programming language was successfully done.

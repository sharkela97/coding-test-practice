## 현영의 코드
```java
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int A = sc.nextInt();
        int B = sc.nextInt();
        double div = (double)A/B;
        if (B != 0) 
            System.out.println(div);
        else
            System.out.println("출력할 수 없습니다.");
    }
}
```
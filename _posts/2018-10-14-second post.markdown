java
===========
###### (마크다운으로 작성)
java 변수
--------------
변수는 데이터를 담는 박스이다.여기에 담겨진 데이터는 다른 데이터로 바꿀 수 있고 변수는 영어에서 대명사와 비슷한 역할을 한다.
변수의 타입으로는
정수 int
실수 float, double
문자 char
문자열 String 등이 있다.
ex)

        int a = 10;
        double b = 3.14;
        String c = "안녕하세요 ";
        System.out.println(c);
        System.out.println("a x b = "+a*b);

결과)  안녕하세요
           a x b = 31.4;

java 출력
--------------
 java에서 출력을 하기 위해서는
 System.out.print();을 작성한 후에
 ()속에 출력하고 싶은 변수,문자를 넣어서 출력할 수 있다.
 (System.out.println();로 출력 후 줄을 나눌 수 있다.)
 ex)  

        int a;
        a = 10;
        System.out.println(a);
        System.out.prinln("안녕하세요 .");


 결과)
 10
 안녕하세요.


java 입력
------------
java에서 입력을 하기 위해서는
import java.util.Scanner;를 package아래 작성해야 사용할 수 있다.
int t;
Scanner scan = new Scanner(System.in);
t = scan.nextInt(); 이 형식으로
변수 t에 입력을 할 수 있다.
ex)   

        int t;
        System.out.print("t를 입력하세요 : ");
        Scanner scan = new Scanner(System.in);
        t = scan.nextInt();
        System.out.print("t는"+t+"입니다.");

결과)
##### t를 입력하세요: 5(5를 입력)
##### t는 5입니다.

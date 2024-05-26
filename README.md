# C_practice8_REVIEW
## 2024/05/26 : 포인터

#### 배열의 0번째 = 986호
#### arr[0] = 20;
#### 986호 = 20;
#### -> 포인터
---------
    #define _CRT_SECURE_NO_WARNINGS
    #include <stdio.h>
    int main() {
    	int a;
    	int *ap;
    	ap = &a;
    	*ap = 20;
    	printf("%d\n", a);
    }
#### *a : a 안으로
#### &a : a의 주소
#### int main 함수 만들기
#### 정수형 변수 a를 만들기
#### 정수형 포인터 변수 ap 만들기
---------
### scanf
---------
### str/arr
---------
## call by reference VS call by value
---------
    #define _CRT_SECURE_NO_WARNINGS
    #include <stdio.h>
    int main() {
        int a = 0;
        int b = 0;
        int temp = 0;
    
        scanf("%d%d", &a, &b);
    
        temp = a;
        a = b;
        b = temp;
        printf("%d %d", a, b);
    }

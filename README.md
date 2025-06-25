    #include <stdio.h>
    
    int main(void){
    int a, b, c;
    printf("Digite um número: ");
    scanf("%d", &a);
    printf("Digite outro número: ");
    scanf("%d", &b);
    printf("Digite um ultimo número: ");
    scanf("%d", &c);
    
    if (a>b && a>c){
    printf("O maior número é %d", a);
    } if (b>a && b>c){
    printf("O maior número é %d", b);
    } if (c>b && c>a){
    printf("O maior número é %d", c);
    }  if (a==b && a==c && b==c){
    printf("Os números são iguais");
    }
    }

# ATV 5

    #include <stdio.h>

    int main(void) {
    int num;
    printf("Digite um ano: ");
    scanf("%d", &num);
    if (num % 4 == 0 && num % 100 != 0 || num % 400 == 0) {
    printf("esse ano é bissexto\n");
    }else {
    printf("esse ano não é bissexto\n");
    }
    }

# ATV 25 

    #include <stdio.h>

    int main(void) {
    int a;
    printf("me fale uma temperatura: ");
    scanf("%d", &a);
    int b = 5/9 * (a - 32);

    printf("essa temperatura em celsius é: %d\n", b);
    }

# ATV 4

    #include <stdio.h>

    int main() {
    int num1, num2, num3, num4, num5, num6, soma;

    printf("Digite seis numeros inteiros: ");
    scanf("%d %d %d %d %d %d", &num1, &num2, &num3, &num4, &num5, &num6);
 
    soma = num1 + num2 + num3 + num4 + num5 + num6;

    printf("Aqui esta a soma dos seis numeros inteiros: %d\n", soma);
    }



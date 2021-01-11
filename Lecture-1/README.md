Com C, se recebemos dois inteiros e queremos dividir para pegar um valor quebrado (float) nós temos que ou que mudar o tipo dos números que estamos recebendo ou falar que no momento da divisão queremos transformá-los para float.

```c
#include <cs50.h>
#include <stdio.h>

int main (void)
{
	int x = get_int("value of x: ");
	int y = get_int("value of y: ");

	float z = (float) x / (float) y;
	printf("%f\n", z);
}
```

Para assignment, podemos:

```c
counter = 0

counter = counter + 1;
counter += 1;
counter++;
```

Quando estamos verificando apenas um character colocamos ele em single quotes ' '.
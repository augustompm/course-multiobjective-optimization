# course-multiobjective-optimization

Guia de como usar o Google Colab para desenvolver C++:

1) Criar um novo notebook em https://colab.research.google.com/

2) No menu, vá até "Runtime" > "Change runtime type" e selecione "T4 GPU" como acelerador de hardware.

3) Na primeira célula execute: ``` !pip install git+https://github.com/andreinechaev/nvcc4jupyter.git ```

4) Crie nova célula abaixo e execute: ``` %load_ext nvcc4jupyter ```

5) Teste o Hello World:
```cpp
%%cu
//Olá mundo imprimindo de 1 até 10
#include <iostream>
int main() {
    for (int i = 1; i <= 10; ++i) {
        std::cout << i << " ";
    }
    std::cout << std::endl;
    return 0;
}
```
6) Mundo precisa de mais programadores C++. :) 

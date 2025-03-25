int x = 5;

x <<= 2;

 Qual o valor final de x? 

 <table>
        <thead>
            <tr>
                <th>Potência</th>
                <th>2<sup>2</sup></th>
                <th>2<sup>1</sup></th>
                <th>2<sup>0</sup></th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Posição</td>
                <td>2</td>
                <td>1</td>
                <td>0</td>
            </tr>
            <tr>
                <td>Resultado</td>
                <td>4</td>
                <td>2</td>
                <td>1</td>
            </tr>
            <tr>
                <td>Binário</td>
                <td>1</td>
                <td>0</td>
                <td>1</td>
            </tr>
        </tbody>
    </table>

    
Em binário o número 5 é ---> 1 0 1

Para achar o valor de x, como o símbolo é deslocamento à esquerda ( << = ) então desloca os bits da variável para a esquerda:

0000 0101   (5 em binário, considerando 8 bits)

x << 2 → multiplica por 2² = 4

Número inicial (x = 5): 0000 0101  (5 em binário)

Deslocando 1 bit para a esquerda (x << 1): 0000 1010  (10 em binário)

Deslocando mais 1 bit para a esquerda (x << 2): 0001 0100  (20 em binário)

int x = 5;
x <<= 2;  ---> Agora x vale 20


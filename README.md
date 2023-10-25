# Teste de PSI Modelo

## Informação do aluno

    Nome: ...

Teste termina às 09:40 (Turno 1) / 13:25 (Turno 2).

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### 1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    char c = '\u00AE';
    Console.WriteLine($@"\n{c}\n");

P1 - Resposta
    
    \n®\n
pq esta apresentando um unicode e o writeline le esses codigo e o resultado é esse
### 2. Considera o seguinte código

    double d = 0.3513;
    float f = 12.645;

    Console.WriteLine($"{d} + {f} = {d + f}");

### Indica a correção necessária para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    double d = 0.3513;
    float f = 12.645F;

    Console.WriteLine($"{d} + {f} = {d + f}");
   tem que se colocar um F no final da varivel do float

### 3. Escreve um programa que solicite uma string ao utilizador, e seguidamente a mostre no ecrã de forma invertida

P3 - Resposta

    

### 4. Quais são os comandos Git para configurares, de uma forma global, o teu **nome** e **email** para realização de *commits*? E se essa configuração for apenas para um repositório?

P4 - Resposta

    git config --global user.name “Nome Apelido”
git config --global user.email “nome.apelido@gmail.com”

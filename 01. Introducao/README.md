# Configurações 

## Compilador C# - Windows
No windows já vem instalado por padrão o framework Microsoft.NET. Podemos acessá-lo na pasta: *C:\Windows\Microsoft.NET\Framework64\v4.0.30319*  
Dentro dessa pasta existe o arquivo: **csc.exe**

### Colocando o compilador no *path* do sistema
Digitar no terminal: `csc`.   
Caso a resposta seja: *'csc is not recognized as internal or external command...'* significa que o compilador não está no *path* do sistema. Para configurar basta:  
01. Copiar o caminho: **C:\Windows\Microsoft.NET\Framework64\v4.0.30319**
02. No windows, procurar por: editar variáveis de ambiente
03. Na aba avançado, clicar em variáveis de ambiente
04. Em variáveis do sistema, clicar em **Path** e no botão editar
05. Clicar em novo e inserir o caminho
06. Abrir o terminal e digitar: `csc`.

## Plugins para o VSCode
* C#

## Olá mundo
Na primeira linha é importado System `using System`   
Como C# é uma linguagem orientada a objeto, tudo é feito em classes.   
Iniciamos criando a classe **Principal** que conterá o método **Main**. Este método é carregado quando a aplicação inicia.   
o Método Main contém as instruções:   
```cs
    static void Main() {
        Console.Write("Olá mundo..."); //olá mundo no console
        Console.ReadLine(); //pausa a aplicação
    }
```

### Compilando
Para compialar basta digitar no terminal: `csc aula01.cs`   
Após compilar será gerado o arquivo aula01.exe

### MicroCode-Like Language
uma evolução leve do Assembly
focado em manter um pouco da baixa abstração, mas também oferecer suporte em funcionalidades extras

### Guía Rápido
cada arquivo escrito tem que ter a extensão ```.mclss``` que significa **MicroCode-Like Source Script**

### Sintaxe
o código deve ser escrito parecido com isso(para a arquitetura x86):
```MicroCode-Like Source Script
/* Isso Aqui é um Comentário */

// Função Principal
FUNC _START [] DO
    HALT [0b00]; // Código de Saída 0, ou Seja, Funcionou
END

OVERRIDE VAR START:_START = _START []; // Nova Instância de _START
```

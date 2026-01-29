DOCUMENTAÇÃO DA LINGUAGEM .cof
📌 Visão Geral
.cof é uma linguagem interpretada simples, educacional, com sintaxe em português, ideal para aprender lógica de programação.

🖨️ Saída de texto
show text("Olá mundo")


📦 Variáveis
String
vari nome: "Lucas"

Número
vari idade: 20
vari altura: 1.75

Input do usuário
vari nome: input("Digite seu nome: ")

Operações matemáticas
vari x: 5
vari x: x + 1
vari y: x * 2


🔀 Condicionais
Igualdade
if nome == "Lucas":
    show text("Bem-vindo")
endif

Operadores suportados
Operador
Significado
==
igual
!=
diferente
>
maior
<
menor
>=
maior ou igual
<=
menor ou igual

If / Else
if idade >= 18:
    show text("Maior de idade")
else:
    show text("Menor de idade")
endif


🔁 Loops
Loop FOR
loop for(3):
    show text("Executando")
endloop

Loop WHILE
vari contador: 0

while contador < 3:
    show text("Loop while")
    vari contador: contador + 1
endwhile


🧩 Funções
Definição
func saudacao():
    show text("Olá!")
endfunc

Chamada
call saudacao()


💬 Comentários
# Isso é um comentário


🧪 Exemplo Completo
show text("Início")

vari nome: input("Nome: ")
vari idade: 22

if idade >= 18:
    show text("Adulto")
else:
    show text("Menor")
endif

loop for(2):
    show text("Rodando")
endloop

show text("Fim")

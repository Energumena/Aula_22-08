# Aula_22-08
---
# Código VSCode
### Usar código por meio do modo edição!!

Para -> Laço de repetição
 Para iniciador, limitador, acrescentador {
  }
-----------------------------------------------------------------
programa {
  funcao inicio() {
    inteiro numero, contador, resultado

    escreva("Informe o número: ")
    leia(numero)
    para(contador=1;contador <=10 ;contador++) {
        resultado = numero * contador
        escreva (numero, " x ", contador, " = ",resultado,"\n")
  }
}

-------------------------------------------------------------------
programa {
  funcao inicio() {
    inteiro agatha

    para(agatha=100;agatha >=0;agatha--) {
        escreva (agatha, "\n")
  }
    escreva("Acabou!!")
}

-------------------------------------------------------------------
programa {
  inclua biblioteca Util

  funcao inicio() {
    inteiro agatha

    para(agatha=60;agatha >=0;agatha--) {
        escreva (agatha, "\n")
        Util.aguarde(1000)
  }     
}
-------------------------------------------------------------------
programa {
  funcao inicio() {
    inteiro soma = 0, numero, agatha
    
    escreva("Digite o número até o qual deseja somar: ")
    leia(numero)
    para (agatha = 0; agatha <= numero; agatha ++)
    {
        soma = soma + agatha
    }
    escreva ("A soma de 1 até ", numero, " é: ", soma,"\n")

  }
}

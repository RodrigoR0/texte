# trabalhoDoMailsonALG
 trabalho do mailson
 
Nome:Rodrigo Ribeiro Silva
Nome:Gilberto Navarro Junior


algoritmo "decimalXbinario"
var
   RST:Caractere
   VLF,VL,i,j:Inteiro
   cd,cb,ES:logico


   
   

inicio
      Escreva("Digite (cd) para conversão em decimal ou (cb) binaria?")
      Leia(ES)
      Se (ES=cd) entao
         Escreva("Informe o valor que quer converter:")
         Leia(VL)
         VLF<-VL
         Enquanto VL > 0  faca
                  Se (VL mod 2)=0 entao
                     RST<- "0" +RST
                  senao
                     RST<-"1"+RST
                  FimSe
                  VL<-VL div 2
         FimEnquanto
         EscrevaL(VLF,"=", RST)
         Senao
              (ES=cb) entao
            Para i de 6 ate 0 passo -1 faca
                 Escreva("Informe o valor para converter")
                 Leia(VL)
               Se (VL)=1 entao
                 RST<-1
                 Para j de 0 ate i faca
                      RST<-exp 2
                 FimPara
                 VLF<-VLF+RST
               FimSe
            FimPara
            EscrevaL(VL,"=",VLF)
         FimSe
fimalgoritmo

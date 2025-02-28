#include <stdio.h>
  
    //Uso do int para números inteiros
    //Uso do char para caracteres
    //Uso do float para números reais

int main (){
    char nome1[50], nome2[50]; //uso do char para caracteres
    char estado1[3], estado2[3]; //uso do char para caracteres
    int populacao1, populacao2; //uso do int para números inteiros
    float PIB1, PIB2, area1, area2; //uso do float para números decimais
    int pontos_turisticos1, pontos_turisticos2; //uso do int para números inteiros

      //entrada de dados da primeira cidade
    printf("\nDigite o nome da primeira cidade: ");
      scanf("%[^\n]", nome1);
    printf("Digite o estado (Ex: PR, SP, RJ): ");
      scanf("%s", estado1);
    printf("Digite a população: ");
      scanf("%d", &populacao1);
    printf("Digite o PIB: "); //em Bilhões
      scanf("%f", &PIB1);
    printf("Digite a área: "); //em km²
      scanf("%f", &area1);
    printf("Digite a quantidade de pontos turísticos: ");
      scanf("%d", &pontos_turisticos1);
        
    //limpeza do buffer para efetuar a leitura da segunda cidade
        getchar();
    
      //entrada de dados da segunda cidade
    printf("\nDigite o nome da segunda cidade: ");
      scanf("%[^\n]", nome2);
    printf("Digite o estado (Ex: PR, SP, RJ): ");
      scanf("%s", estado2);
    printf("Digite a população: ");
      scanf("%d", &populacao2);
    printf("Digite o PIB: ");
      scanf("%f", &PIB2);
    printf("Digite a área: ");
      scanf("%f", &area2);
    printf("Digite a quantidade de pontos turísticos: ");
      scanf("%d", &pontos_turisticos2);
    return 0;
    }
   
  

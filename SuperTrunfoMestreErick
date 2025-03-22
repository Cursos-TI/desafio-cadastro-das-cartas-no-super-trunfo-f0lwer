#include <stdio.h>

int main(void) {
    // dados da primeira carta //
    char Estado1[100], Estado2[100];
    char CodigodaCarta1[20], CodigodaCarta2[20];
    char Nomedacidade1[20], NomedaCidade2[20];
    int populacao1, populacao2;
    double areaEmKm21, areaemkm22;
    double pib1, pib2; 
    int PontosTuristicos1, p_turisticos2;

    // infomações da primeira carta //
    printf("----------------Carta1----------------\n");

    printf("Digite o Estado(de A a H): "); // Estado brasileiro
    scanf("%99s", Estado1);

    printf("Digite o codigo da carta(Estado + de 01 a 04): "); // Um valor de alphanumerico
    scanf("%99s", CodigodaCarta1);

    printf("Digite o nome da cidade: ");
    scanf("%99s", Nomedacidade1);

    printf("Populacao: "); // população inteira
    scanf("%d", &populacao1);

    printf("Area: "); // Em km2
    scanf("%lf", &areaEmKm21);

    printf("Valor de piB: "); // Valor de produto interno bruto da cidade
    scanf("%lf", &pib1);

    printf("Pontos Turisticos: "); // valor pode ser ficticio ou nao
    scanf("%d", &PontosTuristicos1);
    
    // Informações da segunda carta

    printf("----------------Carta2----------------\n");

    printf("Digite o Estado(de A a H): ");
    scanf("%99s", Estado2);

    printf("Digite o codigo da carta(Estado + 01 a 04): ");
    scanf("%99s", CodigodaCarta2);

    printf("Digite o nome da cidade: ");
    scanf("%99s", NomedaCidade2);

    printf("Populacao: ");
    scanf("%d", &populacao2);

    printf("Area: ");
    scanf("%lf", &areaemkm22);
    
    printf("Valor de piB: ");
    scanf("%lf", &pib2);

    printf("Pontos Turisticos: ");
    scanf("%d", &p_turisticos2);

    double pibpercapital1 = pib1 / populacao1; 
    double pibpercapital2 = pib2 / populacao2;
    double densidadepopulacional1 = populacao1 / areaEmKm21; 
    double densidadepopulacional2 = populacao2 / areaemkm22;
    float poder1 = populacao1 + areaEmKm21 + pib1 + PontosTuristicos1 + pibpercapital1 + (1 / densidadepopulacional1);
    float poder2 = populacao2 + areaemkm22 + pib2 +p_turisticos2 + pibpercapital2 + (1 / densidadepopulacional2);
    // Mostruario de informações da primeira carta
    printf("-----------Mostruario da primeira Carta-----------\n");

    printf("Estado: %s\n", Estado1);
    printf("Codigo da carta: %s\n", CodigodaCarta1);
    printf("Nome da cidade: %s\n", Nomedacidade1);
    printf("Populacao: %d\n", populacao1);
    printf("Area: %.2lf km2\n", areaEmKm21);
    printf("Valor de PiB: %.2f\n", pib1);
    printf("Pontos turisticos: %d\n", PontosTuristicos1);
    printf("Pib per capital: %.2lf reais\n", pibpercapital1);
    printf("Densidade populacional: %.2lf hab/km2\n", densidadepopulacional1);
    printf("Super poder: %.2f\n", poder1);

    // Mostruario de informações da segunda carta

    printf("-----------Mostruario da segunda Carta-----------\n");

    printf("Estado: %s\n", Estado2);
    printf("Codigo da carta: %s\n", CodigodaCarta2);
    printf("Nome da cidade: %s\n", NomedaCidade2);
    printf("Populacao: %d\n", populacao2);
    printf("Area: %.2f km2\n", areaemkm22);
    printf("Valor de PiB: %.2f\n", pib2);
    printf("Pontos Turisticos: %d\n", p_turisticos2);
    printf("Pib per capital: %.2lf reais\n", pibpercapital2);
    printf("Densidade populacional: %.2lf hab/km2\n", densidadepopulacional2);
    printf("Super poder: %.2f\n", poder2);

    printf("-----------Resultados-de-comparacoes-entre-as-cartas-----------\n");
    printf("Sendo: 1 para a Carta 1 como vencedora\n");
    printf("Sendo: 0 para a Carta 2 como vencedora\n");

    printf("Populacao: %i\n", (populacao1 > populacao2));
    printf("Area: %d\n", (areaEmKm21 > areaemkm22));
    printf("PIB: %d\n", (pib1 > pib2));
    printf("Pontos turisticos: %d\n", (PontosTuristicos1 > p_turisticos2));
    printf("Densidade populacional: %d\n", (densidadepopulacional1 < densidadepopulacional2));
    printf("PIB per capital: %d\n", (pibpercapital1 > pibpercapital2));
    printf("Super poder: %d", (poder1 > poder2));

    return 0;

}

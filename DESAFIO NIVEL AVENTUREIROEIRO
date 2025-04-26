#include <stdio.h>

int main() {
    
    char estado1[40], nomeCidade1[40];
    int codigo1, populacao1, pontosTuristicos1;
    float area1, pib1;
    float densidade1, pibPerCapita1;

    char estado2[40], nomeCidade2[40];
    int codigo2, populacao2, pontosTuristicos2;
    float area2, pib2;
    float densidade2, pibPerCapita2;

    printf("Digite o estado da primeira cidade: ");
    scanf("%s", estado1);
    printf("Digite o código da primeira cidade: ");
    scanf("%d", &codigo1);
    printf("Digite o nome da primeira cidade: ");
    scanf("%s", nomeCidade1);
    printf("Digite a área da primeira cidade (em km²): ");
    scanf("%f", &area1);
    printf("Digite a população da primeira cidade: ");
    scanf("%d", &populacao1);
    printf("Digite o PIB da primeira cidade: ");
    scanf("%f", &pib1);
    printf("Digite o número de pontos turísticos da primeira cidade: ");
    scanf("%d", &pontosTuristicos1);

    // Cálculo da densidade populacional e PIB per capita da primeira cidade
    densidade1 = populacao1 / area1;
    pibPerCapita1 = pib1 / populacao1;

    printf("\nDigite o estado da segunda cidade: ");
    scanf("%s", estado2);
    printf("Digite o código da segunda cidade: ");
    scanf("%d", &codigo2);
    printf("Digite o nome da segunda cidade: ");
    scanf("%s", nomeCidade2);
    printf("Digite a área da segunda cidade (em km²): ");
    scanf("%f", &area2);
    printf("Digite a população da segunda cidade: ");
    scanf("%d", &populacao2);
    printf("Digite o PIB da segunda cidade: ");
    scanf("%f", &pib2);
    printf("Digite o número de pontos turísticos da segunda cidade: ");
    scanf("%d", &pontosTuristicos2);

    // Cálculo da densidade populacional e PIB per capita da segunda cidade
    densidade2 = populacao2 / area2;
    pibPerCapita2 = pib2 / populacao2;

    printf("\n--- Primeira Cidade ---\n");
    printf("Estado: %s\n", estado1);
    printf("Código: %d\n", codigo1);
    printf("Nome: %s\n", nomeCidade1);
    printf("Área: %.2f km²\n", area1);
    printf("População: %d\n", populacao1);
    printf("PIB: %.2f\n", pib1);
    printf("Pontos Turísticos: %d\n", pontosTuristicos1);
    printf("Densidade Populacional: %.2f hab/km²\n", densidade1);
    printf("PIB per Capita: %.2f\n", pibPerCapita1);

    printf("\n--- Segunda Cidade ---\n");
    printf("Estado: %s\n", estado2);
    printf("Código: %d\n", codigo2);
    printf("Nome: %s\n", nomeCidade2);
    printf("Área: %.2f km²\n", area2);
    printf("População: %d\n", populacao2);
    printf("PIB: %.2f\n", pib2);
    printf("Pontos Turísticos: %d\n", pontosTuristicos2);
    printf("Densidade Populacional: %.2f hab/km²\n", densidade2);
    printf("PIB per Capita: %.2f\n", pibPerCapita2);

    return 0;
}

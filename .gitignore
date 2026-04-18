#include <stdio.h>
#include <stdlib.h>
#include <locale.h>
#include <time.h>

int main()
{  
    setlocale(LC_ALL, "Portuguese");
    int jogador,computador;
    int jogarnovamente;
    
    do {
    
    printf("__________joquenpo__________\n");
    printf("\t1. PEDRA\n");
    printf("\t2. PAPEL\n");
    printf("\t3. TESOURA\n");
    
    printf("___________________________");
    printf("\nDigite a opção desejada: ");
    scanf("%d", &jogador);
    printf("\n");
    
    switch(jogador){
        
        case 1:
            printf("Jogador escolheu PEDRA\n");
        break;
        case 2:
            printf("Jogador escolheu PAPEL\n");
        break;
        case 3:
            printf("Jogador escolheu TESOURA\n");
        break;
    }
    
            //LOGICA DO COMPUTADOR
        
        srand(time(NULL));//chama a função rand
        
            //rand distriuindo valores aleatorios somente com a Blilioteca time
        
        computador = ("%d",rand()%3+1);// 3 valores aleatorios
        
        switch(computador){
            
            case 1:
                printf("Computador escolheu PEDRA");
            break;
            case 2:
                printf("Computador escolheu PAPEL");
            break;
            case 3:
                printf("Computador escolheu TESOURA");
            break;
        }
        
             //ANALISE DO JOGO
        
        if(jogador == computador){
        
            printf("\n\tEMPATE!\n");
        
        }
        else if((jogador == 1 && computador == 3) ||
                (jogador == 2 && computador == 1) ||
                (jogador == 3 && computador == 2)){
                    
            printf("\n\tJOGADOR VENCEU!\n");
        }
        else{
            printf("\n\tCOMPUTADOR VENCEU!\n");
        }
        
        printf("\n\n");
        
        printf("\n============================\n");
        printf("DESEJA JOGAR NOVAMENTE? [1]SIM [0]NÃO\n");
        scanf("%d", &jogarnovamente);
        printf("==============================\n\n");
        
    }while(jogarnovamente == 1);       
    
    printf("obrigado por jogar.-.");
    
    
    return 0;
}

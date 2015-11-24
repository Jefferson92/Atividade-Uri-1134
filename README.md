# Atividade-Uri-1134

 int n1,alcool=0,gasolina=0,diesel=0;

    do{//faz com que o usuario digite varios numeros, quando o usuario quiser a contagem do combustivel ele aperta o 4.
        scanf("%d",&n1);
             if(n1==1)//contagem do alcool
			 {
			  alcool++;
			 }
        else if(n1==2)//contagem da gasolina
			{
			gasolina++;
			}
        else if(n1==3)//contagem do diesel
			{
			diesel++;
			}
    }while(n1!=4);

     printf("MUITO OBRIGADO\n");
     printf("Alcool: %d\n",alcool);
     printf("Gasolina: %d\n",gasolina);
     printf("Diesel: %d\n",diesel);
 
    return 0;
}

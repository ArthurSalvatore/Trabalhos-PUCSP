# Trabalhos-PUCSP
//trabalho para calcular quantos dias se passaram desdo inicio do ano, usando  switch. 
//informações adicionais-nao possue proteção de dados nos dias, ent cuidado com os valores inseridos
int main()
{
    int jan = 31, fev = 0, mar = 31, abr = 30, maio = 31,jun = 30, jul = 31, agost = 31, set = 30, out = 31, nov =30, dez = 31 ;
    int dia, mes, ano, diat;
  printf("vamos calcular a quantidade de dias de uma data até agora\n");
  printf("assim me diga uma data\n");
    scanf("%d %d %d", &dia, &mes, &ano);
    if((ano%4==0)&&(ano%100!=0) || (ano%400==0))fev=29; // ano bissexto e fev tem 29 dias
  else fev=28;
switch (mes)
{
case 1 :
diat = dia; 
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
    break;
    case 2 :
diat = jan + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
 case 3 :
diat = jan + fev + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
 case 4 :
diat = jan + fev+ mar + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
case 5 :
diat = jan + fev+ mar + abr + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
case 6 :
diat = jan + fev+ mar + abr + maio + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
case 7 :
diat = jan + fev+ mar + abr + maio + jun + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
case 8 :
diat = jan + fev+ mar + abr + maio + jun+ jul + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
case 9 :
diat = jan + fev+ mar + abr + maio + jun+ jul+ agost + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
case 10 :
diat = jan + fev+ mar + abr + maio + jun+ jul+ agost + set + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
case 11 :
diat = jan + fev+ mar + abr + maio + jun+ jul+ agost + set+ out + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
case 12 :
diat = jan + fev+ mar + abr + maio + jun+ jul+ agost + set+ out + nov + dia;
printf("Até a data %d / %d / %d transcorreu, durante o ano em curso, a quantidade %d de dias.", dia, mes, ano, diat);
break;
default:
printf("erro erro erro erro erro erro, escreva um valor correto)");
  break;
}
printf("fim");
return 0;
 }

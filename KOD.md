/* Furkan Metin OĞUZ tarafından yapılmıştır */
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
{
    int x,say;
   int toplam_1_sayisi=0;
   int toplam_2_sayisi=0;
   int toplam_3_sayisi=0;
   int toplam_4_sayisi=0;
   int toplam_5_sayisi=0;
   int toplam_6_sayisi=0;
    for(x=1;x<=100000;x++)
    {

    say=1+rand()%6;
    switch(say)
    {
        case 1: toplam_1_sayisi++;break;
        case 2: toplam_2_sayisi++;break;
        case 3: toplam_3_sayisi++;break;
        case 4: toplam_4_sayisi++;break;
        case 5: toplam_5_sayisi++;break;
        case 6: toplam_6_sayisi++;break;
    }
    }
    printf("sayı/tolasılık\n");
    printf("-----------------------------------------\n");
    printf("1\t%.2f\n",toplam_1_sayisi/1000.0);
        printf("2\t%.2f\n",toplam_2_sayisi/1000.0);
            printf("3\t%.2f\n",toplam_3_sayisi/1000.0);
                printf("4\t%.2f\n",toplam_4_sayisi/1000.0);
                    printf("5\t%.2f\n",toplam_5_sayisi/1000.0);
                        printf("6\t%.2f\n",toplam_6_sayisi/1000.0);
    return 0;
}

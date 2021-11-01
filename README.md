#include <stdio.h> #include <stdlib.h>

int main (){

system ("color A"); int menu,pilihan,penjelasan,sulit;

float BTC,ETH,BNB,ADA,USDT,IDR,XRP,SOL,DOT,DOGE,SHIB,USD; while (1){

printf("..................................................................");;
printf("\n                      Pilih Mata Uang\n");
  printf("..................................................................\n");
printf("1. Rupiah                                         2. Dollar                             \n");
 printf("..................................................................\n\n");
printf("Pilih Mata Uang Fiat: "); scanf("%d",&pilihan);

if (pilihan == 1){ printf(".................................................................."); printf("\n Mengkonversi Mata Uang Kripto ke Rupiah\n"); printf ("..................................................................\n"); printf("1. Bitcoin (BTC) 6. Ripple (XRP) \n"); printf("2. Ethereum (ETH) 7. Solana (SOL) \n"); printf("3. Binance (BNB) 8. Polkadot (DOT) \n"); printf("4. Cardano (ADA) 9. Dogecoin (DOGE) \n"); printf("5. Tether (USDT) 10. Shiba inu (SHIB) \n");

   printf("..................................................................\n");




printf("Pilih Mata Uang Kripto: ");
scanf("%d",&menu);


if (menu == 1){

  printf("Masukkan Jumlah Bitcoin(BTC):  ");
  scanf("%f", &IDR);

  BTC = IDR*866727711.37;
printf("..................................................................\n"); printf("Hasil Konversi Bitcoin ke Rupiah = Rp. %.2f\n", BTC); printf("..................................................................\n\n\n\n"); } else if (menu == 2){

  printf("Masukkan Jumlah Ethereum(ETH): ");
  scanf("%f", &IDR);

  ETH = IDR*54175633.99
;

printf("..................................................................\n"); printf("Hasil Konversi Ethereum ke Rupiah = Rp. %.2f\n", ETH); printf("..................................................................\n\n\n\n"); }

    else if (menu == 3){

  printf("Masukkan Jumlah Binance(BNB): ");
  scanf("%f", &IDR);

  BNB = IDR*6704178.18;
printf("..................................................................\n"); printf("Hasil Konversi Binance ke Rupiah = Rp. %.2f\n", BNB); printf("..................................................................\n\n\n\n"); }

    else if (menu == 4){

  printf("Masukkan Jumlah Carndano(ADA): ");
  scanf("%f", &IDR);

  ADA = IDR*31260.78;
printf("..................................................................\n"); printf("Hasil Konversi Cardano ke Rupiah = Rp. %.2f\n", ADA); printf("..................................................................\n\n\n\n"); } else if (menu == 5){

  printf("Masukkan Jumlah Tether(USDT): ");
  scanf("%f", &IDR);

  USDT = IDR*14058;
printf("..................................................................\n"); printf("Hasil Konversi Tether ke Rupiah = Rp. %.2f\n", USDT); printf("..................................................................\n\n\n\n");

   }
else if (menu == 6){

  printf("Masukkan Jumlah Ripple(XRP): ");
  scanf("%f", &IDR);

  XRP = IDR*16073.63;
printf("..................................................................\n"); printf("Hasil Konversi Ripple ke Rupiah = Rp. %.2f\n", XRP); printf("..................................................................\n\n\n\n");

   }

   else if (menu == 7){

  printf("Masukkan Jumlah Solana(SOL): ");
  scanf("%f", &IDR);

  SOL = IDR*2235509.48;
printf("..................................................................\n"); printf("Hasil Konversi Solana ke Rupiah = Rp. %.2f\n", SOL); printf("..................................................................\n\n\n\n");

   }

   else if (menu == 8){

  printf("Masukkan Jumlah Polkadot(DOT): ");
  scanf("%f", &IDR);

  DOT = IDR*612916.87;
printf("..................................................................\n"); printf("Hasil Konversi Polkadot ke Rupiah = Rp. %.2f\n", DOT); printf("..................................................................\n\n\n\n");

   }
       else if (menu == 9){

  printf("Masukkan Jumlah Dogecoin(DOGE): ");
  scanf("%f", &IDR);

  DOGE = IDR*3350.25;
printf("..................................................................\n"); printf("Hasil Konversi Dogecoin ke Rupiah = Rp. %.2f\n", DOGE); printf("..................................................................\n\n\n\n");

   }
     else if (menu == 10){

  printf("Masukkan Jumlah Shiba inu(SHIB): ");
  scanf("%f", &IDR);

  SHIB = IDR*0.3535;
printf("..................................................................\n"); printf("Hasil Konversi Shiba inu ke Rupiah = Rp. %.2f\n", SHIB); printf("..................................................................\n\n\n\n");

   }

    }
else if (pilihan == 2){ printf(".................................................................."); printf("\n Mengkonversi Mata Uang Kripto ke Dollar Amerika\n"); printf ("..................................................................\n"); printf("1. Bitcoin (BTC) 6. Ripple (XRP) \n"); printf("2. Ethereum (ETH) 7. Solana (SOL) \n"); printf("3. Binance (BNB) 8. Polkadot (DOT) \n"); printf("4. Cardano (ADA) 9. Dogecoin (DOGE) \n"); printf("5. Tether (USDT) 10. Shiba inu (SHIB) \n");

   printf("..................................................................\n");




printf("Pilih Mata Uang Kripto: ");
scanf("%d",&menu);


if (menu == 1){

  printf("Masukkan Jumlah Bitcoin(BTC):  ");
  scanf("%f", &USD);

  BTC = USD*61098;
printf("..................................................................\n"); printf("Hasil Konversi Bitcoin ke Dollar = $%.2f\n", BTC); printf("..................................................................\n\n\n\n"); } else if (menu == 2){

  printf("Masukkan Jumlah Ethereum(ETH): ");
  scanf("%f", &USD);

  ETH = USD*3915.68;
printf("..................................................................\n"); printf("Hasil Konversi Ethereum ke Dollar = $%.2f\n", ETH); printf("..................................................................\n\n\n\n"); }

    else if (menu == 3){

  printf("Masukkan Jumlah Binance(BNB): ");
  scanf("%f", &USD);

  BNB = USD*467.04;
printf("..................................................................\n"); printf("Hasil Konversi Binance ke Dollar = $%.2f\n", BNB); printf("..................................................................\n\n\n\n"); } else if (menu == 4){

  printf("Masukkan Jumlah Cardano(ADA): ");
  scanf("%f", &USD);

  ADA = USD*2.20;
printf("..................................................................\n"); printf("Hasil Konversi Cardano ke Dollar = $%.2f\n", ADA); printf("..................................................................\n\n\n\n"); } else if (menu == 5){

  printf("Masukkan Jumlah Tether(USDT): ");
  scanf("%f", &USD);

  USDT = USD*1;
printf("..................................................................\n"); printf("Hasil Konversi Tether ke Dollar = $%.2f\n", USDT); printf("..................................................................\n\n\n\n"); }

   else if (menu == 6){

  printf("Masukkan Jumlah Ripple(XRP): ");
  scanf("%f", &USD);

  XRP = USD*1.15;
printf("..................................................................\n"); printf("Hasil Konversi Ripple ke Dollar = $ %.2f\n", XRP); printf("..................................................................\n\n\n\n");

   }

   else if (menu == 7){

  printf("Masukkan Jumlah Solana(SOL): ");
  scanf("%f", &USD);

  SOL = USD*159.51;
printf("..................................................................\n"); printf("Hasil Konversi Solana ke Dollar = $ %.2f\n", SOL); printf("..................................................................\n\n\n\n");

   }
    else if (menu == 8){

  printf("Masukkan Jumlah Polkadot(DOT): ");
  scanf("%f", &USD);

  DOT = USD*42.54;
printf("..................................................................\n"); printf("Hasil Konversi Polkadot ke Dollar = $ %.2f\n", DOT); printf("..................................................................\n\n\n\n");

   }
   else if (menu == 9){

  printf("Masukkan Jumlah Dogecoin(DOGE): ");
  scanf("%f", &USD);

  DOGE = USD*0.2394;
printf("..................................................................\n"); printf("Hasil Konversi Dogecoin ke Dollar = $ %.2f\n", DOGE); printf("..................................................................\n\n\n\n");

   }
   else if (menu == 10){

  printf("Masukkan Jumlah Shiba inu(SHIB): ");
  scanf("%f", &USD);

  SHIB = USD*0.00002591;
printf("..................................................................\n"); printf("Hasil Konversi Shiba inu ke Dollar = $ %.2f\n", SHIB); printf("..................................................................\n\n\n\n");

   }


     }
}
return 0;

}

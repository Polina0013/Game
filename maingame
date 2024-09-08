#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#include <Windows.h>
#include <locale.h>

int main() {
    setlocale(LC_ALL, "Rus");
    srand(time(0));

    float start, vibor, win, povtor, win1, win2, win3;
    int chance;

    printf("Чтобы начать, введите 1: \n");
    scanf_s("%f", &start);

    if (start == 1) {
        system("cls");
        printf("Загрузка...");
        Sleep(1000);
        system("cls");

        printf("*Одним солнечным днём Вы решили пойти в тир пострелять из лука. Перед Вами 3 мишени.* \n");
        printf("*Каждая из них находится на разных расстоятиях от Вас. В первую попасть легче всего, а в третью, наоборот, тяжелее.* \n");
        printf("*В тире выдаются медальки за успешное попадание во все три мишени. Вы решаете, что не уйдете, пока не заберете её себе.* \n");

        win1 = 0;
        win2 = 0;
        win3 = 0;
        while ((win1 == 0) || (win2 == 0) || (win3 == 0)) {
            //ВСТАВИТЬ СЮДА ВЕСЬ КОД 
            printf("*Выбирайте мишень:* \n(введите 1, 2 или 3:) \n");
            scanf_s("%f", &vibor);
            system("cls");

            while ((vibor > 3) || (vibor <1)) {
                printf("*Нет мишени с таким номером! (Сложно выбрать от 1 до 3? -_-)*\n");
                scanf_s("%f", &vibor);
                system("cls");
            }

            if (vibor == 1) {
                printf("*Выбрана 1 мишень* \n");
                win = 0;

                while (win == 0) {

                    chance = 1 + rand() % 10;  //От 1 до 10

                    if (chance <= 7) {
                        printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Попадает в цель!* \n");
                        printf("   о о о  \n");
                        printf(" о       о \n");
                        printf("о     +   о \n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf(" о       о \n");
                        printf("   о о о   \n");

                        win = 1;
                    }
                    else {
                        printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Не попадает в цель!* \n");
                        printf("   о о о  \n");
                        printf(" о       о   +\n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf(" о       о \n");
                        printf("   о о о   \n");
                        printf("(введите 1, чтобы выстрелить снова:) \n");
                        scanf_s("%f", &povtor);
                    }
                }
                win1 = 1;
            }
            else {
                if (vibor == 2) {
                    printf("*Выбрана 2 мишень* \n");
                    win = 0;

                    while (win == 0) {

                        chance = 1 + rand() % 10;  //От 1 до 10

                        if (chance <= 5) {
                            printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Попадает в цель!* \n");
                            printf("   о о о  \n");
                            printf(" о       о \n");
                            printf("о     +   о \n");
                            printf("о         о \n");
                            printf("о         о \n");
                            printf(" о       о \n");
                            printf("   о о о   \n");

                            win = 1;
                        }
                        else {
                            printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Не попадает в цель!* \n");
                            printf("   о о о  \n");
                            printf(" о       о   +\n");
                            printf("о         о \n");
                            printf("о         о \n");
                            printf("о         о \n");
                            printf(" о       о \n");
                            printf("   о о о   \n");
                            printf("(введите 1, чтобы выстрелить снова:) \n");
                            scanf_s("%f", &povtor);
                        }
                    }
                    win2 = 1;
                }
                else {
                    printf("*Выбрана 3 мишень* \n");
                    win = 0;

                    while (win == 0) {

                        chance = 1 + rand() % 10;  //От 1 до 10

                        if (chance <= 3) {
                            printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Попадает в цель!* \n");
                            printf("   о о о  \n");
                            printf(" о       о \n");
                            printf("о     +   о \n");
                            printf("о         о \n");
                            printf("о         о \n");
                            printf(" о       о \n");
                            printf("   о о о   \n");

                            win = 1;
                        }
                        else {
                            printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Не попадает в цель!* \n");
                            printf("   о о о  \n");
                            printf(" о       о   +\n");
                            printf("о         о \n");
                            printf("о         о \n");
                            printf("о         о \n");
                            printf(" о       о \n");
                            printf("   о о о   \n");
                            printf("(введите 1, чтобы выстрелить снова:) \n");
                            scanf_s("%f", &povtor);
                        }
                    }
                    win3 = 1;
                }
            }
        }

        /*printf("*Выбирайте мишень:* \n(введите 1, 2 или 3:) \n");
        scanf_s("%f", &vibor);
        system("cls");

        if (vibor == 1) {
            printf("*Выбрана 1 мишень* \n");
            win = 0;

            while (win == 0) {
                
                chance = 1 + rand() % 10;  //От 1 до 10
                
                if (chance <= 7) {
                    printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Попадает в цель!* \n");
                    printf("   о о о  \n");
                    printf(" о       о \n");
                    printf("о     +   о \n");
                    printf("о         о \n");
                    printf("о         о \n");
                    printf(" о       о \n");
                    printf("   о о о   \n");

                    win = 1;
                }
                else {
                    printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Не попадает в цель!* \n");
                    printf("   о о о  \n");
                    printf(" о       о   +\n");
                    printf("о         о \n");
                    printf("о         о \n");
                    printf("о         о \n");
                    printf(" о       о \n");
                    printf("   о о о   \n");
                    printf("(введите 1, чтобы выстрелить снова:) \n");
                    scanf_s("%f", &povtor);
                }
            }
            win1 = 1;
        }
        else { 
            if (vibor == 2) {
                printf("*Выбрана 2 мишень* \n");
                win = 0;

                while (win == 0) {

                    chance = 1 + rand() % 10;  //От 1 до 10

                    if (chance <= 5) {
                        printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Попадает в цель!* \n");
                        printf("   о о о  \n");
                        printf(" о       о \n");
                        printf("о     +   о \n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf(" о       о \n");
                        printf("   о о о   \n");

                        win = 1;
                    }
                    else {
                        printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Не попадает в цель!* \n");
                        printf("   о о о  \n");
                        printf(" о       о   +\n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf(" о       о \n");
                        printf("   о о о   \n");
                        printf("(введите 1, чтобы выстрелить снова:) \n");
                        scanf_s("%f", &povtor);
                    }
                }
                win2 = 1;
            }
            else {
                printf("*Выбрана 3 мишень* \n");
                win = 0;

                while (win == 0) {

                    chance = 1 + rand() % 10;  //От 1 до 10

                    if (chance <= 3) {
                        printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Попадает в цель!* \n");
                        printf("   о о о  \n");
                        printf(" о       о \n");
                        printf("о     +   о \n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf(" о       о \n");
                        printf("   о о о   \n");

                        win = 1;
                    }
                    else {
                        printf("*Вы медленно натягиваете тетиву, стрела вылетает и... Не попадает в цель!* \n");
                        printf("   о о о  \n");
                        printf(" о       о   +\n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf("о         о \n");
                        printf(" о       о \n");
                        printf("   о о о   \n");
                        printf("(введите 1, чтобы выстрелить снова:) \n");
                        scanf_s("%f", &povtor);
                    }
                }
                win3 = 1;
            }
        }*/

        /*printf("   о о о  \n");
        printf(" о       о \n");
        printf("о     +   о \n");
        printf("о         о \n");
        printf("о         о \n");
        printf(" о       о \n");
        printf("   о о о   \n");*/

        system("cls");
        printf("*Потрясающе! Все три мишени поражены! У Вас меткий глаз!*\n");
        printf("*Работник тира любезно выдает Вам медальку. С хорошем настроением Вы выходите из тира и отправляетесь дальше.*\n");
        printf("  о о о о \n");
        printf(" о <--<< о\n");
        printf("о >>-->   о\n");
        printf("о   <--<< о\n");
        printf(" о >>--> о\n");
        printf("  о о о о \n");
    }
    else {
        printf("Ошибка загрузки, попробуйте снова :( (Не хочешь играть? Просто введи уже 1)\n");
    }
    return(0);
}

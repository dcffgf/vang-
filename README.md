# vang-#include <stdio.h>
#include <conio.h>
#include <string.h>
	printf("Nhap ho ten cua tung hoc sinh, ket thuc go Enter\n");
	do {
		printf("Ho ten hoc sinh thu %d : ", i++);
		gets(s);
		if (strlen(s) > 0)
		{
			strcat(s, "\n");
			fputs(s, f);
		}
	} while (strlen(s) > 0);
	fclose(f);
}

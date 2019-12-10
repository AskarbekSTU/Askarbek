#include<stdio.h>
#define N 1000





int readText(FILE *fr, char pole [], int count){
	char c;
	count = 0;
	if (fr == NULL){
		printf("Spravu sa nepodarilo nacitat\n");
	}
	
	while (((c = fgetc(fr)) != EOF ) && count < N){
		pole[count] = c;
		count ++;
	}
	return count;
}


int writeMessage(FILE *fr, char pole[], int q){
char t;
if (fr == NULL){	
	printf("Sprava nie je nacitana\n");
	}

	while (((t = fget(fr)) != EOF) &q){
	pole[q] = t;
		q ++;
	}
	return 0;	
	}
}

int readNumbers (FILE, *fr, char pole [], int s) {
	char s;
	if (fr == NULL){
	printf("Sprava nie je nacitana\n");	
	}

	while ( s >= 65 || p <= 90 ) 
	{
		count++
	}
	printf("%c" &p);
	
	while ( s >= 97 || p <= 122);
	printf("%c" &p)
	{
		return 0;
	}
}
	


int main()
{
	FILE *fr;
	int x;
	int q;
	int s;
	
	
	char original[N];
	char updated[N];
	
	char v;
	scanf("%c", &v);
	
	
	switch(v){
		case 'n': fr = fopen("sifra.txt", "r");
		x = readText(*fr, original, updated);
		break;
		
		case u: fr = fopen("sifra.txt", "r");
		q = writeMessage(*fr, original, updated, q);
		break;

		case s: fr = fopen("sifra.txt", "r");
		p = readNumbers (*fr, original, updated,s);
		break;
		
		case d: fr = fopen("sifra.txt", "r");
		p = readNumbers (*fr, original, updated,d);
		break;
		
	
	}
	return 0;
}

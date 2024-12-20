#include <stdio.h>
// Define a structure to store book information struct Book
{
char title[50]; char author[50]; int year; float price; };
int main()
{ struct Book b1; // Input book information printf("Enter book title: ");
scanf("%s", &b1.title); // Use scanf for simple input printf("\n Enter author's name: ");
scanf("%s", &b1.author); // Use scanf for simple input printf("\n Enter year of publication: "); scanf("%d", &b1.year); printf("\n Enter price of the book: "); scanf("%f", &b1.price);
// Display the stored information printf("\n--- Book Information ---\n"); printf("Title: %s\n", b1.title); printf("Author: %s\n", b1.author); printf("Year: %d\n", b1.year); printf("Price: %.2f\n", b1.price); return 0;
}

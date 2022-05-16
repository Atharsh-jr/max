ALGORITHM finding max element SET Max to array[0]
FOR i = 1 to array length - 1 IF array[i] > Max THEN SET Max to array[i] ENDIF
ENDFOR PRINT Max
 #include <stdio.h> 
void main()
{
int i, n,max;
int arr[100];

printf("Enter total number of elements(1 to 100): "); scanf("%d", &n);

for(i = 0; i < n; ++i)
{
printf("Enter array of elements\n”);
 scanf("%d", &arr[i]);
}
max=arr[0];
for(i = 1; i < =n; ++i)
{
if(arr[i]>max)
max= arr[i];
}
printf("Largest element = %d",max); 
}

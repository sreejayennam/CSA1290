import java.util.Scanner;
public class Main{
public static void main(String[]args){
int a[] = new int [2];
System.out.println("enter the numbers\n");
Scanner s = new Scanner(System.in);
for(int i=0;i<2;i++){
a[i]=s.nextInt();
}
int instructions=0;
int clock =1;
int add=0;
int sub = a[0];
int stage =0;
for(int i=0;i<2;i++){
if(a[i]==0){
break;
}
else{
instructions =instructions+1;
clock = clock+1;
add = add+a[i];
sub = sub-a[i];
}
}
System.out.println("The number of clock cycles required are:\n"+clock);
System.out.println("addition:\n"+add);
System.out.println("subtraction:\n"+sub);
System.out.println("highthroughput is:\n");
float throughput;
throughput =instructions/clock;
System.out.println("The throughput requires for execution of the instruction:\n"+throughput+"%");
}
}

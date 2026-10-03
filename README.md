# Hackathon1
# 2a)
public class RoofTopSolarSystem {
public static void main(String[] args) { 
int panelID = 100;              
double energyGenerated = 200.10;  
int numberOfPanels = 10;            
char systemStatus = 'P';            
System.out.println("Rooftop Solar System Details:");
System.out.println("Panel ID: " + panelID);
System.out.println("Energy Generated : " + energyGenerated);
System.out.println("Number of Solar Panels: " + numberOfPanels);
System.out.println("System Status: " + systemStatus);
    }
}
# 2b)
import java.util.Scanner;
public  class Generation{
public static void main (String[] args){
Scanner sc=new Scanner(System.in);
double energyGenerated=sc.nextDouble();
if(energyGenerated>10){
    System.out.println("Good Energy Generation");}
else{
    System.out.println("Low Energy Generation");
    
}}}
# 2c)

import java.util.Scanner;
public class SolarEnergy {

    public static double calculateTotalEnergy(double morningEnergy, double eveningEnergy) {
    return morningEnergy + eveningEnergy;
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter morning energy generated: ");
        double morningEnergy = sc.nextDouble();
        System.out.print("Enter evening energy generated: ");
        double eveningEnergy = sc.nextDouble();
        double totalEnergy = calculateTotalEnergy(morningEnergy, eveningEnergy);
        System.out.println("Total energy generated: " + totalEnergy);

        
    }
}



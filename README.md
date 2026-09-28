# st10529996_PROG1B_TESt
public class GamingReport {
    public static void main (String[] args) {
        
        //1. Single array for sales
        String[] cities = {"CAPE TOWN", "PORT ELIVABETH", "PRETORIA"};
        
        //2. Two dimensinal arrays for sales [cities][console]
        // PS5, XBOX, SWITCH
        int[][] sales = {
            {1000, 2000, 3000}, //Cape Town
            {2000, 3000, 4000}, //Port Elizabeth
            {1500, 1100, 1200}, //Pretoria
        };
        String[] consoles = {"PS5", "XBOX", "SWITCH"};
        
        // --- PRINT HEADER ---
        System.out.println("------------------------------------")
        System.out.println("GAMING CONSOLE REPORT")
        System.out.println("-----")
        System.out.println("PS5", "XBOX", "SWITCH");
        System.out.println("------------------------------------")
        
        // --- PRINT REPORT (using 2d array loop)
        for(int i = 0; i < cities.length; 1++) {
            System.out.printf("%-20s", cities[i]);
            for (int j = 0; j < sales[i]. length; j++) {
                System.out.printf("%-10d", sales[i][j]);
            }
            System.out.println("----");
        
System.out.println("\n---")        
            System.out.println("CONSOLE SALES TOTALS FOR EACH CITY");
            System.out.println("------------------------------------")
            
            // --- CALCULATE TOTAL + FIND MAX CITY ----
            int maxSales = 0;
            String maxSales = "";
            int[] totalPerCity = new int[3];
            
            for(int i = 0; i < sales.length; i++) {
                int total = 0;
                for(int j = 0; j < sales[i].length; j++) {
                    total += sales[i][j]; //sum row
                }
            }
            System.out.println("------------------------------------");
            System.out.println("CITY WITH THE MOST SALES: "maxCity);
            System.out.println("------");

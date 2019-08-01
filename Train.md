# Train-service-using-arrays


package train;
important java.util.*;
public class Train{

       public static void main(string[]args){
       Scanner sc=new Scanner (System.in);
        String [] day={"Monday","Monday","Monday","Monday","Monday","Tuesday","Tuesday","Tuesday","Tuesday","Tuesday","Wednesday","Wednesday","Wednesday","Wednesday","Wednesday"}
      double []time={06.04,09.04,12.04,15.04,19.04,06.04,09.04,12.04,15.04,19.04,06.04,09.04,12.04,15.04,19.04};
       int[]pssngr={22,119,64,177,21,22,111,87,193,22,11,107,93,162,42};

         System.out.println("\nDays\t\t\tDeparture time\t\t\tPassenger number");
     for(int i=0;i<5;i++)
     System.out.println(day[i]+"\t\t\t"+time[i]+"\t\t\t"+pssngr[i]);


System.out.println("\nDays\t\t\tDeparture time\t\t\tPassenger number");
       for(int i=5;i<10;i++)
     System.out.println(day[i]+"\t\t\t"+time[i]+"\t\t\t"+pssngr[i]);



System.out.println("\nDays\t\t\tDeparture time\t\t\tPassenger number");

for(int i=10;i<15;i++)
     System.out.println(day[i]+"\t\t\t"+time[i]+"\t\t\t"+pssngr[i]);

      int most=pssngr[0];
      int inp=0;
      for(int i=0;i<15;i++){
       if(pssngr[i]>most){
          most=pssngr[i];
          inp=i;
        }
     }
    System.out.println("\nThe most popular train:"+day[inp]+"\t\t\t"+time[inp]);

       int least=pssngr[0];
       int inp=0;
       for(int i=0;i<15;i++){
      if (pssngr [i]<least){
      least= pssngr [i];
      inp=i;
     }
   }
  System.out println("The least popular train:"+day[inp]+"\t\t"+time[inp]);

       int train 1=(pssngr[0]+pssngr[5]+pssngr[10])/3;
       int train 2=(pssngr[1]+pssngr[6]+pssngr[11])/3;
    
       if(train1>train2)
            System.out.println("\n6.04 train is more popular than 9.04 train");
       else
            System.out.println("\n9.04 train is more popular than 6.04 train");
     
       if(pssngrr[0]>pssngr[5])
            System.out.println("\n6.04 train on monday is more popular than 6.04 train on tuesday");
       else
            System.out.println("\n6.04 train on monday is not more popular than 6.04 train on tuesday");
       System.out.println("\n\tList of all trains that have less than 50 pssngrs");
       for(int i=0;i<15;i++){
           if(pssngr[i]<50){
              System.out.println("("+day[i]+","+time[i]+")");
           }
       }
       
    
       int average=(pssngr[2]+pssngr[7]+pssngr[12])/3;
       System.out.println("\n\tAverage number of pssngr travelling on the 12.04 train: "+average);
      
       
    }
    
}

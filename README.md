# Multiple-inheritance.java

// multiple inheritance program

class bike{

   public bike()
   {
   
  System.out.println("Class bike");
  
   }
   
   public void vehicleType()
   
   {
   
  System.out.println("Vehicle Type: bike");
  
   }
   
}

class shine extends bike{

   public shine()
   
   {
   
  System.out.println("Class shine");
  
   }
   
   public void brand()
   
   {
   
  System.out.println("Brand: shine");
  
   }
   
   public void speed()
   
   {
   
  System.out.println("Max: 90Kmph");
  
   }
   
}

public class shine100 extends shine{

   public shine100()
   
   {
   
  System.out.println("shine Model: 100");
  
   }
   
   public void speed()
   
   {
   
  System.out.println("Max: 90Kmph");
  
   }
   
   public static void main(String args[]) {
   
   shine100 obj=new shine100();
   
   obj.vehicleType();
   
   obj.brand();
   
   obj.speed();
   
   }
   
}

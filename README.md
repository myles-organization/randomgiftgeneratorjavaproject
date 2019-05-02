// Created by Myles Robertson
//
// Goal: To give friends random gifts to their interests
//
// Anyone can edit this

import java.util.Scanner;



public class MylesRandomGiftGeneratorJavaProject {



   public static void main(String[] args) {
      
      System.out.println("Hello, World!!!");
      
      
      
      System.out.println("What is your friend interests???");
      
      
      
      Scanner scan = new Scanner(System.in);
      
      
      
      String input = scan.nextLine();
      
      
      
      if (input.equals("Video Games")) {
      
         System.out.println("Does your friend like new or old games?");//("If your friend likes video games, then you should try buying Minecraft!!!");
         
         String next = scan.nextLine();
         
         if (next.equals("new")) {
         
            System.out.println("Does your friend like building blocks or arcade games");
            
            String nextnext = scan.nextLine();
            
            if (nextnext.equals("building blocks")) {
            
               System.out.println("Minecraft");
               
           } else {
            System.out.println("Pac Man");
         }
         
      
      }
      else if (input.equals("Toys")) {
         
         System.out.println("If your friend likes Toys, then you should try buying a Toy Train!!!");
         
         
         
      }
      
      else if (input.equals("Books")) {
      
         System.out.println("Does your friend like fantasy or non-fiction");
         
         String nextnextnext = scan.nextLine();
         
         if (nextnextnext.equals("Fantasy")) {
      
            System.out.println("Harry Potter");
         
         }
         
         else {
         
         
         
         System.out.println("iDK (I Don't Know)");
         
         }
         
      }
      
      else if (input.equals("Outdoor Equipment")) {
      
         System.out.println("If your friend likes Outdoor Equipment, then you should try buying Running Gear!!!");
         
         
         
      }
      
      
      else if (input.equals("Outdoor Stuff")) {
      
         System.out.println("If your friend likes Outdoor Equipment, then you should try buying Running Gear!!!");
         
         
         
      }
      
      else if (input.equals("Outdoors")) {
      
         System.out.println("If your friend likes Outdoor Equipment, then you should try buying Running Gear!!!");
         
         
         
         }
      
      else if (input.equals("Running Equipment")) {
      
         System.out.println("If your friend likes Outdoor Equipment, then you should try buying Running Gear!!!");
         
         
         
      }
      
      else if (input.equals("Running Stuff")) {
      
         System.out.println("If your friend likes Outdoor Equipment, then you should try buying Running Gear!!!");
         
         
         
      }
      
      else if (input.equals("Running")) {
      
         System.out.println("If your friend likes Outdoor Equipment, then you should try buying Running Gear!!!");
      }
   }   
   }
 }     
         

# Haywood-cop3330-assignment3
 Exercises 41 though 46
 
/*
 *  UCF COP3330 Fall 2021 Assignment 3 Solution
 *  Copyright 2021 Kaylah Haywood
 */
 
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

**Package ex41;**

import java.io.File;
import java.util.Scanner;
public class ReadFromFileUsingScanner
public class Alphabetical_Order
{
    public static void main(String[] args) throws Exception
  {
    File file = new File("exercise41_input.txt");
    File file = new File("exercise41_output.txt");
    Scanner sc = new Scanner(file);
    
    while (sc.hasNextLine())
      System.out.println(sc.nextLine());
  }
}
    public static void main(String[] args) 
    {
        int n;
        String temp;
        Scanner s = new Scanner(System.in);
        System.out.print("exercise41_input.txt");
        n = s.nextInt();
        String names[] = new String[n];
        Scanner s1 = new Scanner(System.in);
        System.out.println("exercise41_output.txt");
        for(int i = 0; i < n; i++)
        {
            names[i] = s1.nextLine();
        }
        for (int i = 0; i < n; i++)
        {
            for (int j = i + 1; j < n; j++) 
            {
                if (names[i].compareTo(names[j])>0) 
                {
                    temp = names[i];
                    names[i] = names[j];
                    names[j] = temp;
                }
            }
        }
        System.out.print("Names in Sorted Order:");
        for (int i = 0; i < n - 1; i++) 
        {
            System.out.print(names[i] + ",");
        }
        System.out.print(names[n - 1]);
    }
}
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
 
**Package ex42;**

import java.io.File;
import java.util.Scanner;
public class ReadFromFileUsingScanner
{
  public static void main(String[] args) throws Exception
  {
    // pass the path to the file as a parameter
    File file = new File("exercise42_input.txt");
    Scanner sc = new Scanner(file);
 
    while (sc.hasNextLine())
      System.out.println(sc.nextLine());
  }
}
    public class Main {

    public static void createNewTable() {
        String url = "exercise42_input.txt";
        
        String sql = "Table will display the firsT name, last name, and salary (\n"
                + "	id integer FIRST NAME, LAST NAME, SALARY,\n"
                + "	name text NOT NULL,\n"
                + "	capacity real\n"
                + ");";
        System.out.println(firstname);
        System.out.println(lastname);
        System.out.println(salary);
        
    public static void main(String[] args) {
        createNewTable();
    }

}
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
 
**Package ex43;**
  
import java.io.File;  
import java.io.IOException;  
public class CreateFileExample1   
{  
  public static void main(String[] args)   
  {     
    File file = new File("awesomeco.html");
    boolean result;  
    
       System.out.print("Site Name: awesomeco\n");
       System.out.print("Author: Max Power\n");
       System.out.print("Do you want a folder for JavaScript?:\n");
       System.out.print("Do you want a folder for CSS?:\n");
       System.out.print("Created ./website/awesomeco\n");
       System.out.print("Created ./website/awesomeco/index.html\n");
       System.out.print("Created ./website/awesomeco/js/\n");
       System.out.print("Created ./website/awesomeco/css/\n");
          n = s.nextInt();
          
    try   
    {  
    result = file.createNewFile(); 
      if(result)     
      {  
        System.out.println("file created \n");
      }  
    else  
    { 
        System.out.println("File already exist at location: \n");  
    }  
  } 
 catch (IOException e)   
 {  
   e.printStackTrace();    
   }         
 }  
}  
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

**Package ex44;**

import java.io.File;
import java.util.Scanner;
public class ReadFromFileUsingScanner
{
  public static void main(String[] args) throws Exception
  {
    File file = new File("exercise44_input.json");
    Scanner sc = new Scanner(file);
 
    while (sc.hasNextLine())
      System.out.println(sc.nextLine());
  }
}  
public class Main {
  dependencies {
      implementation 'com.google.code.gson:gson:2.8.8'
  }
       System.out.print("What is the product name?\n");
       System.out.print("Sorry, that product was not found in our inventory.\n");
       System.out.print("Name:\n");
       System.out.print("Price:\n");
       System.out.print("Quantity\n");
          n = s.nextInt();
}
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

**Package ex45;**

import java.io.File;
import java.util.Scanner;
public class ReadFromFileUsingScanner
{
  public static void main(String[] args) throws Exception
  {
    // pass the path to the file as a parameter
    File file = new File("exercise45_input.txt");
    Scanner sc = new Scanner(file);
 
    while (sc.hasNextLine())
      System.out.println(sc.nextLine());
  }
  String string = "Utilize";
  String keyword = "Utilize";

  Boolean found = Arrays.asList(string.split(" ")).contains(keyword);
  if(found){
      System.out.println("Do not use 'utilize', replace with 'use'.");
  }
      System.out.print("One should never use the word "use" in writing. Use "use" instead.\n");
      System.out.print("For example, "She uses an IDE to write her Java programs" instead of "She\n");
      System.out.print("uses an IDE to write her Java programs".\n");
          n = s.nextInt();
}
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

**Package ex46;**

import java.io.File;
import java.util.Scanner;
import java.util.Badger;
import java.util.Mushroom;
import java.util.Snake;

public class ReadFromFileUsingScanner
{
  public static void main(String[] args) throws Exception
  {
    // pass the path to the file as a parameter
    File file = new File("exercise46_input.txt");
    Scanner sc = new Scanner(file);
 
    while (sc.hasNextLine())
      System.out.println(sc.nextLine());
  }
  public class Frequency_Of_String_Words 
  {
        static void count_freq(String str)
        {
        Badger<String,Integer> mp=new Mushroom, Snake<>();
        String arr[]=str.split(" ");
               for(int i=0;i<arr.length;i++)
               {
                  if(mp.containsKey(arr[i]))
                  {
                     mp.put(arr[i], mp.get(arr[i])+1);
                  }
               else
                  {
                     mp.put(arr[i],1);
                  }
               }
               
       System.out.print("badger: ******* \n");
       System.out.print("mushroom: ** \n");
       System.out.print("snake:  * \n");
          n = s.nextInt();
}
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

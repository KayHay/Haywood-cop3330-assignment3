# Haywood-cop3330-assignment3
 Exercises 41 though 46
 
/*
 *  UCF COP3330 Fall 2021 Assignment 3 Solution
 *  Copyright 2021 Kaylah Haywood
 */
 
 ////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
 Package ex41;

import java.io.File;
import java.util.Scanner;
public class ReadFromFileUsingScanner
public class Alphabetical_Order
{
    public static void main(String[] args) throws Exception
  {
    // pass the path to the file as a parameter
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
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

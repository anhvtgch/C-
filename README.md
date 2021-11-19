# C-
learn in fpt
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Lesson01
{
    internal class Ex01
    {
public Ex01()
            {
            Console.WriteLine("This is the exercise 01");
            //int arr[5];               // -In C
            int[] arr = new int[5];    // -In C#
                      //5: the length of array 'arr'
                      // we can store at maximun 5 elements
                      //int[] arr = {10, 12, 18, 5 ,9};

            arr[0] = 10;
            // arr[1] = 12.5;
            arr[1] = 12;
            arr[2] = 18;
            arr[3] = 5;
            arr[4] = 9;
            arr[arr.Length - 1] = 9;
            // arr[5] =15; run-time error vs. compiler-time error
            //- Array is a set/list of elements
            // -These elements in an array int the same date type
            // we can access elements of an array via their index
            // we must define the length of an array used

            int j = 0;
            while (j < arr.Length)
            {
                Console.WriteLine(arr[j]);
                j++;
            }

            Console.WriteLine("-------------");

            for(int i = 0; i < arr.Length; i++)
            {
                Console.WriteLine(arr[i]);
            }

            Console.WriteLine("--------------");
            j=0;   
            do
            {
                Console.WriteLine(arr[j]);
                j++;
            }while ( j < arr.Length);

            Console.WriteLine("-------------");
            foreach(int e in arr)
            {
                Console.WriteLine(e);
            }


            string[] songs = new string[10];
            // 10: thength of array 'song'
            songs[0] = "My heart will go on";
            songs[1] = "10";
        }
    }
}

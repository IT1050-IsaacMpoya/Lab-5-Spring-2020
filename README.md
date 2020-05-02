# Lab-5-Spring-2020

Answers 

Qn 2.  P[1], P[2], P[3], P[4],

Qn 3.    {
               string[] months = new string[12];
                months[0] = "Jan";
                months[1] = "Feb";
                months[2] = "Mar";
                months[3] = "Apr";
                months[4] = "May";
                months[5] = "Jun";
                months[6] = "Jul";
                months[7] = "Aug";
                months[8] = "Sep";
                months[9] = "Oct";
                months[10] = "Nov";
                months[11] = "Dec";

                Console.WriteLine("{0}{1,12}","       Index", "month");//headings
                
                for (int i = 0; i < months.Length; i++) //initializes for loop to count
                {
                    Console.WriteLine("{0,12}{1,8}", i, months[i]); // Method used to run the loop
                }   
 

Qn 4.   {   You can use the one below to create the array 
string[] season = new string[4] { "Winter", "Spring", "Summer", "Fall" };//creates 4    elements 
                                  foreach (string i in seasons) // foreach loop initializes counter
                {
                    Console.WriteLine(i); //method
                }

                     OR

                string[] seasons = { "Winter", "Spring", "Summer", "Fall" };//Creates 4 element array
                foreach (string i in seasons) // foreach loop initializes counter
                {
                    Console.WriteLine(i); //method
                }


Qn 5.       int[] randomNumber = new int[1000];
                Random random = new Random();
                for (int i = 0; i < randomNumber.Length; i++)
                {
                    randomNumber[i] = random.Next(0, 100);
                }

                foreach (int i in randomNumber)
                {
                    Console.WriteLine(i.ToString());

                }
                Console.WriteLine();
            }
Qn 6.    string [] names = { "Al Dente", "Anna Graham", "Earle Bird", "Ginger Rayle", "Iona Ford" };
             int i = 0;  
             while (i < names. Length) 
             {
                 Console.WriteLine(names[i]);i++;
             }





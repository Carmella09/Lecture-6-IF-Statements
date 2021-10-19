# L6-Codes

It's my Birthday

      #include <iostream>
      using namespace std;

      int main()
      {
          bool myBirthday = true;
          int age = 18;
          if (myBirthday == true) {
              age++;
              cout << "It is my birthday. I am " <<
                  age << " years old";
          }
          else {
              cout << "It is not my birthday" <<
                  endl;
          }

      }

   Good Morning?
   
      #include <iostream>
      using namespace std;
      int main() 
      {
         int currentTime = 3; 
            if (currentTime > 12) { 
                  cout << "It's PM" << endl; 
            }
            else { 
               cout << "It's AM" << endl;
            }
         cin.get(); 
         return 0;
      }
   
   Extension Problem (Optional)
   
   
   
   Can I vote?
   
      #include <iostream>
      using namespace std;
      int main() 
      {
         int age; 
         cout << "Age: " << endl;
         cin >> age;

            if (age >= 18) { 
                  cout << "You can vote" << endl; 
            }
            else { 
               cout << "You can't vote" << endl;
            }
         cin.get(); 
         return 0;
      }

// Homeworks/Assingment (fixed Version)

   even ODD

      #include <iostream>
      using namespace std;
      int main()
      {
          int Number; 
          cout << "Enter any number: \n" << endl;
          cin >> Number; 
          if (Number % 2 == 0) {
              cout << Number << " is even ";
          }
          else {
              cout << Number << " is odd " << endl;
          }
          cin.get();
          return 0;
      }



   Number Checker positive or not
   
      #include <iostream>
      using namespace std;
      int main()
      {
          double Number;

          cout << "Enter any number: \n" << endl;

          cin >> Number;

          if (Number > 0) {
              cout << Number << " is a positive number. ";
          }
          else if (Number < 0) {
              cout << Number << " is a negative number. ";
          }
          else {
              cout << Number << " is a zero. " << endl;
          }
          cin.get();
          return 0;
      }
      
      
     
 profit or loss (need to be fixed)

      #include <iostream>
      using namespace std;
      int main()
      {
          int Profit, Loss, Purchase, Sale;
          cout << "Enter the Purchase Price: \n" << endl;
          cin >> Purchase;
          cout << "Enter the Sale: \n" << endl;
          cin >> Sale;

          if (Profit = Purchase - Sale  ) {
              cout << " AED " << Profit << endl;
          }
          if (Loss = Sale - Purchase) {
              cout << " AED " << Loss << endl;
          }
          else {
              cout << " none " << endl;
          }
          cin.get();
          return 0;
      }

      
   Name That Shape

      #include <iostream>
      using namespace std;
      int main()
      {
          int Shape;
          cout << "Enter any number: \n" << endl;
          cin >> Shape;
          if (Shape == 3) {
              cout << Shape << " is triangle " << endl;
          }
          else if (Shape == 4) {
              cout << Shape << " is square" << endl;
          }
          else if (Shape == 5) {
              cout << Shape << " is pentagon " << endl;
          }
          else if (Shape == 6) {
              cout << Shape << " is a hexagon " << endl;
          }
          else if (Shape == 7) {
              cout << Shape << " is a heptagon " << endl;
          }
          else if (Shape == 8) {
              cout << Shape << " is a octagon " << endl;
          }
          if (Shape == 9) {
              cout << Shape << " is a nonagon " << endl;
          }
          else if (Shape == 10) {
              cout << Shape << " is a star " << endl;
          }
          else {
              cout << Shape << " sides of shapes is not found " << endl;
          }
          cin.get();
          return 0;
      }


                                               



# Lesson-10
count from 0-50

    # include <iostream>
    using namespace std;
    int main()
    {
      for(int x = 0;x <= 50; x++)
      {
        if (x != 0)
          cout << x << endl;
        else
          cout << "Reached 50" << endl;
      }

    }
    
Count from 50-0


    # include <iostream>
      using namespace std;
      int main()
      {
        for(int x = 50;x >= 0; x--)
        {
          if (x != 0)
            cout << x << endl;
          else
            cout << "Countdown finished" << endl;
        }

      }

Count from 30-50

    # include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 30;x <= 50; x++)
        {
            if (x != 29)
                cout << x << endl;
            else
                cout << "Count starts now!" << endl;
        }

    }

Write a program that counts down from 50 to 10
in decrements of 2

    # include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 50;x >= 10; x-=2)
        {
            if (x != 49)
                cout << x << endl;
            else
                cout << "yey!";
        }

    }
  
Write a program that counts up from 100 to 200
in increments of 5.

    # include <iostream>
    using namespace std;
    int main()
    {
        for (int x = 100;x <= 200; x+=5)
        {
            if (x != 100)
                cout << x << endl;
            else
                cout << "100 to 200 count with increments of 5.\n";
        }

    }
    
odd or even

    #include <iostream>
    using namespace std;
    int main()
    {
      for (int x = 20; x <= 24; x++)
      {
        if (x %2==0)
          cout << x << " - even" << "\n";
        else
          cout << x << " - odd" << "\n";
      }

    }
 
 Rising star 5 lines
 
        #include <iostream>
        using namespace std;
        int main()
        {
            for (int i = 1; i <= 5; i++)
            { 
                for (int j = 1; j <= i; j++)
                {
                    cout << "*"; 
                }
                cout << endl;  
            }
        }

Falling stars

    #include <iostream>
    using namespace std;
    int main()
    {
        for (int i = 1; i <= 5; i++)
        {
            for (int j = i; j < 5; j++)
            {
                cout << "*";
            }
            cout << endl;
        }
    }

rising and falling stars

    #include <iostream>
    using namespace std;
    int main()
    {
        for(int i = 1; i <=5; i++)
        { 
            for(int j = 1; j <=i; j++)
            {
                cout << "*"; 
            }
            cout << endl;  
        }
        for (int i = 1; i <= 5; i++)
        {
            for (int j = i; j < 5; j++)
            {
                cout << "*";
            }
            cout << endl;
        }

    }
    
Cube 

    #include <iostream>
    using namespace std;
    int main()
    {
        int r;
        cout << "Enter a number to find the cube" << endl;
        cin >> r;
        for (int x = 1; x <= r; x++)
        {
            cout << "\nNumber is " << x << " the cube is ";
            int y = x;
            y=y* y* y;
            cout << y;
        }

    }

9s

    #include <iostream>
    using namespace std;
    int main()
    {
        int sum = 0;

        for (int x = 100; x <= 200; x++)
        {
            if (x % 9 == 0)
            {
                cout << "\nNumber is " << x << endl;

                sum = sum + x;

                        }


        }
        cout << "The sum is " << sum << endl;
    }



#include <iostream>

using namespace std;
class rectangle{
private:
    int k,x;
 public:
      rectangle(int rectanglek , int rectanglex){
       k =rectanglek;
        x = rectanglex;
          cout<<"rectangle cons is called"<<endl;
     }


     void area(){
         int area= k*x;
         cout<<"is area :"<<area<<endl;
     }

};

int main()
{
    rectangle p2(6,9);
    p2.area();

         return 0;
}

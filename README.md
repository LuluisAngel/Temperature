# Temperature
Here's the code

  #include <iostream>

  using namespace std;
  
  int main () {
  	
  	double f, c;
  
  	cout << "What is the temperature in Fahrenheit?" << endl;
  	cin >> f;
  
  	c = 5 *(f-32)/9;
  
  	cout << endl << "A temperature of " << f << " degrees Fahrenheit is equal to " << c << " degrees in Celsius." << endl;
  
  	if (c==100 || c>100){
  		
  		cout << endl << "Water boilds at this temperature (under typical conditions)." << endl;
  	}
  
  		else {	
  			cout << endl << "Water doesn't boil at this temperature (under typical conditions)." << endl;
  		}
  
  	return 0;
  }

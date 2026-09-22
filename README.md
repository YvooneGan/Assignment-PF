#include<iostream>
#include<string>
#include<cmath>
using namespace std;
#define SIZE 3

//function duration
int calculateDuration(int entry, int exit);
int calculateHours (int minutes);
double getRate (string vehicle, string vehicleType[], double rate[]);
double calculateDiscount(double charge, char member);

int main(){
  //Array
  string vehicleType[SIZE] = {"Car", "Motorcycle", "Van"};
  double rate[SIZE] = {3.00, 1.50, 5.00};

  int entryHour, entryMinute;
  int exitHour, exitMinute;

  int entryTime, exitTime;
  int duration;
  int parkingHours;

  string vehicle;
  char member;

  double hourlyRate, basicCharge, discount, finalCharge;

  

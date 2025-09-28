/*
## Assignment 5
Prompt the user for a number of seconds. Take the user's input and convert the number of seconds into its duration in Hours, Minutes, and remaining Seconds.

Extra Credit: Make sure the Hours, Minutes, and Seconds print with no decimal places.

## Example Output
```terminal_session
tokyo:~/LearningC/ # ./assignment5                                        
Enter the amount of seconds: 18550
18550 seconds is equal to 5 hours, 9 minutes, and 10 seconds.#
*/

int seconds;
cout << "Enter an amount of seconds << endl;
cin >> seconds;
int secondsTemp = seconds;
int hours = secondsTemp / 3600;
secondsTemp -= hours*3600;
int minutes = secondsTemp / 60;
secondsTemp -= minutes*60;
cout << seconds << " seconds is equal to " << hours << " hours, " << minutes << " minutes, and " << secondsTemp << " seconds." << endl;

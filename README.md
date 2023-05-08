Download Link: https://assignmentchef.com/product/solved-programming-assignment-1-heart-rate-calculator
<br>
Solved: Programming Assignment 1: Heart Rate Calculator

<strong>Problem Description:</strong>

(Target- Heart- Rate Calculator) While exercising, you can use a heart- rate monitor to see that your heart rate stays within a safe range suggested by your trainers and doctors. According to the American Heart Association (AHA) (www. americanheart. org/ presenter. jhtml? identifier= www.americanheart.org/presenter.jhtml?identifier= 4736), the formula for calculating your maximum heart rate in beats per minute is 220 minus your age in years. Your target heart rate is a range that’s 50– 85% of your maximum heart rate.




[Note: These formulas are estimates provided by the AHA. Maximum and target heart rates may vary based on the health, fitness and gender of the individual. Always consult a physician or qualified health care professional before beginning or modifying an exercise program.]




Create a class called HeartRates. The class attributes should include the person’s first name, last name, date of birth (consisting of separate attributes for the month, day and year of birth) and current year. Your class should have a constructor that receives this data as parameters. For each attribute provide set and get methods. The class also should include a method that calculates and returns the person’s age (in years), a method that calculates and returns the person’s maximum heart rate and two methods that calculates and returns the person’s maximum and minimum of target heart rates.




Write a Java application that prompts for the person’s information, current year, instantiates an object of class HeartRates and prints the information from that object— including the person’s first name, last name and date of birth— then calculates and prints the person’s age in (years), maximum heart rate and target-heart-rate range.




<strong> </strong>

<strong> </strong>

<strong>Analysis: – 10 points</strong>

(Describe the problem including input and output in your own words.)




This program will prompt for and take the input of a person’s name (first and last), date of birth (year, month, and day), and the current year. This info will be put into an object of type HeartRates. The class HeartRates will have several methods that will get and set the object’s attributes and calculate the following values: age, maximum heart rate, maximum target heart rate, and minimum target heart rate. Once the user has entered the data, the program will print out the person’s name, age, date of birth, maximum heart rate, and their target range heart rate.










<strong>Design: – 10 points</strong>

(Describe the major steps for solving the problem.  Create a UML diagram to accompany your major steps).




<table width="708">

 <tbody>

  <tr>

   <td width="708">HeartRates</td>

  </tr>

  <tr>

   <td width="708">– firstName: String– lastName: String– birthYear: int– birthMonth: int– birthday: int– currentYear: int– minTargetCoefficient: float = 0.5– maxTargetCoefficient: float = 0.85</td>

  </tr>

  <tr>

   <td width="708">&lt;&lt;constructor&gt;&gt; HeartRates( name : String, surname : String, year : int, month : int, day : int, presentYear : int )+ GetAge() : int+ GetMaxHeartRate() : int+ GetMaxTargetHeartRate() : float+ GetMinTargetHeartRate() : float+ SetFirstName( name : String )+ SetLastName( name : String )+ SetBirthYear( year : int )+ SetBirthMonth ( month : int )+ SetBirthDay ( day : int )+ SetCurrentYear ( year : int )+ GetFirstName() : String+ GetLastName() : String+ GetBirthYear() : int+ GetBirthMonth() : int+ GetBirthDay() : int+ GetCurrentYear() : int</td>

  </tr>

 </tbody>

</table>
# LeapYear
leapyear

function leapyear(year)
{
    if((year % 100 != 0) && (year % 4 == 0)||(year % 400 == 0)){
        console.log(year +" is a leap year");
    }
    else{
        console.log(year + "is not a leap year");
    }

}
const year = prompt("Enter a year:");
leapyear(year)

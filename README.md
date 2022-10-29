# javascript-array-
function getDays(date1, date2) {

	var difference_in_time= date2.getTime()- date1.getTime();
	var difference_in_days= difference_in_time/(1000*3600*24);
	return difference_in_days;
}
var date1 = new Date("09/08/2001");  
var date2 = new Date("05/27/2002");  
console.log(getDays(date1, date2))

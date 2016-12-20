var heightJohn= 103;
var heightAbhi= 05;
var ageJohn=25;
var ageAbhi=23;
var scoreJohn= heightJohn+5*ageJohn;
var scoreAbhi= heightAbhi+5*ageAbhi;
var heightSnehitha= 100;
var ageSnehitha=22;
var scoreSnehitha= heightSnehitha+5*ageSnehitha;
if(scoreJohn>scoreAbhi && scoreJohn>scoreSnehitha){
    console.log("john wiins the game with"+scoreJohn+"points");
}
else if(scoreAbhi>scoreSnehitha && scoreAbhi>scoreJohn){
    console.log("abhi wiins the game with"+scoreAbhi+"points");
}
else if(scoreSnehitha>scoreAbhi && scoreSnehitha>scoreJohn){
    console.log("snehitha wiins the game with"+scoreSnehitha+"points");
}
else{
    console.log("it/'s a draw")
}
    

// Complete the rotLeft function below.
function rotLeft(a, d) {

   for(let i = 1; i <= d; i++) {
       
       let number = a.shift();
       a.push(number);
       
   };
   
   return a;

}
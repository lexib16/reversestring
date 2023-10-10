# reversestring

function reverseString(str) {
  let reversedStr = "";
    for(let i=str.length -1;i>= 0;
        i--){
    reversedStr += str[i];
    }
  return reversedStr;
}
const str=("Clarusway Rocks!")
           
const reversedStr=
  reverseString(str);
console.log (reversedStr);

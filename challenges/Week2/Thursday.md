Thursday Answers

----------------------------------------------------------------------------------------------------------------------------------------------
   1. https://www.codewars.com/kata/57faece99610ced690000165 ✨
**COMPLETED**


`function remove (string) {  
  let arr =[]
  for (let i = string.length-1; i => 0; i--){
    if(string[i] != '!'){
      arr.push(string.slice(0,i+1));
      return arr.join('');
    }  
  }
}`




----------------------------------------------------------------------------------------------------------------------------------------------
   2. https://www.codewars.com/kata/5547929140907378f9000039 ✨
**COMPLETED**


`function shortcut (string) {
  const vowels = /[aeiou]+/g;
  return string.replace(vowels, '' );
}`


----------------------------------------------------------------------------------------------------------------------------------------------
   3. https://www.codewars.com/kata/5672a98bdbdd995fad00000f ✨
**COMPLETED**

`const rps = (p1, p2) => {
  if (p1 === p2) return "Draw!";
  var rules = {rock: "scissors", paper: "rock", scissors: "paper"};
  if (p2 === rules[p1]) {
    return "Player 1 won!";
  }
  else {
    return "Player 2 won!";
  }
};`


---------------------------------------------------------------------------------------------------------------------------------------------
   4. https://www.codewars.com/kata/55bf01e5a717a0d57e0000ec✨
**COMPLETED**
----------------------------------------------------------------------------------------------------------------------------------------------
 5. Complete your 1st Core Challenge. This is one of the requirements for the certification, where you'll boost your dev professional-brand. ✨
**COMPLETED**
----------------------------------------------------------------------------------------------------------------------------------------------

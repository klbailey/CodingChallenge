# CodingChallenge 403 error on codespace unable to push from repository
1)
<html>
<body>
  <div>
    <h1>Welcome to my page!</h1>
    <p>
      Here you will find all sorts of interesting information
    </p>
  </div>
  <div>
    <h2>About me</h2>
        <p>I am a developer who loves to create websites and apps. 
          I also enjoy playing video games and reading books 
          in my spare time.</p>
  </div>
</body>
</html>
2)
function sumPositiveNumbers(nums) {
    let total = 0;
    for (let i = 0; i < nums.length; i++) {
      if (nums[i] > 0) {
        total += nums[i];
      }
    }
    return total;
  }
  
  const numbers = [1, -2, 3, -4, 5, -6, 7, -8, 9, -10];
  console.log(calc(SumPositiveNumbers));
  3)
  // let result = 0; here result will always be 0

function add(x, y) {
  result = x + y;
}

function subtract(x, y) {
  result = x - y;
}

function accumulate(x) {
    result += x;
}
const result = add(5, 10);
console.log(result);//15
const accumulate = add(result, 6); //21
console.log(subtract(accumulate, 12)); //9
// add(5, 10);
// console.log(result);
// accumulate(6);
// subtract(6, 12);
// console.log(result);
4)
function isOldEnoughToDrive(age) {
  if (age >= 16) return "Yes"
  return "No";
  
}

  

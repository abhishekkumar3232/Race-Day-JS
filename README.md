# Race-Day-JS


let raceNumber = Math.floor(Math.random() * 1000);

let early = true;
let runnerAge = '55';

if (early && runnerAge > 18){
  raceNumber += 1000;
}

if (early && runnerAge > 18){
  console.log(`Race starts at 9:30 + ${raceNumber}`);
}
else if (!early && runnerAge > 18){
  console.log(`Race starts at 10:30 + ${raceNumber}`);
}
else if (runnerAge < 18){
  console.log(`Race starts at 12:30 + ${raceNumber}`);
}
else {
  console.log(`See the regidtration desk ${raceNumber}`);
}


# MixedMessages
// javascript

// mixed messages
const starter = [
    'lets go to the ',
    'have you seen the ',
    'Who is the real ',
    'Eat your soup ',
    'butter is better '
];
const middle =[
    ' mall ',
    ' goat ',
    ' slim shady',
    ' young man ',
    ' young lady ',
];
const end = [
    ' everybody',
    ' It is amazing',
    ' please stand up',
    ' or no dessert!',
    ' should have eaten more butter'
];
let randSterter = Math.floor(Math.random()*4);
let randMiddle = Math.floor(Math.random()*4);
let randEnd = Math.floor(Math.random()*5);

console.log(starter[randSterter] + middle[randMiddle] + end[randEnd]);

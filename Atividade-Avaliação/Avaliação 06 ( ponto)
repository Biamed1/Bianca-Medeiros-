var myNumbers = [];
var controle = 0;
while (controle < 6) {
    var v1 = Math.floor(Math.random() * 10);
    var v2 = Math.floor(Math.random() * 10);
    var num = v1 * v2;
    if (num <= 60 && num != 0) {
        myNumbers.push(num);
        controle++;
    }
}
for (var cont = 0; cont < 6; cont++) {
    for (var i = 0; i < 6; i++) {
        if (myNumbers[i] > myNumbers[i + 1]) {
            var temp = myNumbers[i];
            myNumbers[i] = myNumbers[i + 1];
            myNumbers[i + 1] = temp;
        }
    }
}
console.log(myNumbers);

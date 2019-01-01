# Challenge-Lined-Paper
This is a  solution to khan Academy's Challenge: Lined Paper
background(255, 255, 247);
stroke(173, 222, 237);



for( var i=0;i<20;i++){
var lineY=20+(i*20);
line(0,lineY,400,lineY);

}
for( var j=0;j<20;j++){
    var c=20+(j*20);
    line(c,0,c,400);
}

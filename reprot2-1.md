void setup() {
size(500, 300);
textSize(100);
}

int i, dir=1, sp=1;

void draw() {
fill(0);
background(255,255,255);
text("andong", i, 200);

if(i>width) dir=-1;
if(i<0) dir=1;
i = i+dir*sp;
}
void keyPressed(){
sp = key-'0'; 
}

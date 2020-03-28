PFont f;
void setup() {

size(800, 400);
textSize(100);
f= createFont("굴림",64);
textFont(f);
}

int i, dir=1, sp=1;

void draw() {
fill(0);

background(255,255,255);
text("안동대 컴공 사랑합니다♡",0,i);

i = i+dir*sp;
}

void keyPressed(){
sp = key-'0'; 
}

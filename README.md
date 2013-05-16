Easing
======

**has an easing image that follows the mouse**


      float x;
    float y;
    float tx;
    float ty;
    float dx;
    float dy;
    float e=.01;
    
    
    
    void setup() {
      size(600,600);
    }
    
    void draw() {
      background(0);
      fill(255,255,0);
      tx=mouseX;
      ty=mouseY;
      dx=tx-x;
      dy=ty-y;
      x+=dx*e;
      y+=dy*e;
      ellipse(x,y,50,50);
    }
        
    
    
    
    

import processing.video.*;
import ddf.minim.*;

Movie myMovie;
Movie myMovie2;

Minim minim;
AudioInput in;

boolean m2isPlaying = false;
int time =0;

void setup() {
  
  size(600, 700);
  frameRate(15);
  // Load and play the video in a loop
  myMovie = new Movie(this, "fire_cupcake.mov");
  myMovie2 = new Movie(this, "fireOut_cupcake.mov");
  println(myMovie2.duration());
  myMovie.loop();
  minim = new Minim(this);
  minim.debugOn();
  
  // get a line in from Minim, default bit depth is 16
  in = minim.getLineIn(Minim.STEREO, 512);
}

void draw() {
  time++;
 
  image(myMovie, 0, 0);
if(50 + in.left.get(30)*50-  50 + in.left.get(30+1)*50 > 50){
    println("Blow out the candle");
        //myMovie.noLoop();
    myMovie2.play();
    m2isPlaying=true;
    myMovie2.jump(0);
  }
  if (m2isPlaying) {
    image(myMovie2, 0, 0);
  }


  /*float md = myMovie2.duration();
   float mt = myMovie2.time();
   if (mt  == md){
   
   myMovie.loop();
   }*/

  if (myMovie2.duration() == myMovie2.time()  ) {
   println(time);
  
    if(time%30==0){
        m2isPlaying=false;
    }
  }

  //   println(myMovie2.duration() + " : " + myMovie2.time());
}



void movieEvent(Movie m) { 
  m.read();
}

void keyPressed() {
  if (key == 'n') {   
    //myMovie.noLoop();
    myMovie2.play();
    m2isPlaying=true;
    myMovie2.jump(0);
  }
}

void stop()
{
  // always close Minim audio classes when you are done with them
  in.close();
  minim.stop();
  
  super.stop();
}


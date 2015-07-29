#Would a sample at any other rate sound as sweet?

An introduction to how our brains interpret sound

Myles Borins

*@thealphanerd*



## Hello there
![hell tharr](content/hello-tharr.gif)


##My name is Myles
![me!](content/me.jpg)


##I currently work at Famous Industries heading up the Famous.org project
![famous](content/famous_logo.png)



##Believe it or not but I got into programming through music + art!


##String Theory
<video width="640" height="480" controls>
    <source src="content/string-theory.mp4" type="video/mp4">
</video>


##The Speaker Bot
<video width="640" height="480" controls>
    <source src="content/speakerbot.mp4" type="video/mp4">
</video>


##The Voxel meter
<video width="640" height="480" controls>
    <source src="content/voxelmeter.mp4" type="video/mp4">
</video>



##It all started with a little device called the monome
![monome](content/monome.jpg)


##The monome introduced me to a programming language 
##called Max / MSP
![max/msp](content/maxmsp.png)


##Max / MSP allows you to access to it's entire internal API through...


#JavaScript


![max4live](content/max4live2.jpg)



##My love of Music and Technology brought me to California
##to study at CCRMA
####The Center for Computer Research in Music and Acoustics
![ccrma](content/ccrma.jpg)


##While at CCRMA I had the opportunity to learn about sound. The math behind it, the physics behind it, how we compute it and most interestingly...


##How our brains interpret it.
![krang brain](content/krang.jpg)



#What is sampling?


![MPC](content/mpc.jpg)


##Technically correct
##but let's dive deeper


![sampling](content/sampling.jpg)


###Sampling is the method of converting an analogue signal to digital data.
### Digital data which can eventually be turned back into an analogue signal.


##While you can sample many things
##Today we are going to talk about sampling sound
![drop the bass](content/dropthebass.gif)


#We sample sound any time we make a digital recording. 
![say what](content/saywhat.gif)


###Unlike an analogue recording 
###which happens in constant time
###A digital recording needs to be represented in sampled blocks


##You can think of a sample as a pixel for sound!
![mind-blown](content/mindblown-at.gif)



##How about a quick primer on some audio slang
![blood sport](content/bloodsport.gif)


#"Sample Rate"
##The number of samples used to represent a second of sound
###A common Sample Rate is 44.1khz


#"Bit Depth"
##The number of bits used to encode a single sample
###A common bit depth is 16bit


#"Codec"
### An algorithm used to encode an audio signal into digital data
### A very common codec is mp3



#Tying this all together


##A CD is encoded using PCM

###At 16 bits / sample
###At 44.1k samples / second

![chumba](content/chumbawumba.png)


##The algorithm involves encoding each channel of sound as a floating point number between -1 and 1
#####NOTE: this is a simplification
#####only talking about the floating point implementation of PCM encoding.


##You can think of a PCM encoding as an array
##Each channel is "interleaved"
###[L0, R0, L1, R1, L2, R2... Ln, Rn]


##


##Many people will refer to this as a lossless encoding as almost no data is lost from the original source


##An mp3, alternatively, does lossy encoding using pychoacoustic heuristics to decide which data is actually important



##What are the limitations of sampling?


![nyquist](content/Aliasing-folding.png)


#You all got that right?


###It is something called the Nyquist limit


###Named after Harold Nyquist

![harold](content/harry.jpg)


##His work was built upon by Claude Shannon
Creating what we know today to be the fields of Sampling and Information theory


![wat](content/wat.jpg)



##The Nyquist Limit


##Your sampling rate dictates the maximum frequency that can be represented in a system
###You can only represent a frequency equal to half the sampling rate of your signal.


##Anything higher ends up aliasing

(we'll come back to this)



#44.1 kHz
###not jigawatz
![flux](content/flux.png)


##This is a standard sampling rate 
##used in audio


![why](content/why.jpg)


![ear](content/ear.jpg)


###The human ear only hears frequencies
###up to around 20 kHz

![freq](content/freq-response.jpg)


##44.1 kHz is an optimization for compression.

It minimizes the amount of data we need to sample.



##Why Sample Higher?


##96 kHz
###would allow you to avoid aliasing


![44.1 vs 96](content/44v96.jpg)



#What does a lower sample rate sound like?


![telephone](content/telephone.jpg)

only 8kHz !!!!!



###Let's go back to the human ear for a second
###and talk about why music works


![ear](content/freq-response.jpg)

Exponential response!


![double](content/double.jpg)


###As frequency grows exponentially
###we experience pitch linearly


![mind-blow](content/mind-blown.gif)


##This was originally discovered by Pythagoras (afaik)
![pyth](content/pyth1.jpg)


##Pythagoras discovered what we now know as the western musical cannon.
![pyth2](content/pyth2.jpg)


#The Chromatic Scale
![chromatic](content/chromatic.png)


##Pythagoras
![pyth2](content/pyth3.jpg)


#The Diatonic Scale
![diatonic](content/diatonic.jpg)


##Pythagoras
![pyth2](content/pyth4.jpg)


##The Circle of Fifths
![circle of fifths](content/circle-of-fifths.png)


##Pythagoras
![pyth2](content/pyth5.jpg)


##The greatest musical achievement in the modern era?


###Phish's Set two Rotation jam 
###Deer Creek Sunday August 10th 1997
![phish](content/phish.jpg)



#Musical notes as we know them 
###(roughly)
####Ask me afterwards about how we actually use fake notes and the church was really upset about us switching


#Have existed longer


#As a means of communication


#THAN THE ENGLISH LANGUAGE


#Let that sink in for second



#Thanks you

##Myles Borins
###@thealphanerd
![surf pup](content/surfpup.gif)
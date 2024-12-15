# rAVen

An all-in-one GUI audio visualizer for UNIX based systems that allows to visualize audio in real-time as well as for any type of audio file with cool visualizations 

## Why

We all know cava exists for this and it works really well however, it does not use the full power of Fast Fourier Transforms (FFT) to enhance on audio visualization.

Aesthetically so far, people have used cava but with rAVen and its current implementation so far, I can see it beating cava in terms of looks easily if we get the implementation of real-time audio sample gather using audio clients like pipewire, portaudio so on..

The idea does not have great ambitions I do agree.

But that's a plus point if you ask me as this does not seem too out of bounds and unfeasible, which is perfect for taking up a project like this

> [!NOTE]
> 
> Would like to add that this started out and will likely remain a > simple passion project of mine as I did not 
> find any great AVs out there that suited for my needs so I tried to make one.
> 

## How 

Have two modes:

1. Real-Time Audio Capture Mode 
    
2. File Audio Capture Mode 

1. **Real-Time Audio Capture Mode**:
```
a. Capturing Real-Time Audio:

This mode would require us to become clients with audio servers like:

1. Pipewire 
2. Portaudio 
3. Alsa 
4. Jack
5. Pulse

These 5 must be majorly supported as that would significantly increase the compatability across all Linux based distributions

There exists documentation (Doxygen mostly) for each audio server with in depth detail that explains how to capture real-time audio samples and utilize them

b. Performing FFT:

Getting the audio samples is probably the hardest part.

Everything after that has either already been implemented or just need to tweak a few things to get it to work with RTAC

c. Displaying the visualization:

This is done using raylib library in C which makes it look pretty cool and dynamic with a lot of freedom of GUI dev
```

2. **File Audio Capture Mode**:
```
This part has already been implemented in rAVen which is up for reference.
```

## Challenges Faced

- A strict and rigid based system to decide which audio server to become a client of to get the audio samples 

- Possibly adding a config file that allows users to set a lot of parameters regarding the FFT visualizations, audio server to choose so on 

- Avoiding getting garbage audio samples from servers in case of other AVs running 

(I noticed this issue while testing pipewire audio samples capture when cava was running in the background: TLDR -> I was getting garbage samples which did not make sense and am still not sure on how to fix it)

## Good to have features

- Powerful user configuration capabilities

- Proper implementation of client-server connection with an audio server 

- Possible enhancements to the raylib UI which is currently implemented 

- Better and more accurate audio visualization using mathematical concepts like low/highpass filtering, so on

contributed by [nots1dd](https://github.com/nots1dd)

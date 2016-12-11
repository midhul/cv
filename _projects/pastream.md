---
layout: index
---

## WebRTC based Peer Assisted Adaptive Video Streaming 

Bachelor's Thesis Project (August 2016 - Present)

A majority of today's online video streaming systems are HTTP based and use adaptive bitrate streaming standards such as Dynamic Adaptive Streaming over HTTP (DASH) and HTTP Live Streaming (HLS). The WebRTC stack has opened up the possibility of creating a purely browser-based and plugin-free mechanism for adding peer assistance to these kinds of systems. In such a system, peers simultaneously watching a video stream can utilize their upload bandwidth to share chunks of the video which they have already fetched with other peers. Undoubtedly, such addition of peer assistance can greatly reduce the load on streaming servers and CDNs. It’s effect on the Quality of Experience (QoE) perceived by the end user is, however, an issue that has not received much research attention. The goal of my project is to answer this question and understand the trade-off between QoE and server offloading in WebRTC based Peer Assisted Adaptive Streaming Systems.

The major determiner of QoE is the Rate Adaptation algorithm employed by the video player. These algorithms are responsible for controlling bitrate of the video segments being fetched based on network conditions. There has been a considerable amount of work in recent literature dedicated to the design and analysis of these algorithms for HTTP-based streaming systems. The addition of peer assistance to these systems makes the problem of Bitrate Control more complex, as the video stream is now fetched from multiple sources. Apart from selecting the right bitrate, it is also necessary to determine how much of the bitrate is to be fetched from each of the peers. Issues like peer churn further complicate the problem. I am working towards tackling this problem as part of my Bachelor's Thesis Project.   

As a first step, I built a platform for experimentation by implementing a working version of a WebRTC based Peer Assisted Live Streaming System. A paper describing my preliminary work has been accepted in the Poster Track of the International Conference on COMmunication Systems & NETworkS 2017 (COMSNETS), and I will be presenting a poster in the conference which is scheduled in January 2017. I am presently trying to experiment with rate adaptation algorithms in this system using MiniNet emulations.

COMSNETS 2017 Poster Paper:
[[Paper in PDF format]]({{site.url}}comsnets-paper.pdf) 
Preliminary Thesis Report:  
[[View report in PDF format]]({{site.url}}pthesis.pdf)
Preliminary Thesis Poster:
[[View Poster in PDF Format]]({{site.url}}thesis-poster.pdf)

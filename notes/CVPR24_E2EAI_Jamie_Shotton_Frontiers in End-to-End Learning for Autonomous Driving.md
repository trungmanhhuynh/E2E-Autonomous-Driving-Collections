
# Summary of talk
## CVPR24 E2EAI | Jamie Shotton: Frontiers in End-to-End Learning for Autonomous Driving

https://www.youtube.com/watch?v=a_q3Efh6-5E&list=PL5ksjZd5b6SJzV-jQz5sqCypT_rrorCVF&index=2

+ believe that AI for driving is next task that AI can surpass humans
+ driving is challenging because of it is safety critical applications
+ Tradditional AV stack is difficult to scale due to
   + information bottleneck: perception task is mainly supervised to predict the bounding boxes, however, are you comforatable driving in the world of just bounding boxes.
     There is much more other information needs to be considered.
   +  Map is expensive to build
   +  More sensors integrated to systems -- more compute- harder to intergrate
+ E2E:
    + looks a lot simpler.
    + Advatages:
        + easy to deploy
        + easy to generalize to different vehicle platforms.
        + dont need high definition map, 
        + works better

## Simulation

 + close the gap between perception and behaviors
 + The world is very rich compared to just rigid bbox, need to simulate full env
 + Controllable over long-tail
 + Models:
        + PRISM-1: scene resconstruction. 
        + Neural rendering
        + WayScenes101: 4D 101 driving scenarios.
     <img width="1010" height="575" alt="Screenshot 2025-07-14 at 10 46 46 PM" src="https://github.com/user-attachments/assets/2cdf11e5-bdac-4346-9e47-f0379ea04301" />
        + Wayve GAIA (2023) - Generative World Model. 
      <img width="1071" height="581" alt="Screenshot 2025-07-14 at 10 49 11 PM" src="https://github.com/user-attachments/assets/9ac8f793-add2-43bd-8a40-3d09c742a05d" />

## Multimodality: 
  - Vision Langugue Model - Generative world model .
  - LINGO-1, LINGO-2, SimLINGO
## Foundation Models for Embodied AI:  
  - Useful to learn from diverset set of videos.
  - Need high amount of data, cant just use internet video.
  - Embodied AI is next frontier.


Everyone needs access to life-saving technology.

eagle eye a real-time system that detects when someone is drawing a concealed firearm from a video stream. 

The goal is catching the pre-attack movement of an aggresor early using body-worn camera(s). 

My hypothesis is pose estimation over time is good enough to spot suspicious "draw" body language. Once a certain threshold has elapsed, we then run a YOLO detector to confirm a gun is present once flagged. 

We're training on real incident footage; mostly bodycam and egocentric videos plus analysis clips. 

I'm deliberately including non-ideal conditions like varying frame rates (CCTV low framerates), transitional lighting, and video quality. 

The project is very much learn-as-I-go: start simple with a frozen pose model and lightweight temporal head, train lots of quick iterations locally, and improve based on what actually works.

Data quality is of th eutmost importance.

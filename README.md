In this project I wanted to make an object detector.
I first used tensorflow and keras and created a detector using a dataset downloaded from minst.
This worked fine but gave me results i was not expecting like saying the place is a barbershop and not telling me what the objects are.
It was a whole image scene predictor essentially.
I then switched to using yolo as the model and that worked out fantasticly.
I plan on trying to use some kind of transfer learning to make it recognize who it is also.
I will do that for when the image is saved. I think a good plan is to have another model that can detect who the person is and use yolo to detect a person.
Using two models together like this I think could work but 
Since the first method was super slow even when I split the image up and did batch detection in parallel I had the wrong model built.
10/24/2024 - work in progress.

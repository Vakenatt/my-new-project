
# Bark detect

Final project for the Building AI course

## Summary

My idea would be an app for pet owners, who want to know if their dog barks, howls or doesn any other loud noises while being home alone. App would also be able to give statistics on a dog's vocalisation.


## Background

An app would be useful for those who want to know if their dos is allright while being home alone. That kind of information is important for evaluation of dog training, making sure if a dog has signs of separation anxiety and be sure your pet doesn't disturb neighbours.
Newest solutions for pet surveillance available today base mostly on video streaming. Older aprroaches include recording a video (or voice) of a pet and spending a lot of time watching (or listening) to the recordings. Video however is not always necessary if you just vant to know if your dog is barking all day long.


## How is it used?

The app requires a sound receiver which can also send information, an older smartphone that a user doesn't utilize anymore may serve as such sound receiver. The receiver captures sounds of the apartment and transmits them to the user's smatrphone, which is being utilised activelly by the user. User's smartphone analyzes sounds and if barking or howling is detected the app generates a notification of the case. Additionally the app provides daily statistics of the points of time, dates and lengths of barking/ howling. 
The app is primary aimed at private dog owners to help them understand how their dog is doing home alone and to make corrections to dog training.

## Data sources and AI methods

The solution is based on machine learning and neural networks. We need a set of dog sounds (barking, howlling and other loud disturbing sounds) and random sounds so that machine learns to distinguish dog sounds from other sounds. It is possible to obtain data from collaborative creative-commons databases, for example [Freesound](http://www.freesound.org). In addition it would be possible to enable users to upload sound recordings of their own dogs that could serve as test data.

## Challenges

The app is thought primary for one dog owners. In case a user has two or more pets in the house the app probably won't be able to tell the difference of which one of the pets is more vocal.
Another challenge is sound recognition when the source of the sound is not close to the receiver. The machine may capture sounds from let's say neighbours' dog if there happen to be a noisy pet.
Privacy concerns arise given the fact that we are dealing with data transfering. User's smartphone can end up in hostile arms.
The app requires a separate sound receiver.

## What next?

Acquiring programming skills and mastering AI methods. Creating a prototype and testing it.

## Acknowledgments

Thanks to [Elements of AI](https://www.elementsofai.com/fi/) and [Building AI](https://buildingai.elementsofai.com/) creators as well as my crazy dog for inspiration.

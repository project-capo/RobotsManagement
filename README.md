#Mobile Robot Management Application for Android-base Device#

The project has two contributors:
- Krzysztof Nawrot ([knawrot](https://github.com/knawrot)) - the owner of this repository
- Michal Lorens ([michallorens](https://github.com/michallorens))
<br>
 
##Brief description
Application serves as a utility to manage a group of robots 
(see [Project Capo](http://project-capo.github.io/) for more details) 
located both inside (specified by the map in *.json* format; by default - AGH, D17, second floor, 
"Laboratorium Robotów") and outside (*Google Maps*).


##Core functionalities

![DTP](https://doc-08-a4-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/keu0kdh7l387nio65gbi222haqk176jq/1425938400000/01104434867096471125/*/0B39XJsM8m6wWUWE5TVJPQnhEa1E)

Application core features are:

1. **Drive to point** - choose the spot (location) on the map to where your current robot should head.
2. **Drawing collisions** - tell the robot to inform about obstacles it detects.
3. **Video Streaming** - lost your robot or ever wanted to feel like you are really driving it? Enable the video streaming!
4. **Operate via controls (arrows)** - let the robot reach its limit by driving it the way you want it.
5. **GPS** - take your robots outside and use the application wherever you want.

<br>

See those features in action:
- "*Drive to point*" + "*Drawing collisions*":    [![VIDEO](https://doc-10-a4-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/o7akbt760pej79443ch7cph7k1gekvfa/1425938400000/01104434867096471125/*/0B39XJsM8m6wWSW0zWEp1VDZMNDA)](https://docs.google.com/file/d/0B39XJsM8m6wWbm5DYjlaOFRHWUk/preview)
- "*Operate via controls*" + "*Video streaming*":    [![VIDEO](https://doc-10-a4-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/o7akbt760pej79443ch7cph7k1gekvfa/1425938400000/01104434867096471125/*/0B39XJsM8m6wWSW0zWEp1VDZMNDA)](https://drive.google.com/file/d/0B39XJsM8m6wWeXlEVUZQY2hkbkk/preview)
- "*GPS*":    [![VIDEO](https://doc-10-a4-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/o7akbt760pej79443ch7cph7k1gekvfa/1425938400000/01104434867096471125/*/0B39XJsM8m6wWSW0zWEp1VDZMNDA)](https://drive.google.com/file/d/0B39XJsM8m6wWUktpSmR5dU55c0U/preview)

##Specification

#####Target device
Despite the variety of Android-based devices, 
the best results occur when running the application on a tablet
(tested on *ASUS Transformer TF101G*).

#####Target OS
Application is only compatible with Android 4.0 or higher.

#####Other requirements
- robots and a device within the same WiFi connection
- Google Play Services installed on a device



##How to run an application

There is no standalone version (*.apk*) for this project. 
If you want to run it on your device, you frist need to *[set up your workspace](#how-to-set-up-a-workspace)*
and then compile it on your own.



##How to set up a workspace

In order to set up a workspace you first need to download ADT ([Android Development Tools](http://developer.android.com/tools/help/adt.html)). Once you integrate your IDE with ADT you will need two aditional dependencies (imported as separate projects - if using Eclipse):
- [Android Support Library](http://developer.android.com/tools/support-library/index.html) - download via Android site
- [Google Play Services](https://developer.android.com/google/play-services/index.html)

Please also note, that the application uses Android SDK v14.

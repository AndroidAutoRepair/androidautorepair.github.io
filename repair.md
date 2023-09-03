# My Android Auto app isn't working
## Your ultimate guide for Android Auto debuging

I drive everyday, and most of time, I don't need android auto. But from time to time, I do need android auto for navigation.
Unfortunately, android auto is not alway stable. During last year, I've spent a few month debuging and testing why it's not working.
After buying two Pixel Phones and tring a lots of times with different app combinations, I've found that the problem is linked to Google play service.
As Google Play Service  is a service you can not disable, it's not possible to develop another app to make android auto working.

# The first step is to make sure that your phone's android auto was enable on your head unit
## normally, this is under setting -- android auto

But I've finally found an option to make android auto working, which is made possible  by Auto Companion App [Auto Companion](https://play.google.com/store/apps/details?id=com.ingenika.autocompanion).

After running Auto Companion App, disconnect your phone from car, reconnect it to the car, normally, should solve the problem.

Sometimes, with big version upgrade from Android auto, this approach is not working, you can try forget the bluetooth device on your car, and pair the phone again.

If this step is not working, uninstall the update of android auto app, repeat the previous procedures again. 

And if you are confortable at disable google play service update. There is an option to make android auto working, without to run auto companion app very often:

Find a version of google play service that is working, disable google play store. So, because google play service is parked at that version, it will not be upgraded and not causing problems with android auto.

Here is a video of using Auto Companion Pro App, which is an improved version of Auto Companion App on [youtube](https://www.youtube.com/@Kluane)
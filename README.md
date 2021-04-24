## Kodular Professional App Template

Hi Everyone

Reason for posting the professional looking template which is not just design but actually works on click events is going to help newbies to test the idea as fast as possible. I faced similar problem and it took me 7 days of work to make this draft template which can be customized to launch your idea in couple of hour.

I wish such type of template should be part of Kodular create where people not proficient in design and coding can immediately work upon it. Normally people give up if they stuck on simple thing. For example Google Signup is a very common but too much work require to make that screen working without bugs. So here is my little contribution and which is free for all. If you ever think this template helped you to launch your idea then feel free to sponsor me a beer :).

Professional App Working Template Design and Click Events to put your code:

1. Splash screen with lotty
2. Onboard or introduction flipper screen
3. Google & Firebase sign up screen
4. Cool Home Screen
5. Cool Sub Screens
6. List View Screens for Followers, Leaderboards, Shopping, Reward Points
7. Cool Sidebar with procedure to copy on all screens

### Screenshot

![CoolAdmin admin dashboard template preview](https://github.com/vinodkotiya/kodular_professional_app/blob/main/Screenshots/Screenshot_2021-03-31-11-22-14-363_com.tester.jpg)


No custom extension used.

Important point for your Google Signup to work.
Configure your firebase and get json file to upload on assets. So many youtube tutorials available. If don’t want to test with sign up simply delete the sign up screen from project and remaining screen will work perfectly for further customization. You can check sign up functionality in apk. Tou have to add google-services.json with ensuring following in your json file top section:
“project_info”: {
“project_number”: “123456789”,
“firebase_url”: “https://your-projekt-id.firebaseio.com”,
“project_id”: “your-projekt-id”,
“storage_bucket”: “your-projekt-id.appspot.com 1”

This firebase_url line is missing if you download json from firebase and it wasted my time to figure it out. So you have to add it manually.

For any further help DM me and hope this free template will work for you. Cheers.

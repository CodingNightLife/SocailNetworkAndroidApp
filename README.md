# SocailNetworkAndroidApp
A social networking android application with backend on java and mysql.<br>
**The database and the scripts are uploaded on AWS EC2 Instance**

Here is the download link to the app. Feel free to give any sort of feedbacks.<br>
https://drive.google.com/open?id=1zwQ0FS6x_p_gRn5qTj6Hh9dqZ3yIpfym

The scripts are written in jsp and use apache tomcat server to run.

# Project Explained
There are basic login and signup activities with client side validations.
<p><img src="https://github.com/shivamvk/SocailNetworkAndroidApp/blob/master/images/Screenshot_20180704-154804.jpg" height="400px" width="240px">
<img src="https://github.com/shivamvk/SocailNetworkAndroidApp/blob/master/images/Screenshot_20180704-154812.jpg" height="400px" width="240px"></p>

After signing up there is a **SelectProfilePicture** activity.<br>
All the images are stored in the **firebase storage** and the link to them is stored in the mysql database<br><br>
And then there is this home activity which have three **fragments** with a **tablayout with viewpager**.<br>
The three fragments are **FeedFragment**, **FriendRequestsFragment** and **ProfileFragment**.
<br>
<img src="https://github.com/shivamvk/SocailNetworkAndroidApp/blob/master/images/Screenshot_20180704-154836.jpg" height="400px" width="240px">
<img src="https://github.com/shivamvk/SocailNetworkAndroidApp/blob/master/images/Screenshot_20180704-154845.jpg" height="400px" width="240px">
<img src="https://github.com/shivamvk/SocailNetworkAndroidApp/blob/master/images/Screenshot_20180704-154851.jpg" height="400px" width="240px">

You can upload new post with images or without them the **FeedAdapter** will handle it accordingly and diplay the feed.<br>
While uplaodng the post you can select if you want or not to attach an image with it.<br>
<img src="https://github.com/shivamvk/SocailNetworkAndroidApp/blob/master/images/Screenshot_20180704-161537.jpg" height="400px" width="240px"><br>
You can send **friend request** to different people.<br>
And you can also search for users with the **search option in action bar**.<br>
<img src="https://github.com/shivamvk/SocailNetworkAndroidApp/blob/master/images/Screenshot_20180704-154903.jpg" height="400px" width="240px">

**Ps : I am still working on it to make it better. Any forks are welcomed  ^_^**

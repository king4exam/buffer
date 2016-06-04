# buffer
Auto post to social media using Buffer API and codeigniter
=========================

Usage:
------------
1. Just copy those two files from library to your codeigniter library folder
2. Replace <YOUR_CLIENT_ID> with your actual buffer client id
3. Replace <YOUR_CLIENT_SECRET> with your actual buffer client secret
4. Replace <YOUR_CALLBACK_URL> with http://www.yourdomain.com/callback
 
------------------------
Now in any controller function 
---------------------------
1. $this->load->library('MyBuffer') //load the library
2. $b=new MyBuffer() // Create a object of that class
3. $b->sendUpdate($title,$link,$pictureurl,$thumbnailurl);

    


# HelpMe: Support Service
An iOS mutual help application. 

HelpMe was born from the idea that the world always had two categories always interchanging: people who need help and people who want to help.
    
HelpMe is an application for mutual support between users. It gives the users the possibility to contact an 'Helper' and talk anonimously about his/her problems.
This can be done in three ways:

    - Through the HelpLine that was opened on a Whatsapp Professional account;
    - Through a dedicated email;
    - Through the live anonymous chat provided by the application;
    
    
![1242x2208bb](https://user-images.githubusercontent.com/1354168/155526706-13c412f5-7b87-4468-b80a-ac7235d10c58.png)
![1242x2208bb (4)](https://user-images.githubusercontent.com/1354168/155526712-f0ca8eba-c6f3-418f-8e3e-07d69b725429.png)
![1242x2208bb (5)](https://user-images.githubusercontent.com/1354168/155526713-b6b8541e-a6c6-47a7-b75b-866ae7f15c88.png)

The app's Backend was on Parse Platform by Facebook (now dismissed) and the realtime chat was possible thanks to dedicated Listeners and to in-app messages integration. 
All the chats were archived on the server using AES cryptography. 

HelpMe: Support Service has been on the App Store from 2017 to 2020 when I removed it after Heroku migrated its services from MongoDB mLab. It reached 500 users from Italy, Germany and France and a total of 20 registered and verified Helpers.  

This code includes: 

    - <img src="https://cdn-icons.flaticon.com/png/128/586/premium/586293.png?token=exp=1646817942~hmac=75ff0e2b7ec2802a953a386b43db96d8" width="15px"> Database access with Parse Platform (deployed on Heroku);
    - <img src="https://cdn-icons.flaticon.com/png/128/5165/premium/5165249.png?token=exp=1646818176~hmac=45b54ea619914eee3a72ad1d8cb49228" width="15px"> Live location tracking (kept private) in case of emergency;
    - <img src="https://cdn-icons-png.flaticon.com/128/1060/1060387.png" width="15px"> User authentication;
    - <img src="https://cdn-icons.flaticon.com/png/512/4755/premium/4755434.png?token=exp=1646818207~hmac=b571a92e24259c3ad540ad7b2e967a70" width="15px"> AES Cryptography;
    - <img src="https://cdn-icons-png.flaticon.com/128/2950/2950711.png" width="15px"> Live chat (developed without external libraries);
    - <img src="https://cdn-icons-png.flaticon.com/512/1182/1182769.png" width="15px"> Push notifications (<b>device to device</b>);
    

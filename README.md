# Augmental-Reality(nk-codes)

AZURE project URL :- https://imageaugmentation.azurewebsites.net/

This project is on AR which is for :-
1) feature detection :- In this , image detection is done in as "dl.png"
2) feature matching :- now , we will find the match the " dl.png " with " dl_from_webcam.jpg " for feature matching .
3) IMAGE augemtation :- and finally it will detect that image ("dl.png") and will match and mask that image with " mask.jpeg " .

AZURE service used :- WEB APP
Explanation :- Azure Web Apps are Microsoft's offering to cloud to host web applications. It allows developers to focus on delivering business values rather than consuming time on Sever updates or OS patches. Interestingly, applications built on Java, PHP, Python or Node. js can also be deployed on web apps

I have done all the project in python language and done following steps to finally deployed my project using Azure "Web App" :-

1) First i logged in with my student id into Microsoft Azure using the helpful bot in Azure site.
2) then I clicked on + Create a resource and then Clicked on Web App to create a new Web App resource.    ![image](https://user-images.githubusercontent.com/89216667/153861389-251776c2-e27f-4cde-aa66-b61a0ca9170e.png)

3) Then I named the resource group as "augmental-reality" and  app service as "ImageAugmentation" ,Runtime Task as "python 3.8" and done all default .![image](https://user-images.githubusercontent.com/89216667/153861556-7aec7414-fc4d-4103-948a-ffe8278f6fc6.png)

4) And I clicked on Review + create and finally Review all the details entered and then clicked on Create.
5) After clicking on create it will start deploying the Web App resource.
6) Once deployment is complete the portal will display: ![image](https://user-images.githubusercontent.com/89216667/153861629-d35cd7fb-73c0-4df7-aafd-d54000fe9a24.png)

7) Then go to the resource group in which the Web App was created and click on the created Web App.
8) Finally, I CLick on Deployment Center and filled the following details and save and starts the service. ![image](https://user-images.githubusercontent.com/89216667/153861995-c4342a8f-6aff-4d2f-b7d7-203bbe48effa.png)

9) After a while, in Github's "Action" section, there is the following queues done. and yup, all is done.
![image](https://user-images.githubusercontent.com/89216667/153861656-15a9ff72-0394-4565-ae51-4add5c039624.png)
![Uploading image.png…]()









run:-
just run according to the steps mentioned above. But before you need Opencv and numpy as well .

Note:- Download dl.png in your mobile and then run all mentioned above .
after that camera will open and use that dl.png image and see the magic.

OUTPUT images:-
Feature detection pic:-
![image](https://user-images.githubusercontent.com/89216667/153774873-bb3f971b-10bc-4309-a055-74b92f5e0202.png)

Feature matching pic
![image](https://user-images.githubusercontent.com/89216667/153774892-1212f642-c2b0-4e5f-9c9a-f3b6ca8a1daa.png)

Image augmentation:-
![image](https://user-images.githubusercontent.com/89216667/153774943-c5931795-3d58-402a-9bea-d15b150cd069.png)



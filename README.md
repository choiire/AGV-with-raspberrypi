# AGV-with-raspberrypi

# Profile
It's an AGV that runs on a raspberry pie. Recognize the QR coordinates with the lower camera and correct the orientation with the front camera.

The server used the Heroku site, and the app production used Kodular.

https://www.dropbox.com/s/7nusbbvzvgehb70/1%EC%A1%B0%20%EB%B0%9C%ED%91%9C%20%EC%98%81%EC%83%81.mp4?dl=0

https://www.dropbox.com/s/0pm9ut13t3pq5ab/%EC%A2%85%ED%95%A9%EC%84%A4%EA%B3%84%20%EC%98%81%EC%83%81%EB%B0%9C%ED%91%9C.mp4?dl=0

# things to improvements

1. Replace the pie cam with a wide-angle lens
(Due to the actuator space above, the lens is narrow, so the QR coordinate recognition rate is low)

2. DC motor gear ratio greater torque than 1/100
(When AGV lifted the item, I felt that the 1/100 gear ratio I used was not strong enough)

3. When QR coordinates are recognized by Pi-Cam, Pi-Cam calculates the slope of the QR picture and adds an angle correction function
(Limited angle correction with Huskylens sensor in front)

4. Highlight bottom ballwheel offset
(In the cad file I posted, two ball wheels and two wheels are designed to fit perfectly with the ground, so if the floor is uneven, it doesn't move. So I removed one of the ball wheels in front of AGV)

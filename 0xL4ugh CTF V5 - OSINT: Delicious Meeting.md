## Challenge 

**Delicious Meeting**

Willow1124 is planning to meet Ken to enjoy their favorite food. The uploaded files include a picture of Willow1124’s hometown. Use Google Maps at all times.

Your task is to figure out the email address of the place where they met.

Flag Format: 0xL4ugh{0xL4ugh@gmail.com}

Author: Zwique


![Challenge image](https://github.com/0x8366/assets-images/blob/main/sushi2.png?raw=true)

## Methodology/Solution

The challenge image was just the starting point here to get a general location: Stockholm, Sweden. From there used the tool Sherlock to discover Willow1124's blog at: https://willow1124.blogspot.com

![Challenge image](https://github.com/0x8366/assets-images/blob/main/sushi5.png?raw=true)

![Challenge image](https://github.com/0x8366/assets-images/blob/main/sushi4.png?raw=true)


On the blog there is another image which is of Stockholm's Central Station. A few key sentences stood out in the blog: **I was meeting Ken to eat sushi**, **the name of the place we’re meeting up at consists of four parts**, and **I’d gotten off one stop too early** 

Because it says they gotten off one stop early, I traced stops along train/subway routes:

![Challenge image](https://github.com/0x8366/assets-images/blob/main/sushi1.png?raw=true)

From there we can see that the stop before Stockholm Central is Hötorget subway station. I looked around for a sushi restaurant that was four parts and came across this place: `Soyokafe Sushi and Ramen`
https://www.soyokaze.se/soyokafe

This indeed was the correct location:

![Challenge solve](https://github.com/0x8366/assets-images/blob/main/sushi3.png?raw=true)

**Flag:** `0xL4ugh{kafe@soyokaze.se}`


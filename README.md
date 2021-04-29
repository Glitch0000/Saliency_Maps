# Saliency_Maps
Like class activation maps, saliency maps also tells us what parts of the image the model is focusing on when making its predictions.  
The main difference is in saliency maps, we are just shown the relevant pixels instead of the learned features.
We can generate saliency maps by getting the gradient of the loss with respect to the image pixels. 
This means that changes in certain pixels that strongly affect the loss will be shown brightly in our saliency map.

Input: 
![image](https://user-images.githubusercontent.com/64538407/112746145-cdd3e280-8fb5-11eb-9678-8745f2ea32d3.png)


Output:

![image](https://user-images.githubusercontent.com/64538407/112746152-d7f5e100-8fb5-11eb-8e65-f7dcf4721747.png)

Output with the origional image:

![image](https://user-images.githubusercontent.com/64538407/112746163-e5ab6680-8fb5-11eb-8aff-5d1ab8338732.png)

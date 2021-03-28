# Saliency_Maps
Like class activation maps, saliency maps also tells us what parts of the image the model is focusing on when making its predictions.  
The main difference is in saliency maps, we are just shown the relevant pixels instead of the learned features.
We can generate saliency maps by getting the gradient of the loss with respect to the image pixels. 
This means that changes in certain pixels that strongly affect the loss will be shown brightly in our saliency map.



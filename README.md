# Computer Vision And Generative AI
[image1]: ./results/image1.png
[image2]: ./results/image.png
[image3]: ./results/image2.png
[image4]: ./results/AppView.png
[image5]: ./starter/car.png
[image6]: ./starter/dragon.jpeg
[image7]: ./results/image3.png
[image8]: ./results/image4.png
[image9]: ./results/image5.png
[image10]:./starter/monalisa.png
The Segment Anything Model (SAM) is used to construct a mask around the specified object, and the most accurate mask is chosen. Creating a simple app that allows users to select a subject and then change its background, or to keep the background and change the subject. The user is given the option of accepting the result or refining the mask with more points. Once the mask is complete, the user enters a text description (and perhaps a negative prompt) to choose a new background for the selected object, which is generated using a text2image diffusion model and shown as the final image.

## Libraries
Include all items used to build project.  
* pytorch
* diffusers 
* transformers
* gradio
* numpy
* PIL


## Results Achieved 
- You can find original images in the `starter` folder and the generated images in the `results` folder.  

![image4]  
Generate image     |  Generate image |  Generate image
:-------------------------:|:-------------------------:|:-------------------------:
![][image1]                | ![][image2]               |![][image3]  
![][image7]                | ![][image8]               |![][image9]  

- Demonstrate proficiency in loading and using the Segment Anything Model (SAM) to segment objects.
- Demonstrate proficiency in loading a pretrained AutoPipelineForInpainting from the diffusers library.
- Use the interavtive app, showing they understand how to run SAM to segment the subject and substitute the background or the subject with text prompts.
## License

[License](LICENSE.txt)

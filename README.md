# VirtualClothingTryOn
Virtual Clothing Try On Gradio App

# Virtual Clothing Try On Demo

This is a Gradio web application that allows users to virtually try on clothing. By uploading an image of a garment and an image of a person, the application will generate a final image showing the person realistically wearing the garment. This demo utilizes the Google Gemini AI model for image generation.

## Overview

Have you ever wondered how a specific piece of clothing would look on you or someone else? This application provides a fun and easy way to visualize that! Simply upload images of the clothing item and the person, and let AI do the rest.

## Key Features

* **Realistic Virtual Try On:** Generates an image of a person wearing a chosen garment in a realistic manner.
* **Simple User Interface:** Built with Gradio, providing an intuitive and easy-to-use web interface.
* **Powered by Google Gemini AI:** Leverages the power of Google's advanced image generation model for high-quality results.
* **Example Images Provided:** Includes pre-loaded examples to quickly get started and see the app in action.

## How to Use

1.  **Upload Garment Image:** Click on the "Imagen de la prenda" (Garment Image) upload box and select an image of the clothing item you want to try on.
2.  **Upload Person Image:** Click on the "Imagen de la persona" (Person Image) upload box and select an image of the person who will be "wearing" the garment.
3.  **View the Result:** The application will process the images and display the generated "Imagen final" (Final Image) showing the person wearing the uploaded garment.
4.  **Try Examples:** You can also click on the example images provided below the upload boxes to quickly test the application with pre-selected images.

## Examples

The application includes the following example image pairs to demonstrate its capabilities:

| Garment Image                                                                                                                                | Person Image                                                                                                                                |
| :------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------ |
| [Image of a blue jacket](https://image.uniqlo.com/UQ/ST3/WesternCommon/imagesgoods/477795/sub/goods_477795_sub14_3x4.jpg?width=400)      | [Image of fashionable duo in stylish pleated outfits](https://www.pexels.com/photo/fashionable-duo-in-stylish-pleated-outfits-31422876) |
| [Image Linen Blend Dress with a V Neck Gingham print](https://image.uniqlo.com/UQ/ST3/WesternCommon/imagesgoods/477218/sub/goods_477218_sub14_3x4.jpg?width=400) | [Image of a woman smiling](https://www.pexels.com/photo/woman-wearing-white-and-blue-floral-dress-carrying-brown-handbag-3195980/)    |
| [Image of black pants](https://image.uniqlo.com/UQ/ST3/WesternCommon/imagesgoods/463182/sub/goods_463182_sub14_3x4.jpg?width=400) | [Image of a man looking away](https://www.pexels.com/photo/man-standing-on-seashore-2907034)      |
| [Image of a blue dress](https://image.uniqlo.com/UQ/ST3/WesternCommon/imagesgoods/474056/sub/goods_474056_sub14_3x4.jpg?width=400)  | [Image of a woman in a red dress](https://www.pexels.com/photo/photo-of-woman-wearing-red-dress-1644898/)    |

*(Note 📝: You might need to update these links if you are hosting the images locally or using different examples.)*

## Dependencies

The application relies on the following Python libraries:

* `google-generativeai`
* `Pillow (PIL)`
* `gradio`

You can install these libraries using pip:

<img width="488" alt="Screenshot 2025-04-05 at 21 06 14" src="https://github.com/user-attachments/assets/1ca67b30-a7c3-4d77-88b9-a6418deb2913"/>




# GAN-Implementation-on-Fashion-MNIST-dataset

This repository contains code to generate new images from normal distribution using GAN (Generative Adversial Networks) architecture and training using FashionMNIST dataset.

GAN architectures comprises of :
1. Generator - Generates images such that the discriminator finds it hard to discriminate
2. Discriminator - Distinguishes between real and fake images

## Project Structure

The project is organized as follows:

1. Import Dependencies and Data  
2. Visualize Data and Build Dataset  
3. Build Neural Network<br>
   3.1. Import Modelling Components<br>
   3.2 Build Generator<br>
   3.3 Build Discriminator

4. Construct Training Loop<br>
   4.1 Setup Losses and Optimizers<br>
   4.2 Build Subclassed Model<br>
   4.3 Build Callback<br>
   4.4 Train<br>
   4.5 Review Performance<br>
   
5. Test Out the Generator<br>
   5.1 Generate Images<br>
   5.2 Save the Model

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/rachitdani/GAN-Implementation-on-Fashion-MNIST-dataset.git
```

2. Navigate to the jupyter notebook file:

```
cd GAN-Implementation-on-Fashion-MNIST-dataset/GAN_on_FashionMNIST_dataset.ipynb
```

3. Create an Folder named images manually or via code :

```
mkdir images
```

4. Run the Notebook file


## Usage

Once you have completed the required steps you can generate new images based on the FashionMNIST dataset using the GAN architecture. The images will be availbe in the images folder and will be generated after each epoch.

I have trainied the architecture only upto 10 epochs but you can train till upto 2000 epochs to generate better images.

## Screenshots

The kind of similar images our GAN architecture should generate from normal distribution
![Screenshot 2023-11-07 at 10 57 14 PM](https://github.com/rachitdani/GAN-Implementation-on-Fashion-MNIST-dataset/assets/79761144/8707bf30-fc2b-4e78-80b8-aef391a5b0ba)

Generator generated images after 1 epoch from normal distribution
![Screenshot 2023-11-07 at 10 58 51 PM](https://github.com/rachitdani/GAN-Implementation-on-Fashion-MNIST-dataset/assets/79761144/8cfad27f-e98f-4e2a-a4b3-f5eca2a53a65)


Generated Images after training for 10 epochs from normal distribution

![Screenshot 2023-11-07 at 10 56 12 PM](https://github.com/rachitdani/GAN-Implementation-on-Fashion-MNIST-dataset/assets/79761144/a4b7c370-8200-492e-983a-bbe5f2ebb77c)



## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Description of your changes'`.
4. Push your changes to your fork: `git push origin feature-name`.
5. Create a pull request on the original repository.



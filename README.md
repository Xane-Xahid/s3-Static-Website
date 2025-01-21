# My s3 project- Hosting a static website

This repository contains the code for a simple and elegant static website. The website features a clean layout, a welcoming message, and a visually engaging gallery with hover effects. It is hosted on an Amazon S3 bucket for reliable and scalable access.

## Features

- **S3 Hosting**: The website is hosted in the S3 bucket `mywebsite-2434duej3j`, making it accessible globally with high availability.
- **Responsive Design**: The layout adjusts to different screen sizes for a great user experience on desktops, tablets, and mobile devices.
- **Gallery Section**: A stylish image gallery with hover effects for a dynamic look and feel.
- **Clean Aesthetic**: Minimalistic design with soft colors and simple typography.
- **Interactive Hover Effects**: Smooth animations enhance the gallery images when hovered.

## Technologies Used

- **HTML5**: The structure of the website.
- **CSS3**: For styling, layout design, and animations.
- **AWS S3**: Hosting the static website.

## File Structure

```
.
├── index.html    # Main HTML file
├── apple.jpeg    # Image of an apple
├── papaya.jpeg   # Image of a papaya
├── pineapple.jpeg # Image of a pineapple
```

## How to Access

The website is live and can be accessed via the S3 bucket's public URL:
```
http://mywebsite-2434duej3j.s3-website-<AWS-region>.amazonaws.com
```

*(Replace `<AWS-region>` with the region where your S3 bucket is hosted.)*

## How to Use Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Open the `index.html` file in any web browser:
   ```bash
   open index.html
   ```

## Gallery Preview

The gallery displays images with a modern layout and smooth hover effects:
- **Apple**
- **Papaya**
- **Pineapple**

Each image is offset slightly for a dynamic staggered look.



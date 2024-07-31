# Project Create a Form, Setup and Implementation

## 🛠️ Step 1: Set Up and Planning

1. **Initialize Your Git Repository**:

   - Start by creating a new git repository. You can refer to past projects for guidance if needed.
   - Run `git init` to initialize a new repository in your project directory.

2. **Set Up HTML and CSS Files**:

   - Create your basic HTML and CSS files and link them together. Add some dummy content to ensure everything is connected correctly.

3. **Download Design File**:
   - Obtain a high-resolution copy of the design file you will be working with. Familiarize yourself with the layout to guide your HTML structure.

## 📦 Step 2: Gather Assets

1. **Background Image**:

   - Find and download a high-quality background image for your design. You can use the design's reference from [unsplash.com](https://unsplash.com) or choose your own.
   - Be sure to credit the creator of the image.

2. **External Font**:

   - Choose a font for the ‘logo’ section. The design uses Norse Bold, but you can select any font you prefer.
   - Add the font to your project using a link or `@font-face` rule in your CSS.

3. **Image Sidebar**:
   - Use an image for the sidebar. The provided design uses an Odin logo, but you can use a different image if desired.

## 📌 Step 3: Implementation Tips

1. **Scaffold the Structure**:

   - Start by setting up the basic structure of the page. Focus on getting the layout in place before working on the individual sections.

2. **Background and Overlay**:

   - The area behind the “ODIN” logo uses a semi-transparent background color to enhance text readability. Apply this using a dark, semi-transparent background color.

3. **Button Styling**:

   - Use the color `#596D48` for the ‘Create Account’ button. This color matches tones found in the background image.

4. **Input Field Borders**:

   - Style the input fields with a light border (`#E5E7EB`). Use the `:invalid` pseudo-class to apply a red border for invalid inputs.
   - Use the `:focus` pseudo-class to add a blue border and subtle box-shadow for selected inputs.

5. **Responsiveness**:
   - Do not worry about mobile responsiveness for now. This will be covered in later lessons.

## 📋 Notes

- Validating that the password fields match each other will require JavaScript, which is covered in a future lesson. For now, focus on validating each field separately.

## 📑 Example Code

Here is an example of how to implement some of the styles:

```css
input:focus {
  border: 1px solid rgb(98, 98, 238);
  box-shadow: 5px 5px 7px 0px rgba(0, 0, 0, 0.29);
  outline: none;
}

input:invalid {
  border: 1px solid rgb(230, 22, 22);
  box-shadow: 5px 5px 7px 0px rgba(0, 0, 0, 0.29);
  outline: none;
}
```

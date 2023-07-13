CSS, advanced

For this project, you will focus on the CSS and the style of the page.
This designer file will be available on Figma 
What is CSS?
CSS stands for Cascading Style Sheets. It is a style sheet language used to describe the presentation of a document written in HTML or XML. CSS is used to define the layout, colors, fonts, and other visual aspects of a web page.

How to add style to an element?
To add styles to an element using CSS, you can use various methods:
Inline Styles: You can use the style attribute directly in an HTML element to define its style. For example: <div style="color: blue;">This is a blue div.</div>
Internal Stylesheet: You can define styles within the <style> tag in the <head> section of your HTML document. For example:
<style>
  .my-class {
    color: blue;
  }
</style>
External Stylesheet: You can create a separate CSS file with .css extension and link it to your HTML document using the <link> tag. For example:
<link rel="stylesheet" type="text/css" href="styles.css">

What is a class?
In CSS, a class is a way to group multiple elements that share similar styles. You can define a class by using the dot notation (.) followed by a class name. For example:
.my-class {
  color: blue;
}

https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/4/1f4cd63ecc3a8c03b0f4309b74aca179e225aabf.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230713%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230713T190130Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4f8e4f0cd8222a8ec31feee12ea92be78d8aaa3e04f6f2dea8303db8f73fbb1c
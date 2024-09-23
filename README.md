# exercise-valentinos-express-site

## Learning Goals

Upon completing this exercise, you will be able to:

- Set up an Express.js server
- Serve static HTML, CSS, and image files using Express.js
- Organize static files in a public directory
- Understand the basics of routing in Express.js

## Introduction

Welcome to Valentino’s — an award-winning Italian Restaurant! 🥇

Until now, customers have only discovered Valentino’s via word-of-mouth. But times are changing, and Valentino’s wants to expand operations by building an online presence.

Your task is to build a website to help showcase Valentino’s to the public!

The website should consist of three pages:

- Homepage — `index.html`
- Menu  — `menu.html`
- About Us — `about.html`

You should use Express.js to serve static files to the browser (client), including:

- HTML files
- CSS file
- Images

If you do this right, you could be eating at Valentino’s FREE FOR LIFE! 🍝  🍕 🦞 😋


## Getting Started

1. Fork the repository
2. Clone the repository to your computer
3. Open the repository in VS Code
4. Start the Live Server in VS Code
5. Follow instructions

## **Instructions**

Welcome to Valentino’s kitchen! 🍝

Make yourself at home — you can put your laptop on the Chef’s table over there. 💻
Now let’s roll our sleeves up and get to work! 👨🏻‍🍳

### **Task 1**

After forking and cloning the repository, you will find an empty Node.js project. We have already initialized it, so you should see an existing `package.json` file

Your first task is to **install Express** and **set up the project** **to follow the structure below**:

valentinos-website/
│
├── public/
│   ├── css/
│   │   └── styles.css
│   ├── views/
│   │   ├── index.html
│   │   ├── menu.html
│   │   └── about.html
│   └── images/
│       └── (add your images here)
│
├── app.js
├── package.json



### Task 2

Open `app.js` and set up an Express Server to listen to incoming HTTP requests.

<aside>
ℹ️

Remember, you can use port 3000.

If you receive an error that the port is already in use, then it means that you have an existing instance of an Express Server already running on the same port.

You need to locate it and terminate the Express Server first.

</aside>

Set up your Express Server to **serve static files** from the `public` directory. 

### Task 3

Open up `index.html`  and create a basic homepage that welcome’s users to Valentino’s.

Use HTML elements such as Headings, Paragraphs and Lists to create some visual hierarchy within your content.

Ignore styling for now. You can tackle that later.

### Task 4

Open up `menu.html` and maintain a basic menu for Valentino’s Italian Restaurant.

Use images to represent the items on the menu!

Store your images in the `public/images` directory and link to them in your HTML file.

### Task 5

Open `about.html` and write a short description about Valentino’s Award Winning Restaurant.

If you’re out of ideas, you could consider mentioning:

- When Valentino’s was founded
- The people or person behind Valentinos
- Where the inspiration for the menu came from

Get creative! There’s no right or wrong answer here. 🙂

### Task 6

Now that you’ve created your `index.html` , `menu.html` and `about.html` pages, let’s serve them to the client and make them available to the user!

Your task is to **create a route** for each page in `app.js` .

You should be able to access each page at the following URLs via your web browser:

- `localhost:3000/index`
- `localhost:3000/menu`
- `localhost:3000/about`

### **Bonus Task: Make your site look good!**

If you made it this to point, you should have successfully served static pages for Valentino’s site.

Well done! 👏🏻

Now let’s make Valentino’s website look good!

Your job is to implement styling in `styles.css` .

Don’t forget to link your CSS stylesheet to your HTML files.

Once you’ve implemented styling, test it out in the browser!

Valentino can’t wait to see the end result!! 🙂



## **Submission**

When you've completed the exercise:

1. Run the following commands:

```jsx
git add .
git commit -m "Completed Valentino's Express Site"
git push origin main
```

1. Create a Pull Request and submit your assignment.

Happy coding! 🙂

## Frequently Asked Questions (FAQs)

<details>
  <summary>How can I embed images into my HTML file that are stored in the /images folder?</summary>
 
You can embed images into your HTML file using the `<img>` tag and setting the `src` attribute to the relative path of the image within the `/images` folder. 

For example:

`<img src="/images/your-image.jpg" alt="Description of the image">`

This will display the image stored in the `/images` folder.

When linking to files in your `public` directory, you should use paths relative to the `public` directory without including the public part in the path hence why it’s just `/images`
 
</details>

<details>
  <summary>How do I link my HTML page to an external CSS file?</summary>
 
You can link your HTML page to an external CSS file using the `<link>` tag inside the `<head>` section of your HTML file. Set the `href` attribute to the path of your CSS file and the `rel` attribute to `"stylesheet"`. 

For example:

```jsx
<head>
    <link rel="stylesheet" href="/css/styles.css">
</head>
```

Once again, the link to the CSS folder is relative to the `public` directory.
 
</details>

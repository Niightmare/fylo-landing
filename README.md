# Frontend Mentor - Fylo landing page with two column layout

![Design preview for the Fylo landing page with two column layout challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges allow you to improve your skills in a real-life workflow.

**To do this challenge, you need a basic understanding of HTML and CSS.**

## Where to find everything

Your task is to build out the project to the designs inside the `/design` folder. You will find both a mobile and a desktop version of the design to work to. 

The designs are in JPG static format. This will mean that you'll need to use your best judgment for styles such as `font-size`, `padding` and `margin`. This should help train your eye to perceive differences in spacings and sizes.

If you would like the Sketch file in order to see sizes etc, it is available to download from the challenge page.

You will find all the required assets in the `/images` folder. The assets are already optimized.

There is also a `style-guide.md` file, which contains the information you'll need, such as color palette and fonts.

## Building your project

Feel free to use any workflow that you feel comfortable with. Below is a suggested process, but do not feel like you need to follow these steps:

1. Initialize your project as a public repository on [GitHub](https://github.com/). This will make it easier to share your code with the community if you need some help. If you're not sure how to do this, [have a read through of this Try Git resource](https://try.github.io/).
2. Configure your repository to publish your code to a URL. This will also be useful if you need some help during a challenge as you can share the URL for your project with your repo URL. There are a number of ways to do this, but we recommend using [Vercel](https://bit.ly/fem-vercel). We've got more information about deploying your project with Vercel below.
3. Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes that you could create to make reusable styles.
4. Before adding any styles, structure your content with HTML. Writing your HTML first can help focus your attention on creating well-structured content.
5. Write out the base styles for your project, including general content styles, such as `font-family` and `font-size`.
6. Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.
7. If you'd like to try making your project fully responsive, we'd recommend checking out [Sizzy](https://bit.ly/fm-sizzy). It's a great browser that makes it easy to view your site across multiple devices.

## Deploying your project

As mentioned above, there are a number of ways to host your project for free. We recommend using [Vercel](https://bit.ly/fem-vercel) as it's an amazing service and extremely simple to get set up with. If you'd like to use Vercel, here are some steps to follow to get started:

1. [Sign up to Vercel](https://bit.ly/fem-vercel-signup) and go through the onboarding flow, ensuring your GitHub account is connected by using their [Vercel for GitHub](https://vercel.com/docs/v2/git-integrations/vercel-for-github) integration.
2. Connect your project to Vercel from the ["Import project" page](https://vercel.com/import), using the "From Git Repository" button and selecting the project you want to deploy.
3. Once connected, every time you `git push`, Vercel will create a new [deployment](https://vercel.com/docs/v2/platform/deployments) and the deployment URL will be shown on your [Dashboard](https://vercel.com/dashboard). You will also receive an email for each deployment with the URL.

## Sharing your solution

There are multiple places you can share your solution:

1. Submit it on the platform so that other users will see your solution on the site. Here's our ["Complete guide to submitting solutions"](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) to help you do that.
2. Share your solution page in the **#finished-projects** channel of the [Slack community](https://www.frontendmentor.io/slack).
3. Tweet [@frontendmentor](https://twitter.com/frontendmentor) and mention **@frontendmentor** including the repo and live URLs in the tweet. We'd love to take a look at what you've built and help share it around.

## Giving feedback

Feedback is always welcome, so if you have any to give on this challenge please email hi[at]frontendmentor[dot]io.

This challenge is completely free. Please share it with anyone who will find it useful for practice.

**Have fun building!** 🚀

## Community Sponsors

A massive thank you to our community sponsors!

- [Sizzy](https://bit.ly/fm-sizzy) is an extremely useful browser designed specifically to improve a developer's workflow when building websites. You can fire up multiple device emulators and run them all in sync while building out your web pages. Perfect for helping build fully responsive websites!
- [Diversify Tech](https://bit.ly/fem-diversify-tech) is an amazing resource for underrepresented people in tech. The site features job listings for anyone seeking new opportunities. The resource section is also full of useful links to dive into!
- [Dracula PRO](https://bit.ly/fem-dracula) is a beautiful dark theme to help keep you focused and productive while you code. The theme isn't just for your editor either. You can also apply it to your most-used apps like your terminal and even Slack!
# fylo-landing





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />
    <link rel="stylesheet" href="style.css" />

    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css"
    />
    <script src="main.js" defer></script>

    <title>Frontend Mentor | Ping coming soon page</title>
  </head>
  <body>
    <div class="container">
      <div class="content">
        <img class="logo" src="images/logo.svg" alt="Ping Logo" />
        <h2>We are launching <strong>soon!</strong></h2>
        <p>Subscribe and get notified</p>
        <form class="notify-form" novalidate>
          <input
            type="email"
            name="email"
            id="email"
            aria-label="Email Address"
            placeholder="Your email address..."
            required
          />
          <p class="message">Please provide a valid email address</p>
          <button type="submit" id="btn-submit" class="btn btn-blue">
            Notify Me
          </button>
        </form>

        <img
          src="images/illustration-dashboard.png"
          alt="illustration-dashboard"
          class="dashboard"
        />
      </div>

      <footer>
        <div class="socials">
          <div class="social-icon">
            <i class="fab fa-facebook-f"></i>
          </div>
          <div class="social-icon">
            <i class="fab fa-twitter"></i>
          </div>
          <div class="social-icon">
            <i class="fab fa-instagram"></i>
          </div>
        </div>
        <p class="copyright">© Copyright Ping. All rights reserved.</p>
        <p class="attribution">
          Challenge by
          <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
            >Frontend Mentor</a
          >. Coded by <a href="#">NI1GHTMARE</a>.
        </p>
      </footer>
    </div>
  </body>
</html>



:root {
  --Blue: hsl(223, 87%, 63%);
  --Pale-Blue: hsl(223, 100%, 88%);
  --Light-Red: hsl(354, 100%, 66%);
  --Gray: hsl(0, 0%, 59%);
  --Very-Dark-Blue: hsl(209, 33%, 12%);
}

@import url("https://fonts.googleapis.com/css2?family=Libre+Franklin:wght@300;600;700&display=swap");

html,
body {
  margin: 0;
}

body {
  display: flex;
  flex-direction: column;
  font-family: "Libre Franklin", sans-serif;
  font-size: 20px;
  color: var(--Very-Dark-Blue);
  /* border: 2px dotted orange; */
}

.container {
  padding: 3em 1em 0 1em;
  text-align: center;
  /* border: 1px solid green; */
}

/* .content {
  border: 1px solid red;
} */

.logo {
  margin-bottom: 1em;
  width: 4em;
  /* border: 1px solid green; */
}

h2 {
  font-size: 1.5rem;
  font-weight: 300;
  color: var(--Gray);
  /* border: 1px solid blue; */
}

h2 strong {
  color: initial;
}

p {
  font-size: 0.7em;
  /* border: 1px solid red; */
}

.notify-form {
  display: flex;
  flex-direction: column;
  margin-top: 2em;
  margin-bottom: 4em;
  /* border: 1px solid blue; */
}

.notify-form input {
  border: 1px solid var(--Pale-Blue);
  border-radius: 25px;
  padding: 1em 2em;
  outline: none;
}

input::placeholder {
  font-weight: 300;
  color: var(--Pale-Blue);
}

input:focus {
  border: 2px solid var(--Pale-Blue);
}

.message {
  display: none;
  margin-top: 0;
  color: var(--Light-Red);
  font-style: italic;
  font-size: 12px;
  padding-top: 0.5em;
}

.error {
  display: block;
}

.input-error {
  border: 1px solid var(--Light-Red) !important;
}

.btn {
  margin-top: 1em;
  padding: 1em 2em;
  border-radius: 25px;
  box-shadow: 1px 10px 10px #507ef32f;
  font-size: 0.7em;
  border: none;
  outline: none;
}

.btn-blue {
  color: white;
  background-color: var(--Blue);
}

.btn-blue:hover {
  background-color: #658bec;
}

.dashboard {
  max-width: 100%;
  margin-bottom: 5em;
  /* border: 1px solid darkcyan; */
}

.socials {
  display: flex;
  justify-content: center;
  /* border: 1px solid fuchsia; */
}

.social-icon {
  display: inherit;
  align-items: center;
  justify-content: center;
  width: 1.5em;
  height: 1.5em;
  border-radius: 50px;
  cursor: pointer;
  margin-right: 0.5em;
  border: 1px solid var(--Pale-Blue);
}

.social-icon:hover {
  background-color: var(--Blue);
}

.social-icon:hover > i {
  color: white;
}

.copyright {
  color: var(--Gray);
}

i {
  color: var(--Blue);
}

.attribution {
  font-size: 12px;
  text-align: center;
}

.attribution a {
  text-decoration: underline dotted;
  color: hsl(228, 45%, 44%);
}

.attribution a:hover {
  color: var(--Blue);
}

@media screen and (min-width: 800px) {
  .logo {
    width: auto;
  }

  h2 {
    font-size: 2em;
  }

  .notify-form {
    flex-direction: initial;
    justify-content: space-between;
  }

  .notify-form input {
    width: 72%;
  }

  .message {
    position: absolute;
    margin: 3.6em 0 0 2.5em;
  }

  .btn {
    margin-top: 0;
    width: 20%;
  }
}

@media screen and (min-width: 1024px) {
  body {
    align-items: center;
  }
  .btn {
    width: 20%;
  }

  h2 {
    font-size: 2.5em;
  }

  p {
    font-size: 20px;
  }
}

@media screen and (min-width: 1200px) {
  .container {
    width: 40em;
  }
}



function validateEmail(email) {
    let regex = /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
    return regex.test(String(email).toLowerCase());
  }
  
  function validate() {
    let email = document.querySelector("#email");
    let message = email.nextElementSibling;
  
    !validateEmail(email.value)
      ? (email.classList.add("input-error"),
        message.classList.add("error"))
      : (email.classList.remove("input-error"),
        message.classList.remove("error"));
  }
  
  let submitBtn = document.getElementById("btn-submit");
  
  submitBtn.addEventListener("click", (e) => {
    e.preventDefault();
    validate();
  });
  



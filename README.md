#  Modupeola's Portfolio Website Template

#### Accessible portfolio template for Developers and Data scientist✨.

#### A personal portfolio website showcasing my work as a Data Analyst, Data Scientist, BI Engineer, and ML Engineer/GenAI.

## Technologies Used
- Pure HTML
- Custom CSS
- Vanilla JavaScript
- GitHub Pages for hosting

## Customization
The portfolio includes:
- Data Science projects
- Machine Learning implementations
- BI Engineering work
- GenAI projects
- Research publications

## Getting Started 🚀
```bash
# Clone this repository
git clone https://github.com/Modupeolawuraola/modupeola-portfolio
````
### Want to learn how to create a template like this ?

### Live Website
Visit my portfolio at: https://modupeolawuraola.github.io/modupeola-portfolio/


## Features
- Clean, Simple and Modern UI Design
- Built with HTML, CSS and JavaScript
- Responsive design
- Project showcase
- Research publications
- Blog integration
- Contact information
- Fast loading ⚡

### Contributions are warmly welcomed ❤️.

If you don't have Git installed or you don't like using the terminal then you can download the [zip](https://github.com/nisarhassan12/portfolio-template/archive/master.zip) and extract that and open the extracted folder in the code editor of your choice.

## Portfolio Sections
- About Me
- Work/Projects
- Research
- Blog
- Contact

## Editing the Template 🔨

Go to `index.html` and fill your information. 

### Header

In all of the places where you're supposed to fill your information you'll find HTML comments. As shown below just replace what is already in the opening and closing tags below the comment with your information.

```html
<div class="header__text-box row">
    <div class="header__text">
        <h1 class="heading-primary">
        <!-- Replace the following name with your name -->
        <span>Modupeola Fagbenro</span>
        </h1>
        <!-- Put a small paragraph about yourself -->
        <p>Data Analyst| Data Scientist| BI Engineer| ML Engineer| Gen AI</p>
        <a href="#contact" class="btn btn--pink">Get in touch</a>
    </div>
</div>
```

### About Section

- Replace the contents in the below paragraph with information about yourself.
- Place a nice photo of yourself in the `images/` directory and then change the name in the src with your image name.

```html
<section class="about" id="about">
    <div class="row">
        <h2>About Me</h2>
        <div class="about__content">
            <div class="about__text">
                <!-- Replace the below paragraph with info about yourself -->
                <p>
                
                </p>
                <!-- Provide a link to your resume -->
                <a href="#" class="btn">My Resume</a>
            </div>

            <div class="about__photo-container">
                <!-- Add a nice photo of yourself -->
                <img
                class="about__photo"
                src="./images/modupeola_scrn.png"
                alt=""
                />
            </div>
        </div>
    </div>
</section>
```


### Work Section

Each div with class `work__box` represents a project, replace the contents of the all the tags with the information of your projects.

```html
<div class="work__box">
    <div class="work__text">
    <h3>Portfolio Template</h3>
    <p>
        A free Open Source Portfolio for anyone to use for free.
    </p>
    <ul class="work__list">
        <li>Python</li>
        <li>R</li>
        <li>SQL</li>
        <li>ML(TensorFlow, Keras, PyTorch)</li>
    </ul>

    <div class="work__links">
        <a href="#" class="link__text">
        Visit Site <span>&rarr;</span>
        </a> 
        <a href="https://github.com/Modupeolawuraola/modupeola-portfolio/tree/main" target="_blank">
        <img src="./images/github.svg" class="work__code" alt="GitHub">
        </a>
    </div>
    </div>
    <div class="work__image-box">
        <img
            src="./images/project-1.png"
            class="work__image"
            alt="Project 1"
        />
    </div>
</div>
```

For changing the screenshot:
- first place the image in `images/` folder and then in HTML replace the name in `src` with the name of your image.

- Recommended size for project image (1366 x 767px) also make sure the size of all  project images is the same.

```html
<img
    src="./images/name-of-your-image.png"
    class="work__image"
    alt="Project 1"
/>
```

### Research Section 

- Place research links publications that you have done accordingly 


```html
<div class="work__links"><a href="#" class="link__text" target="_blank" rel="noopener noreferrer">
        Read Publication <span>&rarr;</span></a></div>
```

### Blog Section 

- Enjoy technical write up? place your technical write-up here

```html
 <div class="work__links">
              <a href="https://medium.com/@Gold31" class="link__text">
                Visit Medium Profile <span>&rarr;</span>
```


### Contact Section

- Modify the paragraph to your likings.
- Replace the email with yours in the `href` anchor property and the text also.

```html
<section class="contact" id="contact">
      <div class="row">
        <h2>Get in Touch</h2>
        <div class="contact__info">
          <p>
              # contact writing here 
          </p>
          <!-- Replace the email with yours -->
          <a href="mailto:you@example.com" class="btn">you@example.com</a>
        </div>
      </div>
</section>
```

### Footer

- Replace the `href` attribute values to your profile URLs for all anchors.
- Remove the div with class `footer__github-buttons`.

```html
<footer role="contentinfo" class="footer">
    <div class="row">
        <!-- Update the links to point to your accounts -->
        <ul class="footer__social-links">
            <li class="footer__social-link-item">
                <a href="https://github.com/Modupeolawuraola">
                    <img src="./images/github.svg" class="footer__social-image" alt="Github">
                </a>
            </li>
            
            <li class="footer__social-link-item">
                <a href=https://www.linkedin.com/in/modupeola-fagbenro/">
                    <img src="./images/linkedin.svg" class="footer__social-image" alt="Linkedin">
                </a>
            </li>
        </ul>

        <!-- If you give me some credit by keeping the below paragraph, will be huge for me 😊 Thanks. -->
        <p>
          &copy; 2020 - Template designed & developed by <a href="https://modupeolawuraola.github.io/modupeola-portfolio/">Modupeola Fagbenro</a>.
        </p>
        <div class="footer__github-buttons">
          <iframe
            src="https://github.com/Modupeolawuraola/modupeola-portfolio/tree/main" 
            frameborder="0" scrolling="0" width="170" height="20" title="Watch Portfolio Template on GitHub">
          </iframe>
        </div>
    </div>
</footer>
```
### Contact
Feel free to reach out:
- Email: modupeola.fagbenro@gwu.edu
- LinkedIn: https://www.linkedin.com/in/modupeola-fagbenro/
- GitHub: https://github.com/Modupeolawuraola

### Contributions welcome ✨
Suggestions and feedback are welcome!

&copy; 2025 Modupeola Fagbenro 💫


###  Credits
Based on the accessible portfolio template by [Nisar](https://github.com/nisarhassan12), customized and modified for data science and ML portfolio presentation.


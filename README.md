
# HTML5 Résumé Template for Web Developer

Online Résumé(CV) template for web developer using HTML5 and CSS3.


![Screenshot](/assets/img/screenshot.png)
<!-- <div align="center">
  <img src="/assets/img/screenshot.png" />
</div> -->


## Change Your Name, Job and Profile Image

```html
<header>
  <h1 class="heading-container">Résumé</h1>
  <h2 class="name-container">your name</h2>
  <h3 class="job-container">your role</h3>
  <div class="profile-picture">
    <img src="./assets/img/profile.png" alt="">
  </div>
  ...
</header>
```

 - Write down your name in `h2` tag
 - Write down your job name in `h3` tag
 - Change the image file in `/path/assets/img/profile.png`


## Change Your Contact Information

```html
<header>
  ...
  <div class="contact-container">
    <ul class="contact-list">
      <li>
        <a href="tel:01000000000">+82. 010. 0000. 0000</a>
        <span><i class="fa fa-phone" aria-hidden="true"></i></span>
      </li>
      <li>
        <a href="mailto:your@email.com">your@email.com</a>
        <span><i class="fa fa-envelope-o" aria-hidden="true"></i></span>
      </li>
      <li>
        <a href="#" target="_blank">your homepage address</a>
        <span><i class="fa fa-globe" aria-hidden="true"></i></span>
      </li>
      <li>
        <a href="https://github.com/dhparkdh/resume-for-web-developer" target="_blank">your github address</a>
        <span><i class="fa fa-github" aria-hidden="true"></i></span>
      </li>
    </ul>
  </div>
</header>
```

 - Write down your phone number in first `li` tag
 - Write down your email address in second `li` tag
 - Write down your homepage web address in third `li` tag
 - Write down your github page address in fourth `li` tag


## Change Your Experiences

```html
<section class="resume-item experience">
  <div class="inner">
    <h2>experience</h2>
    <ul>
      <li>
        <h3>Your Role</h3>
        <h4 class="company">Your Company Name & Location</h4>
        <span class="date">Working Period</span>
        <p class="detail">
          Details what you did at this company
        </p>
      </li>
      ...
    </ul>
  </div>
</section>
```

 - Write down your role when you were in the company in `h3` tag
 - Write down your company name and location when you were in the company in `h4` tag
 - Write down your working details when you were in the company in `p` tag


## Change Your Projects

```html
<section class="resume-item project">
  <div class="inner">
    <h2>project</h2>
    <ul>
      <li>
        <h3><a href="#" target="_blank">Your Project Name</a></h3>
        <p class="detail">
          Details what the project is
        </p>
        <p class="tags">#hash #tags</p>
      </li>
      ...
    </ul>
  </div>
</section>
```

  - Write down your project name in `h3` tag
  - Write down the details about your project in first `p` tag
  - Write down hash tags about your project in second `p` tag


## Change Your Skills

```html
<section class="resume-item skill">
  <div class="inner">
    <h2>Skill</h2>
    <ul>
      <li>
        <h3>Your Skill Name</h3>
        <div class="skill-bar">
          <span class="bar" style="width: Percentage% ;"></span>
        </div>
      </li>
      ...
    </ul>
  </div>
</section>
```

  - Write down your skill name in `h3` tag
  - Write down your proficiency percentage in `width` attribute of `span` tag

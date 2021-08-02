# Andrei Karabash

*e-mail: andrzej.karabasz@gmail.com / tel: +48 731 379 914 / telegram: @frissonar*

## About

I learn programming to be able to develop my own software. First of all, I focus on quality. Therefore, I try to put as much effort as I can to understand new infromation well from the very beginning. My main priorities are efficiency, accuracy and tolerance to the people around me. I am good at communicating with people, understanding their needs and managing. Recently, I noticed that my quality-first approach is also usefull in programming. What often helps me a lot is my ability to understand sophisticated concepts relatively fast.
My working experience is not related to programming but it teached me usefull skills like:

1. As an assistant mechanical engineer, I had to understand how the vessels work by applying my theoretical knowledge in practice.
2. When working as sales specialist, I learned how to speak with people in order to undestand their needs
3. When I was a marketing manager, I found out what drives people minds the most and how to manage a team.

On each of these positions it was essential to assimilate a lot of new information in a timely manner and utilise it propperly. It is hard but also very interesting and fun for me.

## Skills

* HTML
* CSS
* GIT
* GitHub
* VScode

## Code examples

```* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  height: 1200px;
}

.container {
  display: flex;
  justify-content: center;
}

.example {
  display: flex;
  justify-content: space-around;

  width: 800px;
  margin: 50px 0;
  background-color: #D6E9FE;
}

.item img {
  display: block;
}

.item-relative {
  position: relative;
  bottom: 30px;
  right: 30px;
}

.item-absolute {
  position: absolute;
  bottom: 50px;
  right: 50px;
}

.absolute {
  position: relative;
}

.item-fixed {
  position: fixed;
  bottom: 0;
  right: 0;
}
```
```* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  height: 1200px;
  font-size: 18px;
  font-family: sans-serif;
  color: #5D6063;
}

a:link,
a:visited {
  color: #5D6063;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}

.header {
  position: fixed;
  display: flex;
  justify-content: space-between;

  width: 100%;
  padding: 50px;
  background: #D6E9FE;
}

.menu {
  margin-top: 15px;
}

.menu > li {
  display: inline;
  margin-right: 50px;
}

.menu > li:last-of-type {
  margin-right: 0;
}

.dropdown:hover .features-menu {
  display: flex;
  flex-direction: column;
  background: #B2D6FF;
  border-radius: 5px;
  padding-top: 60px;

  position: absolute;
  top: -25px;
  left: -30px;
  z-index: 1;
}

.features-menu li {
  list-style: none;
  border-bottom: 1px solid #FFF;

  padding: 0 40px 10px 20px;
  margin: 10px;
}

.features-menu li:last-of-type {
  border-bottom: none;
}

.dropdown {
  position: relative;
}

.dropdown > span {
  z-index: 2;
  position: relative;
  cursor: pointer;
}

.features-menu {
  display: none;
}
```
```<!DOCTYPE html>
<html lang='eng'>
  <head>
    <meta charset='UTF-8'/>
    <title>Semantic HTML</title>
  </head>
  <body>
    <div class='page'>
      <header>
        <h1>Interneting is Easy!</h1>
        <nav>
          <ul>
            <li><a href='#'>Home</a></li>
            <li><a href='#'>About</a></li>
            <li><a href='#'>Blog</a></li>
            <li><a href='#'>Sign Up</a></li>
          </ul>
        </nav>
      </header>
        <article>
          <header>
            <h1>Semantic HTML</h1>
            <p>By Troy McClure. Published <time datetime='2017-1-3 15:00-0800'>January 3rd</time></p>
          </header>

          <aside class='advert'>
            <img src='some-advert-image.png'/>
          </aside>

          <p>This is an example web page explaining HTML5 semantic markup.</p>

          <section>
            <h2>The Document Outline</h2>
            <p>HTML5 includes several "sectioning content" elements that affect the
              document outline.</p>

            <figure>
              <img src='semantic-elements.png'
                   alt='Diagram showing <article>, <section>, and <nav> elements'/>
              <figcaption>New HTML5 semantic elements</figcaption>
            </figure>

            <h3>Headers</h3>
            <p>The <code>&lt;header&gt;</code> element is one such sectioning
             element.</p>

            <h3>Footers</h3>
            <p>And so is the <code>&lt;footer&gt;</code> element.</p>
          </section>

          <h2>Inline Semantic HTML</h2>
          <section>

            <p>The <code>&lt;time&gt;</code> element is semantic, but it's not
               sectioning content.</p>
          </section>
          <footer>
            <p>This fake article was written by somebody at InternetingIsHard.com, which
              is a pretty decent place to learn how to become a web developer. This
              foot is only for the containing <code>&lt;article&gt;</code> element.</p>
            <address>
              Please contact <a href='mailto:troymcclure@example.com'>Troy
              McClure</a> for questions about this article.
            </address>
          </footer>

        </article>

        <aside class='sidebar'>
          <h2>Sidebar</h2>
          <p>Some sidebar content</p>
          <nav>
            <h3>HTML &amp; CSS Tutorial</h3>
            <ul>
              <li><a href='#'>Introduction</a></li>
              <li><a href='#'>Basic Web Pages</a></li>
              <li><a href='#'>etc...</a></li>
            </ul>
          </nav>
          <nav>
            <h3>JavaScript Tutorial</h3>
            <ul>
              <li><a href='#'>Introduction</a></li>
              <li><a href='#'>Hello, JavaScropt</a></li>
              <li><a href='#'>etc...</a></li>
            </ul>
          </nav>
        </aside>
        <footer>
          <p>&copy; 2017 InternetingIsHard.com</p>
        </footer>`
    </div>
  </body>
</html>
```
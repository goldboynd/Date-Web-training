html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}
* {
	box-sizing: border-box;
}
body {
    background: url(https://orange.codeberryschool.com/content/images/project-assets/wedding-landing-background.png) repeat center;
    font-family: 'Libre Baskerville', serif;
    font-size: 1.125rem;
    line-height: 1.5;
    color: #444349;
}
div {
  display: block;
}
.cover {
  background: url(https://orange.codeberryschool.com/content/images/project-assets/wedding-landing-cover.jpg) no-repeat 70% center/cover;
  display: table;
  text-align: center;
  height: 100vh;
  width: 100%;
}

.info {
  vertical-align: middle;
  display: table-cell;
}
.info2 {
  margin: 0 auto;
  padding: .625rem;
  color: hsla(0,0%,100%,.9);
  background: hsla(100,0%,0%,.5);
}

.h2 h3 {
  font-family: 'Libre Baskerville', serif;
}
h1 {
  font-family: 'Great Vibes', cursive;
}
.headline {
  font-size: 4rem;
  color: #d2ba87;
  margin: 1rem;
}
.tagline {
  font-size: 2rem;
  letter-spacing: .15rem;
}
.date {
  font-size: 2rem;
  letter-spacing: .15rem;
}
.tagline::after {
  display: block;
  content: "";
  background-color: #fff;
  height: 1px;
  width: 12.515625rem;
  margin: .5rem auto;
}
.date::before, .date::after {
  display: inline-block;
  content: "";
  background-color: #fff;
  height: 1px;
  width: 1.5rem;
  vertical-align: middle;
  margin: 0 .5rem;
}
section {
  display: block;
}
.location {
  width: 100%;
  margin: auto;
  padding: 2rem 1rem;
  text-align: center;
}
h1 {
  font-size: 4rem;
  text-align: center;
}
h2 {
  font-size: 2rem;
  margin-bottom: .8rem;
  font-weight: 700;
  letter-spacing: .05rem;
}
.picture {
  width: 8rem;
}
h3 {
  font-size: 1.5rem;
  margin-top: .8rem;
}
.location1::after {
  content: "";
  display: block;
  height: .1875rem;
  width: 25vw;
  margin: 1.5rem auto;
  background-color: #444349;
}
.program {
  width: 100%;
  text-align: left;
  background-color: hsla(100,0%,0%,.6); 
  color: #d2ba87;
  font-family: 'Muli', sans-serif;
  margin-top: -0.9rem;
}
.program h1 {
  font-family: 'Great Vibes', cursive;
  margin-top: 1rem;
  text-align: center;
  padding: 0.5rem;
}
.program1  {
  font-size: 1.3rem;
  padding: 0.5rem;
  margin-bottom: 1rem;
}
.gift {
  width: 100%;
  margin: -0.9rem auto;
  text-align: center;
}
.gift h1 {
  padding: 1rem;
}
.faq {
  margin: 1.5rem auto;
  padding: .8rem;
  color: #d2ba87;
  background-color: hsla(100,0%,0%,.6);
  letter-spacing: .05rem;
}
.question {
  font-weight: 700;
}
.answer {
  margin-bottom: 1.5rem;
  font-family: 'Muli', sans-serif;
}
.faq1::after {
  display: block;
  content: "";
  background-color: #d2ba87;;
  height: 4px;
  width: 12.515625rem;
  margin: .5rem auto;
}
.contact {
  text-align: center;
}
footer {
    height: 10vh;
    width: 100%;
    background-color: #606060;
    color: #fff;
    font-family: 'Muli', sans-serif;
    display: table;
    text-align: center;
    font-size: .875rem;
}
.foter {
  display: table-cell;
  vertical-align: middle;
  padding: .5rem 1rem;
}
/* Media */
@media (min-width: 768px) {
  .info {
    padding: 1.25rem;
    border-radius: 4px;
    width: 50%;
  }
  .cover {
    background: url('https://orange.codeberryschool.com/content/images/project-assets/wedding-landing-cover.jpg') no-repeat center/cover;
  }
}
@media (min-width: 768px) {

  .location1 {
    display: inline-block;
    width: 30%;
    padding: 1.5rem;
    margin: .5rem;
  }

  .location1::after {
    display: none;
  }

}
@media (min-width: 768px) {

  .program1 {
    width: 30vw;
    margin: 0 auto;
  }

}
@media (min-width: 768px) {
  .faq1 {
    display: inline-block;
    width: 30%;
    vertical-align: top;
    padding: 1.5rem;
    margin: .5rem;
  }
  .faq1::after {
    display: none;
  }
  .faq1 h2 {
    text-align: left;
  }
}
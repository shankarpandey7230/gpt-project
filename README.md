# create react app

npx create-react-app@latest gpt-project

# install react icons

npm install react-icons

# for gradient

use Angry tools
.gradient\_\_bg {
background:-moz-radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 25%);

/_ safari 5.1+,chrome 10+ _/
background:-webkit-radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 25%);

/_ opera 11.10+ _/
background:-o-radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 25%);

/_ ie 10+ _/
background:-ms-radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 25%);

/_ global 92%+ browsers support _/
background:radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 25%);
}

# animation

visit https://animista.net/

#Navbar
import React from "react";
import { RiMenu3Line, RiCloseLine } from "react-icons/ri";
import logo from "../../assets/logo.svg";
import "./navbar.css";

const Navbar = () => {
return (

<div className="gpt3__navbar">
<div className="gpt3__navbar-links">
<div className="gpt3__navbar-links_logo">
<img src={logo} alt="logo" />
</div>
<div className="gpt3__navbar-links_container">
<p>
<a href="#home">Home</a>
</p>
<p>
<a href="#wgpt3">What is GPT3?</a>
</p>
<p>
<a href="#possibility">Open AI</a>
</p>
<p>
<a href="#features">Case Studies</a>
</p>
<p>
<a href="#blog">Library</a>
</p>
</div>
</div>
<div className="gpt3__navbar-sign">
<p>Sign in</p>
<button type="button">Sign up</button>
</div>
</div>
);
};
export default Navbar;

# navbar.css

.gpt3\_\_navbar {
display: flex;
justify-content: space-between;
align-items: center;

padding: 2rem 6rem;
}

.gpt3\_\_navbar-links {
flex: 1;
display: flex;
justify-content: flex-start;
align-items: center;
}

.gpt3\_\_navbar-links_logo {
margin-right: 2rem;
}

.gpt3\_\_navbar-links_logo img {
width: 62.56px;
height: 16.02px;
}

.gpt3\_\_navbar-links_container {
display: flex;
flex-direction: row;
}

.gpt3\_\_navbar-sign {
display: flex;
justify-content: flex-end;
align-items: center;
}

.gpt3**navbar-links_container p,
.gpt3**navbar-sign p,
.gpt3**navbar-menu_container p {
color: #fff;
font-family: var(--font-family);
font-weight: 500;
font-size: 18px;
line-height: 25px;
text-transform: capitalize;
margin: 0 1rem;
cursor: pointer;
}
.gpt3**navbar-sign button,
.gpt3\_\_navbar-menu_container button {
padding: 0.5rem 1rem;
color: #fff;
background: #ff4820;
font-family: var(--font-family);
font-weight: 500;
font-size: 18px;
line-height: 25px;
border: none;
outline: none;
cursor: pointer;
border-radius: 5px;
}

.gpt3**navbar-menu {
margin-left: 1rem;
display: none;
position: relative;
}
.gpt3**navbar-menu svg {
cursor: pointer;
}
.gpt3**navbar-menu_container {
display: flex;
justify-content: flex-end;
align-items: flex-end;
flex-direction: column;
text-align: end;
background: var(--color-footer);
padding: 2rem;
top: 40px;
margin-top: 1rem;
min-width: 210px;
border-radius: 5px;
box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
}
.gpt3**navbar-menu_container p {
margin: 1rem 0;
}
.gpt3**navbar-menu_container-links-sign {
display: none;
}
@media screen and (max-width: 1050px) {
.gpt3**navbar-links_container {
display: none;
}
.gpt3**navbar-menu {
display: flex;
}
}
@media screen and (max-width: 700px) {
.gpt3**navbar {
padding: 2rem 4rem;
}
}
@media screen and (max-width: 550px) {
.gpt3**navbar {
padding: 2rem;
}
.gpt3**navbar-sign {
display: none;
}
.gpt3**navbar-menu_container {
top: 20px;
}
.gpt3**navbar-menu_container-links-sign {
display: block;
}
}

# header

import React from "react";
import "./header.css";
import people from "../../assets/people.png";
import ai from "../../assets/ai.png";

const Header = () => {
return (

<div className="gpt3__header section__padding" id="#home">
<div className="gpt3__header-content">
<h1 className="gradient__text">
Let's Build Something amazing with GPT-3 OpenAI
</h1>
<p>
Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat
quaerat obcaecati voluptas excepturi! Molestias quae provident nobis
nostrum corporis! Necessitatibus, ab, expedita soluta, cupiditate
doloremque quos molestias quia quae eveniet commodi consequuntur
corporis dignissimos repudiandae pariatur autem deserunt. Atque, quos!
</p>
<div className="gpt3__header-content__input">
<input type="email" placeholder="Your Email Address" />
<button type="button">Get Started</button>
</div>
<div className="gpt3__header-content__people">
<img src={people} alt="people" />
<p>1600+people requested the access</p>
</div>
</div>
<div className="gpt3__header-image">
<img src={ai} alt="ai" />
</div>
</div>
);
};

export default Header;

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

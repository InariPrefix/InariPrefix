- 👋 Hi, I’m @InariPrefix
- 👀 I’m interested in working with Blender
- 🌱 I’m currently learning in colledge
- 💞️ I’m looking to collaborate with animation projects
- 📫 How to reach me Email: inariprefix@mail.ru
  
-------------------HTML--------------------------------------------------------------------------

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Document</title>
</head>
<body>
    <a href="#" style="--clr:#f1ce81"><span>Button</span><i></i></a>
    <a href="#" style="--clr:#f54]e81"><span>Button</span><i></i></a>
    <a href="#" style="--clr:#f13241"><span>Button</span><i></i></a>
</body>
</html>

------------------CSS-----------------------------------------------------------------------------

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: fantasy, sans-serif;
}
body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #150e1a ;
    flex-direction: column;
    gap: 50px;
}
a {
    position: relative;
    background: #fff;
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 1.5em;
    letter-spacing: 0.1em;
    font-weight: 400;
    padding: 10px 30px;
    transition: 0.5s;
}
a:hover {
    background: var(--clr);
    color: var(--clr);
    letter-spacing: 0.25em;
    box-shadow: 0 0 35px var(--clr);
}
a:before {
    content: '';
    position: absolute;
    inset: 2px;
    background: #150e1a;
}
a span {
    position: relative;
    z-index: 1;
}
a i {
    position: absolute;
    inset: 0;
    display: block;
}
a i::before {
    content: '';
    position: absolute;
    top: 0;
    left: 80%;
    width: 10px;
    height: 4px;
    background: #150e1a;
    transform: translateX(-50%) skewX(325deg);
    transition: 0.5s;
}
a:hover i::before {
    width: 20px;
    left: 20%;
}
a i::after {
    content: '';
    position: absolute;
    bottom: 0;
    right: 80%;
    width: 10px;
    height: 4px;
    background: #150e1a;
    transform: translateX(-50%) skewX(325deg);
    transition: 0.5s;
}
a:hover i::after {
    width: 20px;
    right: 20%;
}

<!---
InariPrefix/InariPrefix is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

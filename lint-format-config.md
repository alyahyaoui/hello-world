# How to setup eslint & prettier & vscode (Easy way)



*Writing high quality code is as important as the code itself, this is why tools for liting and formatting are required to improve code style.  
in this article we will see how to setup Eslint with **Airbnb config** + Prettier in Vscode*.   
why using linting tools like Esline. linting tools allow us to reduce errors and accelerate developping workflow    
linting is creating automated checking for javascript without executing it.
using combined liting and formatting tools help to improve overall code quality.   
Formatting tools such as "Prettier" help to enforece a code style making team work easier and code more understandable this is why we use Airbnb code style in this article.
***
**prerequisites:**    
- **Nodejs & NPM installed**
- **Eslint extension for Vscode**
- **Prettier extension for vscode**   

***

First of all we need to install related packages using NPM in our working directory ( -D flag used to install packages as dev dependancies ).  

```bash
npm install -D eslint prettier eslint-config-prettier eslint-plugin-prettier
```
You can enable Eslint globally ( *this way you dont have to install it in the working folder and you can generate a global .eslistrc file but this is not recommended* )
```bash
sudo npm install -g eslint
````
now our needed packaged are fully downloaded, time to start the configuration.
`bash
eslint --init
`

---
[https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/templates/javascriptt2-dark_1200x303.png?sfvrsn=78a85ef2_2]

# How to setup eslint & prettier & vscode (Easy way)



*Writing high quality code is as important as the code itself, this is why tools for liting and formatting are required to improve code style.  
in this article we will see how to setup Eslint with **Airbnb config** + Prettier in Vscode*.   

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

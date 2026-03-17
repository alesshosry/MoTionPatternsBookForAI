## Intro

This file contains references to the repositories of MoTion and the metamodels that are supported in this documentation. 

### MoTion repository
To get MoTion repository, you can refer to this link: https://github.com/moosetechnology/MoTion .\
If you want you can paste the below in the playground of your Pharo to install the library. And don't forget to load Moose matcher package if yo are using Moose image.
```Smalltalk
Metacello new
    baseline: 'MoTion';
    repository: 'github://moosetechnology/MoTion:main';
    load.
```

### FASTTypeScript repository
To get FASTTypeScript repository and represent the AST of TypeScript in Moose, you can refer to this link: https://github.com/moosetechnology/FASTTypescript .\
To install it you can execute the below in the playground of Pharo:
```smalltalk  
Metacello new  
  baseline: 'FASTTypeScript';  
  repository: 'github://moosetechnology/FASTTypescript:main';  
  load.
```  

### FASTXML repository
To get FASTXML repository and represent the AST of TypeScript in Moose, you can refer to this link: https://github.com/Evref-BL/FASTXML .\
To install it you can execute the below in the playground of Pharo:
```smalltalk  
Metacello new  
  baseline: 'FASTXML';  
  repository: 'github://Evref-BL/FASTXML:master';  
  load.
```

### FASTJava repository
To get FASTXML repository and represent the AST of TypeScript in Moose, you can refer to this link: https://github.com/moosetechnology/fast-java .\
To install it you can execute the below in the playground of Pharo:
```st
Metacello new
  githubUser: 'moosetechnology' project: 'FAST-JAVA' commitish: 'v3' path: 'src';
  baseline: 'FASTJava';
  load
```

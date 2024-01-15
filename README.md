# BuildAngular
TP Workflow : utiliser GitHub Actions pour build un code Angular 

  on
  
    push.[main]
  
  jobs : 

    compiler code Angular (Ubuntu.latest)
    
      steps :
    
        installer Node.js
        installer npm
        installer angular
        build l'application 

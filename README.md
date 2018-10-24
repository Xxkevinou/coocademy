# Moocademy 
## Travail réalisé par 
Sophie (@Kevinou), Quentin (@Dremsis), Yannis (@Yannis), Marin (@Marin), Robin (@Robin Caron)<br/>
Ce programme contient la base de donnée d'un site de cours immaginaire avec des cours et des leçons.<br/>
## Pour l'utiliser
Ruby version utilisé 2.5.1 <br/>
Rails version utilisé 5.2.1 <br/>
Clone le repo <br/>
`git clone https://github.com/Xxkevinou/coocedemy`<br/>
Installe les gems<br/>
`bundle install`<br/>
Fais ce qu'il te plait<br/>
## Gem utilisées
cf `Gemfile` (gems classiques d'une app rails)<br/>
## Schema de la base de donnée
```
                              ____________        ____________       
                             |   cours    |      |   lessons  |    
                             |¯¯¯¯¯¯¯¯¯¯¯¯|      |¯¯¯¯¯¯¯¯¯¯¯¯|      
                             |            |      |            |      
                             | title      |1    n| title      |
                             | description|¯¯¯¯¯¯| body       |
                             | lesson_id  |      |            |      
                             |____________|      |____________|
```
## kiss

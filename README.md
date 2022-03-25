# Test-animations-CSS
Just a front-end website to practice my animation skill in css.

Colors, text-sixe, text-content and margin are updaptable and dedicated to test (sorry for colors). 

Code composition : 
    -index.html : contains html Code.
    -images folder : contains the downloaded images.
    -package.json : In this case, used only for charging the Sass script.
    -sass folders : -base folder : -base.scss : contains rules for basic parameters
                    -components folder : -bouton.scss : contains all the bouton rules of the website, and animations.
                    -layout folder : -footer.scss : contains all rules for the footer
                                    - header.scss : contains all rules for the header
                    -pages folder : -section.scss : contains all rules for the body                                   
                    -utils folder :- mixins.scss : contains all mixins of this website
                                    - variables.scss : contains all variables of this website
                    -main.scss : contains all links to import in css file
    -css folders : - style.css : All the code in css language
                    - style.css.map : Contains the map to find style.css
                    - prefixed folders : - style.css : contains a version of the css code with autoprefixer to translate it to the different navigators.
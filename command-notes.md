```shell
## create new project
ng new angular-ui

## add anti-hero module
ng g m anti-hero

## make the two components. 
## This will create two new components, form and list, under the pages folder.
ng g c anti-hero/pages/form
ng g c anti-hero/pages/list 

##  add a routing module
ng g m anti-hero/anti-hero-routing --flat

## Create shared module 
ng g m shared


## create FooterComponent and NavbarComponent  
ng g c shared/layout/navbar
ng g c shared/layout/footer



```
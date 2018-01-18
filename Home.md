Welcome to the HammerJS wiki!


https://www.youtube.com/watch?v=5Z2C0wy4bmg

https://daneden.github.io/animate.css/

https://hammerjs.github.io/


angular material:

internationalized
clean and simple api
well-tested
customizable
fast
well-documented

components:
form controls-radio
navigation-toolbar,menus
layout-lists,grid-lists,cards
buttons-indicators & icons-button,icons,progrss,spinner,progress bars
popup and models-dialog,toolups
data table-table,sorting,pagination


form-controls:
checkbox
radio button

dilaog in matreial 

different javascript
1)bootstrap-
diffenet look and design
3rd party components
alot of dependencies

2)angular material- 
modules angular application
design by material
still new
same quality components
common api
easy to use

install angular material:


https://material.angular.io/guides
->get started
->cd material-demo/
->npm i --save @angular/cdk @angular/material @angular/hammerjs
@angular/animations



cdk-component depencendy kit
animation-add animaiton
hammerjs- powerful library gesture support
rotate,pinch,press,pan,tap,swipe


style.css:
@import "~@angular/material/prebuilt-themes/indigo.pink.css";

app.module.ts:

import { BrowserModule } from '@angular/platform-browser'
import { BrowserAnimationModule } from '@angular/platform-browser'
import { MdCheckboxModule } from '@angular/material/checkbox';
import  
imports:[
BrowserModule,
BrowserAnimationsModule
MdCheckboxModule 
],

check Boxes:

<md-checkbox>subscri to new letter</md-checkbox>


niranjan

abb
cdc2
 
2floor
app.html:

<md-checkbox>subscribe to newletter</md-checkbox>

cmd:
terminal- ng serve


components:

api-
show which components define

# contentprojection-contentchild-and-contentchildren

Hi, <br/>
This is a simple Angular POC created by Abhishek Choubey. <br/>
In this POC I tried to demonstrate the usage of Content Projection, @ContentChild and @ContentChildren decorator of Angular. <br/>
<br/>
I this POC I showed how to access following inside the Parent Component <br/>
1. Child Component <br/>
2. Directive <br/>
3. DOM Element <br/>

I created following components and directives  in this POC <br/>
ng g c counter <br/>
ng g c counter-parent <br/>
ng g c parent-color <br/>
ng g c theme <br/>
ng g d changebgcolor <br/>

<b> Important Note </b> <br/>
@ContentChildren(ChangebgcolorDirective, { descendants: true })
<br/>
<b> Short Description</b> <br/>
In counter and counter-parent component I showed the usage of @ContentChild and @ContentChildren with QueryList<> <br/>
In parent color component I showed the usage of @ContentChild and @Children example with directives <br/>
and {descendants:true} argument inside @ContentChildren <br/>                      
In theme component I showed the usage of @ContentChild and @ContentChildren with ElementRef and QueryList<ElementRef> <br/>

Software Used <br/>
node --version = v14.20.0 <br/>
npm --version = 6.14.17 <br/>
ng version <br/>
Angular CLI: 14.0.0 <br/>

Check my work 👉👉👉👉 https://abhigit799.github.io/contentprojection-contentchild-and-contentchildren/

<br/>


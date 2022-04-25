# UDEMY COURSE - BOOTSTRAP PROJECT 2

## Go to the Project Page
✳️   https://gulcanc.github.io/BOOTSTRAP-4-PAGE/

## The Purpose of the Project
🌸 Learning and creating high quality Bootstrap 4 theme 

🌸 Learning the Bootstrap 4 utilities, classes, components & JS widgets using a custom sandbox environment

🌸 Learn semantic HTML5 & modern CSS3 techniques

🌸 Using CSS Preprocessor Program "Sass", "Syntactically Awesom Style Sheets", with Bootstrap

## About the Project

This project is a fully responsive one page theme. We have a fixed customized navbar with a logo at the top; for smooth scrolling we used JQuery block in this navigation bar. After that, there is a home container which is a main show case area with a background image. This section containes some texts and an image. After home section there is a newsletter section with a line form and there are four boxes. Under this section, we have a different section that contains a title, some texts and vertically collapsed accordions which can be opened and closed. Next, we have "Meet the Authors" section where there are some images over cards, we can hover over these to change the color. After that, we have a contact form where we use input groups. Finally, there is a footer at the end of the page.
Moreover, in this project we used Sass, CSS precompiler, that allows us to do things like use variables, nesting and we can edit the bootstrap. 
Last important thing is that we used an application **Koala** for compaling our Sass; Koala is a GUI application for Less, Sass, Compass and CoffeeScript compilation, to help web developers to use them more efficiently.
## Techniques Used 

I started to the project by installing the application Koala, and downloading Bootstrap. Bootstrap source files have all scss files as well. I take all bootstrap scss files and add them inside my own scss folder. Next, I add my project to tha Koala App, here I decide what I want to compile and where it should go. I want to compile **bootstrap.scss** file and **style.scss** file inside **scss** folder. When I right click on the bootstrap.scss file and style.scss file, I see **set output path**, I click that and I want to set the output to go to the regular **css folder**. To this folder I add **bootstrap.css** and **style.css** files. If they are already exist I have to replace them. Thus, these two sass files will get compiled to **bootstrap.css** and **style.css**. When we manually compile this files, I will see my bootstrap.css and style.css files inside css folder. 

When I open the folder in VSCode, I see **_variables.scss** file where I can make all the cahnges to customize my bootstrap project. 

For starting to the project, first, I add a navigation menu and a logo to the navigation bar using an unordered list of clickable list items with different "IDs". I use a button for the navigation menu so that the navigation menu is properly displayed on the small screen.

       <button
          class="navbar-toggler"
          data-toggle="collapse"
          data-target="#navbarCollapse" >
          <span class="navbar-toggler-icon"></span>
        </button>
        
 Navbars require a wrapping .navbar with **.navbar-expand{-sm|-md|-lg|-xl}** for responsive collapsing and color scheme classes.
        
:pushpin: **box-shadow**:Horizontal offset | Vertical offset | Blur | Color  
:pushpin: **box-shadow**:2px 2px 5px $color-primary;

:pushpin: **position:relative**  The element is positioned relative to its normal position, so "left:20px" adds 20 pixels to the element's LEFT position.

:pushpin: **position:absolute**  The element is positioned relative to its first positioned ancestor element.

:pushpin: **Accordion**

<details>
 <summary>See the code for accordions</summary>
     
              <div id="accordion">
                <div class="card">
                  <div class="card-header">
                    <h5>
                      <div href="#collapse1" data-toggle="collapse" data-parent="#accordion">
                        <i class="fas fa-arrow-circle-down"></i>Get inspired
                      </div>
                    </h5>
                  </div>
                  <div id="collapse1" class="collapse show">
                    <div class="card-body">Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
                    </div>
                  </div>
                </div>
              </div>
       
</details>

:pushpin: **Responsive images**

class="img-fluid"

max-width="100%"

height="auto"

:pushpin: **Form in Bootstrap**

<form>
  <div class="input-group input-group-lg">
    <div class="input-group-prepend">
      <span class="input-group-text">
        <i class="fas fa-user"></i>
      </span>
    </div>
    <input type="text" class="form-control" placeholder="Name">
  </div>
</form>


























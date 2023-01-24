# programing-hero-notes

## CSS- Notes

**1. Rules to make responsive website** 

    1. meta viewport
    2. CSS relative measurement unit (rem,vh,vw,vmax,vmin)
    3. Responsive Image (Fluid Image)
        + img{width:100%}
    4. Body max-width and margin auto (for bigger screen)
        + body{
            max-width: 1400px;
            margin: 0 auto;
        }

    5. Split screen using flex 
    6. Grid responsive(multi column)


## Bootstarp- Notes

**1. Bootsrap grid is not CSS grid it is a 12  column layout** 

**2. Use this Grid in bellow pattern** 
    
    <div class="container / container-fluid>
        <div class= "row">
            <div class= "col">
                <div> 
                    <!--content -->         
                </div>           
            </div>
            <div class= "col">  
                <div> 
                    <!--content -->         
                </div>         
            </div>
        </div>
    </div>

**3. For Responsive we need 5 things**

    1. Container
    2. Row
    3. Column
    4. Breakpoints
    5. Concept of 12 columns
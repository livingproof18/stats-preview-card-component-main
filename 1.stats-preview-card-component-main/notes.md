Making of Design

Phone(Mobile Size){

    1. Body with the colour: - Very dark blue (main background): hsl (233, 47%, 7%);

    2. Then  the main content container..(needs margin)(responsive) with the colour: Dark desaturated blue (card background): hsl(244, 38%, 16%) ----- Center all text in the container.

    3. Then the hero-image...at tthe top of the container.(margin at the bootom.)

    4.Main heading( <h1>Get insights that help your business grow.</h1>) colour: - Soft violet (accent): hsl(277, 64%, 61%) and - White (main heading, stats): hsl(0, 0%, 100%)

    5. The the paragraph( <p>Discover the benefits of data analytics and make better decisions regarding revenue, customer 
          experience, and overall efficiency.</p>) 
          colour: - Slightly transparent white (main paragraph): hsla(0, 0%, 100%, 0.75)

    6. Then the stats( <ul class="stats">
            <li>
              <strong>10k+ </strong>
              <span> COMPANIES</span>
            </li>
            <li>
              <strong>314 </strong>
              <span>templates </span>
            </li>
            <li>
              <strong>12m+</strong>
              <span>queries</span>
            </li>
          </ul>) 

        colour: - Slightly transparent white (stat headings): hsla(0, 0%, 100%, 0.6)

    7. Change the colour of the image - colour- Soft violet (accent): hsl(277, 64%, 61%) and - White (main heading, stats): hsl(0, 0%, 100%).- This can be done through the fiter in css -  filter: invert(10%) sepia(27%) saturate(1666%) hue-rotate(242deg) brightness(50%) contrast(80%);


}

Desktop{
    1. Body with the colour: - Very dark blue (main background): hsl (233, 47%, 7%);

     2. Then  the main content container..(needs margin)(responsive) with the colour: Dark desaturated blue (card background): hsl(244, 38%, 16%) ----- In the center of the body

    3. Switch the layout of the content..- The image should be on the right and the written content on the left.(use grid)

    4. Fix the written content..
    the stats should be next to each other now( used flexbox)

}
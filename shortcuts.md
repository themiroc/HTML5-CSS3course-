<!--todo     VS code shortcuts: -->     search for them in docs.emmet.io
    
    ctrl + b                        hides navigation left panel
    ctrl + e                        buscar archivos recientes
    ctrl + p                        to search for files in the explorer
    ctrl + ,                        to open the settings
    ctrl + shift + e                seleccionar en el explorador de archivos / volver
    ctrl + shift + m                console pannel
    ctrl + shift + n                new VSC window
    ctrl + shift + p                Opens VS functionalities
    ctrl + shift + x                Extensions
    ctrl + shift + ?                minimap toggle off 
    ctrl + k + z                    to open zen mode
    ctrl + k ctrl + shift + s       save without formatting
    shift + alt + f                 Format document
    'exclude'   ???                 so explorer doesn't show some files
    

<!--todo     Code -->
    shift + alt + a                 comment several lines of code 
    alt + arrow up or down          select and move several lines
    ctrl + d                        to select a word to be copied or cut
    ctrl + d*                       multiple times we select several times a term within our text
    ctrl + f                        to find and replace words inside de code
    shift + alt + up or down arrow  duplicate line of code
    alt + q alt + w                 wrap with abbreviation
    
<!--todo    HTML -->
    !                               estructura de HTML
    div                             <div></div> 
    div.container                   <div class="container"></div>
    div#container                   <div id="container"></div>
    div.container#smthg             <div class="container" id="smthg"></div>
    .container#smthg                <div class="container" id="smthg"></div>    the div is implied
    h1.title#cooltitle              <h1 class="title" id="cooltitle"></h1> id identifies a section within the HTMLdoc
    ul  ol                          <ul></ul>   <ol></ol>
    li*3                            <li>1</li> <li>2</li> <li>3</li> to repeat elements
    ul>li*3{Item $}                 <ul> <li>Item 1</li> <li>Item 2</li> <li>Item 3</li> </ul>
    p>lorem5                        <p>Lorem ipsum dolor sit amet.</p>
    input:text                      <input type="text" name="" id="">
    lorem#                          dummy text. el # determina cuantas palabras se ingresan
    img                             <img src="" alt="">
    a                               <a href=""></a>
    video                           <video src=""></video> <video controls autoplay loop src=""></video> with boolean attributes
    audio                           <audio src=""></audio> <audio autoplay loop src=""></audio>

    <!--* entities: -->
    &nbsp;                          to have those two words in the same line inside de <p></p>
    &lt;                            <
    &gt;                            >
    &copy;                          copyrights symbol

    semantic elements:
    article                         <article></article>
    figcaption                      <figcaption></figcaption>
    time                            <time datetime="YEAR-MO-DA HO:MI"></time>
    nav                             <nav></nav>


<!--todo     CSS -->
    cur                             cursor: pointer;
    p10                             padding: 10px;
    m10                             margin: 10px;
    bxsh                            box-shadow: inset hoff voff blur #000;

    <!--* Selectors specificity -->
    h1 {}                           0.0.1
    .highlight {}                   0.1.0   
    #products                       1.0.0
    h1#products                     1.0.1

    *                               Universal selector for all elements in the html document

    a[href=“…”]                     Anchors with the given href 
    a[href*=“google”]               Anchors whose href contains google 
    a[href^=“https”]                Anchors whose href starts with https
    a[href$=“.com”]                 Anchors whose href ends with .com
    
    <!--* Relational selectors   -->
    #products p                     All p elements inside #products
    #products > p                   All p elements that are direct children of #products
    #products + p                   The p element immediately after #products (sibling)
    #products ~ p                   All p elements after #products (siblings)
    .class > *                      All elements that are direct children of .class

    <!--* Pseudo-class selectors  -->
    article :first-child            The first child of article elements 
    article :first-of-typ           The first occurrence of elements of different type 
    article p:first-of-typ          The first p element inside article elements
    article :last-child 
    article :last-of-type 
    article :nth-child(odd)         to pick odd or even elements
    article :nth-child(even)

    <!--* Pseudo-element selectors -->
    p::first-letter                 The first letter of every p element 
    p::first-line                   The first line of every p element 
    ::selection                     Any selected element 
    p::before                       To insert content before the content of p elements
    p::after                        To insert content after the content of p elements

<!--todo     Extensions -->
    ctrl + alt + n                  advanced New File: choose directory, name the file.
    alt + l alt + o                 opens live server
    
    * Polacode is to share snipetts of my code, for example, on twitter
    * Better comments (*, !, TODO, ?) 
    <!--TODO:--> 
    <!-- * -->
    <!-- ? -->
    <!-- ! -->

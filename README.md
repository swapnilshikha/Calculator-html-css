<style>
    .bg{
        background: red;
    }
    .tx{
        font-size: 50px;
    }
    #bg{
        background: yellow;
    }
</style>

<h1 class="bg tx">Hello</h1> /* WE can use multiple classes at a time */

<h1 class="bg" id="bg" >Hello</h1> /* ID has more priority than CLASS  id > class */

Priorities = inline styling > id > class > tag selector(eg, <h1>, <p>) > universal selector(*)

Child selector = '>'

'+' = Adjacent Siblings 
example, <div>
            <div>
                <p></p>
            </div> 
            <h1></h1>
         </div>
         Here, inner div and h1 are adjacent siblings as they are on the same level. 
         <p> is the child of the inner div.

         div+h1{
                 color:brown;
               } 

Responsiveness = 
default to 768px
768px  to 425px;
 425px to 320px;
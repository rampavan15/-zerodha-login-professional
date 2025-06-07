Why Flexbox for Zerodha Login:
1)  One-dimensional layout: simple for vertical  or horizontal  
2) Content-based sizing - Form adjusts to content naturally
3) Easy centering - Perfect for centering login box
4) Flexible spacing - Adjusts to different screen sizes
5) Responsive layout control: can make simple media for  different viewport tablet and mobile screens.


2. Show before/after code examples
   .main-content {
  text-align: center;
  margin: 0 auto;
}
  AFTER
  .main-content {
  display: flex;
    justify-content: center;
    align-items: center;
    flex: 1;
}

3. Problems Flexbox Solves

 No float or position hacks for layout.
 Makes it easy to  items responsively.
 light weight than Bootstrap 




ii  Why NOT CSS Grid:
1) .main-content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  justify-items: center;
  align-items: center;
}
  
 2) Overkill
  we should  also include row and columns which not requied for this.
  two-dimensional layout not useful for this  single-column login page

3) : Designing a newspaper, creating dashboards, magazine layouts

Why NOT Bootstrap:

more classes is requied 

as you mentions IKEA furniture - fast to assemble, looks good, but limited customization
mostly multi- pages it used  aldery code is writen we just extract.
 
 good choice = Quick assembly, team consistency, rapid prototyping


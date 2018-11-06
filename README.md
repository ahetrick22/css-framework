# css-framework

This framework utilizes a 12 column grid system. Each column needs to be defined in a div, and a set of columns should be within a div of class "row". To take up 100% of the screen, column class assignments should total 12 within each row. To facilitate this, classes exist from .col-1 through .col-12.

A couple of examples:

3 columns of 5/12, 5/12, and 1/6 widths from left to right:

    <div class="row">
      <div class="col-5">.col-5</div>
      <div class="col-5">.col-5</div>
      <div class="col-2">.col-2</div>
    </div>

2 columns, each taking up 50% of the width:

    <div class="row">
      <div class="col-6">.col-6</div>
      <div class="col-6">.col-6</div>
    </div>
    

This framework also has navbar classes built in for a navbar fixed to the top of the page. There are two style options: light (".nav-light") and dark(".nav-dark"). These classes should be applied to a nav element. Links should be built inside the navbar as <a> elements, and an option is available to make the selected link active ("nav-active").

An example: 

    <nav class="nav-dark">
      <a href = "#" class="nav-active">Home</a>
      <a href = "#">About</a>
    </nav>

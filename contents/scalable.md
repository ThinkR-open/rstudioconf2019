## Scale Big Shiny Apps 

Most of the time, building a big Shiny App means that it will be scaled to numerous users, that it will be used for a (relatively) long time, and that you might implement new things on it in the future.

<ul class="list-unstyled">
  <li><i class="fa fa-angle-right"></i> JavaScript can make the app lighter (don't make R do things it doesn't need to do).</li>
  <li><i class="fa fa-angle-right"></i> Learn `{future}` and `{promises}`.</li>
  <li><i class="fa fa-angle-right"></i> Modules also allow to implement new things more easily.</li>
  <li><i class="fa fa-angle-right"></i>It's easier to maintain "bite size" pieces of code than on monolithic, 1000s of lines long files.</li>
</ul>


# shiny-object

Used for the purposes of my blog post http://www.andrewchallis.co.uk/category/shiny/docker-creating-a-portable-image-recognition-app-with-tensorflow-and-shiny/

To run the container:

`docker run —rm -p 3838:3838 \
-v PATH/TO/SHINY/shinyapps:/srv/shiny-server/ \
-v PATH/TO/SHINY/shinylog/:/var/log/shiny-server/ \
challisa/shiny-object`

Then put the Shiny App in a directory PATH/TO/SHINY/shinyapps/appdir/<your-shiny-app>

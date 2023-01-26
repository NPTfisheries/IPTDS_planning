library(shiny)

#UI
ui <- fluidPage(
  titlePanel("IPTDS Planning"),
  mainPanel(style='width:100% !important; height:90vh;',
    helpText('Please be patient while the map loads.'),
    includeHTML(path='./maps/iptds_pop_prioritization_v2.html')
    )
)

# Server
server <- function(input, output) {
}

# App 
shinyApp(ui = ui, server = server)

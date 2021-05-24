library(shiny)
library(shinydashboard)
library(ggplot2)
library(ggplot2movies)
library(dplyr)

df <- as.data.frame(movies)

# header
header <- dashboardHeader(
  title = "Menu")

# sidebar
sidebar <- dashboardSidebar(
  sidebarMenu(
  menuItem("Main dashboard", tabName = "dash", icon = icon("dashboard")),
  menuItem("KPI 1", tabName = "kpi1", icon = icon("caret-right")),
  menuItem("KPI 2", tabName = "kpi2", icon = icon("caret-right")),
  menuItem("KPI 3", tabName = "kpi3", icon = icon("caret-right")),
  menuItem("KPI 4", tabName = "kpi4", icon = icon("caret-right"))
))

# body
body <- dashboardBody(
    box(),

    box(),

    box(),

    box()
  )

shinyApp(
  ui = dashboardPage(header, sidebar, body),
  server <- function(input, output) {}
)

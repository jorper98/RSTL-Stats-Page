# RSTL-Stats-Page
Really-Simple-Traffic-Logger-Stats-Page

This script generates a basic web statistics page based on log files generated by Really-Simple-Traffic-Logger (RSTL) script which are stored in .\data

# Background: ;
  Really-Simple-Traffic-Logger (RSTL) is a basic PHP=based website traffic logger which incorporates log statistics into any web page.   
    
  However the original package did not have a way to display the data
        
        At first I created a quick table-based page to display a summary per day.  
        It included:  
            Date, Total Page Views, Total Unique IPs, and Total Unique Referers
        (as I said a simple summary)
        
        Then I started to look for a simpler / more graphical way of displaying the data  and ran into TinyAnalytics which used Google Graphs to  create the graph, so I combined the two.
        
        I am posting it here to help others.   
      
# To use it 
    1) Drop this file at  the root folder where you placed RSTL package.   I typically use /stats
    2) Change the password
    
    It should work withouy any modifications. Everything is includeds.
    It makes utilizes:  
        - Google Charts https://developers.google.com/chart/interactive/docs/
        - jquery
        
# Based on: 
        - data gathered with:  Really-Simple-Traffic-Logger
                https://github.com/VR51/Really-Simple-Traffic-Logger
        
        - graphical data display TinyAnalytics
              https://github.com/benyafai/TinyAnalytics

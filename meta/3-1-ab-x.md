---

layout: indicator        
goal: '3'        
indicator: '3.1.ab-x'        
indicator_display: '3.1.a, b'        
indicator_sort_order: '3-1-ab-x'        
permalink: /3-1-ab-x/        

#
reporting_status: complete        
published: true        
data_non_statistical: false   
dialogue: deleted     


#Metadata        
national_indicator_available: Vorzeitige Sterblichkeit        

dns_indicator_definition: Der Indikator umfasst die Todesfälle der weiblichen (3.1.a) und männlichen (3.1.b) unter 70-jährigen Bevölkerung, bezogen auf 100&nbsp;000&nbsp;Einwohnerinnen und Einwohner der alten Europastandardbevölkerung unter 70&nbsp;Jahren (unter Ausschluss der unter 1-Jährigen).        

dns_indicator_intention: Bis zum Jahr 2030&nbsp;soll die vorzeitige Sterblichkeit bei Frauen bei höchstens 100&nbsp;und bei Männern bei höchstens 190&nbsp;Todesfällen je 100&nbsp;000&nbsp;Einwohnerinnen und Einwohnern liegen.        


indicator_name: Vorzeitige Sterblichkeit        
section: Gesundheit und Ernährung        
postulate: Länger gesund leben        
target_id: 3.1.1        
previous: 3-1-ab        
next: 3-1-cd        

#Sources        

source_active_1: true
source_organisation_1: <a href="https://www.destatis.de/DE/Home/_inhalt.html" target="_blank">Statistisches Bundesamt</a>
source_organisation_1_short: <a href="https://www.destatis.de/DE/Home/_inhalt.html" target="_blank">Statistisches Bundesamt</a>
source_organisation_logo_1: <a href="https://www.destatis.de/DE/Home/_inhalt.html" target="_blank"><img src="https://dns-indikatoren.de/public/OrgImgDe/destatis.png" alt="Statistisches Bundesamt" title=" Klicken Sie hier um zur Homepage der Organisation Statistisches Bundesamt zu gelangen." style="height:60px; width:148px; border:transparent"/></a>
source_url_1: 'https://www.gbe-bund.de/gbe/pkg_isgbe5.prc_menu_olap?p_uid=gast&p_aid=52889592&p_sprache=D&p_help=2&p_indnr=562&p_indsp=3194&p_ityp=H&p_fid='
source_url_text_1: Vorzeitige Sterblichkeit


graph_target_points:
  - xValue: 32
    yValue: 100
    pointStyle: triangle
    rotation: 180
    borderColor: "#2d5f21"
    preset: target_points
  - xValue: 32
    yValue: 190
    pointStyle: triangle
    rotation: 180
    borderColor: "#93c587"
    preset: target_points
  - type: label
    xValue: 31.9
    yValue: 60.0
    backgroundColor: transparent
    content: ['Ziel:','100']
    font: {
      size: 14
      }
    borderColor: transparent
  - type: label
    xValue: 31.9
    yValue: 225.0
    backgroundColor: transparent
    content: ['Ziel:','190']
    font: {
      size: 14
      }
    borderColor: transparent        

data_show_map: true        
copyright: '&copy; Statistisches Bundesamt (Destatis), 2024'        

data_footnotes: "Todesfälle pro 100&nbsp;000&nbsp;Einwohner/-innen unter 70&nbsp;Jahren (ohne unter 1-Jährige).<br>• Altersstandardisierung: alte Europabevölkerung."        

graph_title: Vorzeitige Sterblichkeit        




graph_annotations:
  - value: 100
    label:
      content: Ziel 2030 - a) Frauen
      position: left
      backgroundColor: transparent
      color: transparent
    preset: target_line
    borderColor: transparent
  - value: 190
    label:
      content: Ziel 2030 - b) Männer
      position: left
      backgroundColor: transparent
      color: transparent
    preset: target_line
    borderColor: transparent        

precision:
  - decimals: 0.0


span_gaps: true        
show_line: true        

graph_type: line        

data_start_values:
  - field: time series
    value: premature death (women)
  - field: time series
    value: premature death (men)        



graph_stepsize:
  - step: 50.0




national_geographical_coverage: Deutschland                
---

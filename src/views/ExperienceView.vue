<script setup lang="ts">
import card from '../components/card.vue'

</script>

<template>
  <div>
    <h2>Work Experience</h2>
    <p>
      Here are a few positions and companies I've worked on recently.
    </p>
  </div>
  <div class="row">
    <div class="col-sm-12">
      <div class="card-deck">
      
        <card card_header="July 2024 – Today" card_title="FIS ENGINEER – INVENTEC" card_text="• Configuration and maintenance of computer equipment." 
          card_href=""
          card_href_text="" />

        <card card_header="September 2021 – February 2024" card_title="OPEX & METHODS ENGINEER – APTIV" card_text="• Standardization of workflow.
         • Development and implementation of databases in MS Access.
         • Improved performance in Excel VBA.
         • Balance workloads on machines.
         • Operational training." card_href="" card_href_text="" />

        <card card_header="April 2021 - August 2021" card_title="WEB DEVELOPER – APTIV" card_text="• Full-Stack Developer: Development and implementation of a web system to collect Scrap in the manufacturing
          area using NET MVC #C, SQL Server and adding validations and user interactions with jQuery. • Frontend Developer: Development and Implementation of improvements in UI/UX: VueJS consuming an API and
          Vanilla JavaScript and CSS." card_href="" card_href_text="" />

        <card card_header="January 2019 – June 2020" card_title="WEB DEVELOPER - FREELANCE" card_text="• Frontend Developer: Development and Implementation of improvements in UI/UX: VueJS consuming an API and
          Vanilla JavaScript and CSS.
          • Development of a web application in Java to facilitate the display and selection of a file catalog, save it in
          the MySQL database and send the request by mail and execute the file transfer using Windows BAT.
          " card_href="" card_href_text="" />

        <card card_header="August 2019 – November 2020" card_title="DEGREE PROJECT" card_text="• Computer vision: Development and Implementation of prototype of artificial vision system
          for detecting careless drivers using python,          
          OpenCV and the Keras interface to obtain a deep neural network model." card_href="" card_href_text="" />

      </div>
    </div>
  </div>

</template>

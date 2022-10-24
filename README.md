<div>
  <img src='https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white'>
  <img src='https://img.shields.io/badge/Drupal-0678BE?style=for-the-badge&logo=drupal&logoColor=white'>
<div>

# Docker-compose-assignment

Create a custom drupal website with a postgres database.

How to use:

<ol>
  <li>
  <h5>Configure Custom password in docker-compose.yml(under postgres enviropment)</h5>
  </li>
  <li>
  <h5>Run:</h5>
   <code>
    docker-compose-up
   </code>
  </li>
  <li>
   <h5>Visit localhost:8080, follow the instructions :
   <code>
    databasename=postgres
   </code>
   </br>
   <code>
    databaseusername=postgres
   </code>
  </br>
  Click on advanced and set:
   <code>
    host=postgres
   </code>
   </h5>
  </li>
</ol>

<h5>Tear Down :
  <code>Docker compose down -v</code>
to clear persistant data</h5>

## Endpoints docs 
   
   ** Functions of the API **
   
   The service is running on https://issuesprovider.herokuapp.com/ and the routes that can 
   be called in order to save the information to the database  is listed below. 
   
   - get_bug(#,project,criteria)
        
        - # > number of bugs
        - project > name of the project and service
        - criteria (important bugs)
   
   - get_cand_devs(project)
   
        - project and service 
 
   ** GET_BUG ENDPOINTS **
   
   http://issuesprovider.herokuapp.com/api/v1/gitlab/2rbdPSvGXzbxYSCUoszC/1206370/bugs
   
   http://localhost:3000/api/v1/service/github/zdr00/repos
   http://localhost:3000/api/v1/service/bitbucket/zdr00/repos
   http://localhost:3000/api/v1/service/gitlab/2rbdPSvGXzbxYSCUoszC/repos
   
   http://localhost:3000/api/v1/service/gitlab/2rbdPSvGXzbxYSCUoszC/1206370/bugs
   http://localhost:3000/api/v1/service/bitbucket/zdr00/menubarmac/bugs
   http://localhost:3000/api/v1/service/github/rails/rails/bugs
   
   
   ** GET_CAND_DEVS(project) **
   
   -- dev --
      
   http://localhost:3000/api/v1/service/github/rails/rails/users
   http://localhost:3000/api/v1/service/gitlab/2rbdPSvGXzbxYSCUoszC/1206370/users
   http://localhost:3000/api/v1/service/bitbucket/zdr00/menubarmac/users
      
   http://localhost:3000/api/v1/eclipse/:product/:component/users
   http://localhost:3000/api/v1/bugparty/:product/:component/repos
   http://localhost:3000/api/v1/bugzilla/:product/:component/bugs
   
   https://bugzilla.mozilla.org/rest/bug/707428/history
   
   
## Enterprise url's
   
   ** BITBUCKET URLS **

   https://api.bitbucket.org/2.0/repositories/abram
   https://api.bitbucket.org/2.0/repositories/zdr00/menubarmac/issues

   ** GITLAB URLS **

   https://gitlab.com/api/v3/projects/?private_token=2rbdPSvGXzbxYSCUoszC
   https://gitlab.com/api/v3/projects/1206370/members?private_token=2rbdPSvGXzbxYSCUoszC
   https://gitlab.com/api/v3/projects/1206370/issues?private_token=2rbdPSvGXzbxYSCUoszC

   ** BUGPARTY URLS **

   http://localhost:8080/bugparty/:name/bugs
   http://localhost:8080/bugparty/:name/reports
   http://localhost:8080/bugparty/:name/topics/alldates

   ** GITHUB URLS **

   https://api.github.com/users/zdr00/repos?per_page=100
   https://api.github.com/repos/mojombo/grit/issues

   ** BUGZILLA URLS **

   https://bugzilla.mozilla.org/rest/user?names=lhenry@mozilla.com
   https://bugzilla.mozilla.org/rest/bug?component=Activity%20Streams%3A%20Timeline&product=Firefox
   https://bugzilla.mozilla.org/rest/product/firefox
   https://bugzilla.mozilla.org/rest/bug?assigned_to=lhenry@mozilla.com
   
   https://bugzilla.mozilla.org/rest/bug/707428/history
   
   
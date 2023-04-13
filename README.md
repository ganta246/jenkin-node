# jenkin-node
this is a jenkins node
poll scm 
create a job  new item : demo-job and select free style project and ok click
configure click  GO TO the source code management git select repository url :paste here and go to build triger poll scm select : ******
go to build  excute shell select echo update
sava and click
completed poll scm
periodically

go to jenkins dashboard create job new item click name :jenkins-demo
select freestyle project and ok click
go to configure click select to the source code management git select repository url : paste here
advanced  build options click periodically select  name : ******
go to build excute shell: date
save and apply click

sonarqube integrate jenkins with using pipeline 
go to jenkins dashboard
manage jenkins and manage plugins click and available sonarqube scanner install without restart click

configure source code management  git select give the repository url : paste
go to the build name: sonarqube
sonarqube url: paste here
apply and save build now click
go to manage jenkins and global configuration click github project select url paste here
go to the maven install and name : sonarqube
                             version : paste here
                             
   apply and save  click
   
   go to the create project name:jenkins-pipeline and pipeline select and ok click
   
   go to pipeline 
    after complete appy and save build now fineshed success
    
    
    
    nexus integrate jenkins with using pipeline
    
  go to the create job new item : nexus3-job and freestyle project select and ok click 
  manage jenkins and manage plugins and available artifact uploader  select install without restart click  fineshed : sucess
  go to the configure click description : this is a nexus 3 job
  
  10/20 
  go to source code management git select and repository url :paste here
 select artifact uploader name : nexus3
 protocol :http
 version nexus 3.8.9
 nexus repository maven hosted select 
 apply and save click fineshed sucess
 pipeline syntax click  
 pipeline after complted apply and  save
   build now click finished  success
   
 maven integratre jenkins with using pipeline
 
 create a job new item name: maven-demo and select maven-project and ok click
configure click go to source code management  git select repository url: paste here
go to build invokepe top level  target select
 name:pom.xml and goals clean install
 apply and save click  build now click 
 fineshed: Sucess
 
 global configuration system
 
go to maven build select name : maven3 and version : maven3.8.6
apply and save click  go to pipeline completed build now click fineshed :sucess

slave and master jenkins using run the job pipeline
jenkins server and slave node

pipeline {
      agent any
        stages{
        


 
 
 
 
 
           



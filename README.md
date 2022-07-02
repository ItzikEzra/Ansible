<b>This repo will manage my playbook for ci cd with azur edevops.</b> </br></br>
to use it, you will need to attached an hosts file with the details for your vms.</br>
also, you will need to declere the foloowing vars to make it work: </br>
to make it more safe, I injected the vars form azure devops libary and used in task "replece token", </br> 
thats why itr will look like \__var__: </br>
list:</br>
 LOADBALNCERIP: \__LOADBALNCERIP__ </br>
    OKTAORGIL: \__OKTAORGIL__</br>
    OKTACLIENTID: \__OKTACLIENTID__</br>
    OKTACLIENTSECRET: \__OKTACLIENTSECRET__</br>
    PGHOST: \__PGHOST__</br>
    PGUSERNAME: \__PGUSERNAME__</br>
    PGDATABASE: \__PGDATABASE__</br>
    PGPASSWORD: \__PGPASSWORD__</br>



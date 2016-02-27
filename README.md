####How to setup the  Dashboard development environment

* Install go-lang https://golang.org/
* checkout the source code available at https://apremalal@bitbucket.org/apremalal/wifi-manager.git	
* Execute wifi-manager/build.sh 
    * This will create a distribution pack (wifi-manager.zip)
* Installing the DataBase
    * Create a Db with name ‘dashboard’
    * Update the wifi-manager/server/resources/scripts/setup_config.sh with your mysql parameters
    * Execute wifi-manager/server/resources/scripts/setup.sh
* Configure server parameters in  wifi-manager/server/configs/config.yaml
* To run the server execute wifi-manager/server/server.sh
* Navigate to https://localhost:8081/dashboard/
* Username : admin@isl.com Password: admin

#### IDE support for go-lang

* https://github.com/golang/go/wiki/IDEsAndTextEditorPlugins

#### Configure Redis

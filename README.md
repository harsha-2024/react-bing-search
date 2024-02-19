# react-bing-search
Connect Server URLs

Table	       	URL
Entity (table) List		https://connect_server_url/api.rsc/
Metadata for table VideoSearch		https://connect_server_url/api.rsc/VideoSearch/$metadata?@json
VideoSearch		https://connect_server_url/api.rsc/Bing_VideoSearch

Connect On-Prem (Server) URLs

Table	       	URL
Entity (table) List		http://localhost:8080/odata.rsc/
Metadata for table VideoSearch		http://localhost:8080/odata.rsc/VideoSearch/$metadata?@json
VideoSearch		http://localhost:8080/odata.rsc/Bing_VideoSearch

npm install -g babel
npm install -g babel-cli

cd ./apiserver-react

npm install

npm start

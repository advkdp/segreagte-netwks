# segreagte-netwks
here we create webserver - nginx connected to 2 ntwks app1_net and app2_net
and then create 2 httpd servers
  1st httpd assign app1_net
  2nd httpd assign app2_net
  so when we run docker-compose up and see in browser loaclhost:8080 it shows on xminal request for app1
  & if we put localhost:8080/app2 then on xminal it shows request for app2

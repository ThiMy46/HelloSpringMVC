# HelloSpringMVC
Tạo 1 project mẫu về config ban đầu của Spring MVC \n
pom.xml: add dependencies \n
web.xml:  +khai báo dispartcherServlet - chứa tên file chứa applicationconfig \n
          +Khai báo đường dẫn đầu tiên được truy cập - gọi tới dispartcherServlet \n
spring-config.xml:  + config componant được scan \n
                    + config link rút gọn của view - default: view nằm trong "webapp"-prefix, đuôi ".jsp"-suffix \n

@Controller \n
Khai báo đường dẫn nào sẽ tới view nào, và có kèm model thì đc gửi lun ở đây \n
  @RequestMapping() - chứa link đường dẫn mà chúng ta truy cập và method GET,POST,.. kèm theo \n
  
  

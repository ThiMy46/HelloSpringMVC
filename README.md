# HelloSpringMVC
Tạo 1 project mẫu về config ban đầu của Spring MVC
pom.xml: add dependencies
web.xml:  +khai báo dispartcherServlet - chứa tên file chứa applicationconfig
          +Khai báo đường dẫn đầu tiên được truy cập - gọi tới dispartcherServlet
spring-config.xml:  + config componant được scan
                    + config link rút gọn của view - default: view nằm trong "webapp"-prefix, đuôi ".jsp"-suffix

@Controller
Khai báo đường dẫn nào sẽ tới view nào, và có kèm model thì đc gửi lun ở đây
  @RequestMapping() - chứa link đường dẫn mà chúng ta truy cập và method GET,POST,.. kèm theo
  
  

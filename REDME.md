DigitalMoneyHouse/
├── eureka-server/                         # Servicio de registro (Eureka)
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── resources/
│   │   │       ├── application.yml
│   └── pom.xml
├── config-server/                         # Servidor de configuración centralizada
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── resources/
│   │   │       ├── application.yml
│   └── pom.xml
├── gateway/                               # API Gateway
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── resources/
│   │   │       ├── application.yml
│   └── pom.xml
├── user-service/                          # Microservicio de Usuarios (registro e inicio de sesión)
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/digitalmoneyhouse/user/
│   │   │   │       ├── controller/
│   │   │   │       ├── service/
│   │   │   │       ├── model/
│   │   │   │       ├── repository/
│   │   │   │       └── security/           # Implementación de seguridad JWT
│   │   │   └── resources/
│   │   │       ├── application.yml
│   └── pom.xml
├── wallet-service/                        # Microservicio de Billetera (gestión de saldo y movimientos)
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/digitalmoneyhouse/wallet/
│   │   │   │       ├── controller/
│   │   │   │       ├── service/
│   │   │   │       ├── model/
│   │   │   │       └── repository/
│   │   │   └── resources/
│   │   │       ├── application.yml
│   └── pom.xml
├── payment-service/                       # Microservicio de Pago (gestión de métodos de pago)
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/digitalmoneyhouse/payment/
│   │   │   │       ├── controller/
│   │   │   │       ├── service/
│   │   │   │       ├── model/
│   │   │   │       └── repository/
│   │   │   └── resources/
│   │   │       ├── application.yml
│   └── pom.xml
├── transaction-service/                   # Microservicio de Transacciones (registro de actividad)
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/digitalmoneyhouse/transaction/
│   │   │   │       ├── controller/
│   │   │   │       ├── service/
│   │   │   │       ├── model/
│   │   │   │       └── repository/
│   │   │   └── resources/
│   │   │       ├── application.yml
│   └── pom.xml
├── common-library/                        # Librería común para DTOs y clases compartidas
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/digitalmoneyhouse/common/
│   │   │   │       ├── dto/
│   │   │   │       └── exception/
│   │   │   └── resources/
│   └── pom.xml
├── docs/                                  # Documentación del proyecto
│   ├── swagger/                           # Documentación Swagger para los endpoints de la API
│   └── README.md                          # Documentación general del proyecto
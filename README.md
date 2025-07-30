
# 🏦 Banking Application

A simple Spring Boot-based Banking Application that demonstrates core banking features like account creation, transactions, and user management.

## 🚀 Features

- User registration and authentication
- Account creation and management
- Transaction processing (debit/credit)
- View account balance and transaction history
- Configurable via `application.properties`

## 🛠️ Tech Stack

- Java 17+
- Spring Boot
- Maven
- RESTful APIs
- H2 / MySQL (configure in `application.properties`)

## 📦 Project Structure

```
banking.application/
├── src/
│   └── main/
│       ├── java/
│       │   └── banking/
│       │       ├── controller/
│       │       ├── service/
│       │       ├── model/
│       │       └── repository/
│       └── resources/
│           └── application.properties
├── pom.xml
└── README.md
```

## ▶️ Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.x

### Run the Application

```bash
git clone https://github.com/your-username/banking.application.git
cd banking.application
mvn spring-boot:run
```

### Build the Application

```bash
mvn clean install
```

## ⚙️ Configuration

Edit `src/main/resources/application.properties` to set DB configurations, ports, etc.

Example:
```properties
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
```


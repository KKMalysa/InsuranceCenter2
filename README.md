# InsuranceCenter

projekt aplikacji „centrum ubezpieczeń” dla klienta będącego firmą ubezpieczeniową / agentem ubepieczeniowym.

wykorzystywane biblioteki:
- Lombok (redukuje boiler code)
- Spring web (do RESTful api, spring MVC, tomcat, servlety etc.)
- MySQL Driver – relacyjna baza danych (sterownik)
- Spring Data JPA – przy pomocy java persistance API zapisuje dane SQL-owo korzystając ze Spring Data i Hibernate’a. wzięty, bo dzięki niemu szybko pisze się rozwiązania.
- Spring Boot Actuator – feature, który dodaje health end pointy (monitorowanie parametrów aplikacji typu użwana pamięc, wątki etc. W połączeniu z narzędziem typu 
  Prometheus Monitoring można na wykresach wyświetlić jak to się buja.

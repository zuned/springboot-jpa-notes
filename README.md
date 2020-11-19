# SpringBoot JPA with H2:
	1. Include dependency jpa-starter and h2_db dependency in pom.xml
	2. update application properties with:
		* spring.datasource.url=jdbc:h2:mem:testdb
		* spring.data.jpa.repositories.bootstrap-mode=default

		* spring.jpa.show-sql=true
		* spring.h2.console.enabled=true
	
	3. to make sure defualt data insert you can data.sql in resource folder

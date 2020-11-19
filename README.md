# SpringBoot JPA with H2:
	Include dependency jpa-starter and h2_db dependency in pom.xml
	update application properties with:
		spring.datasource.url=jdbc:h2:mem:testdb
		spring.data.jpa.repositories.bootstrap-mode=default

		spring.jpa.show-sql=true
		spring.h2.console.enabled=true
	
	to make sure defualt data insert you can data.sql in resource folder

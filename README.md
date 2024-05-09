# Getting Started

### Create project Spring boot

`dependency: Spring Web`

### Config application.yaml
####
	server:
		ssl:
			key-alias: spring-https
			key-store: classpath:watermelon.jks
			key-store-type: JKS
			key-password: 123456
			
#### Win + R: 
	keytool -genkey -alias spring-https -storetype JKS -keyalg RSA -keysize 2048 -validity 365 -keystore watermelon.jks
##### Ex:
	Enter keystore password: 123456
	What is your first and last name?
	[Unknown]:  Lenh Nguyen
	What is the name of your organizational unit?
	  [Unknown]:  NLU
	What is the name of your organization?
	  [Unknown]:  Nong Lam University
	What is the name of your City or Locality?
	  [Unknown]:  Ho Chi Minh City
	What is the name of your State or Province?
	  [Unknown]:  Ho Chi Minh City
	What is the two-letter country code for this unit?
	  [Unknown]:  VN
	Is CN=Lenh Nguyen, OU=NLU, O=Nong Lam University, L=Ho Chi Minh City, ST=Ho Chi Minh City, C=VN correct?
	  [no]:  yes
	
#### Win + S:
keyword: watermelon.jks
-> Copy file paste into the folder resources of project Spring
